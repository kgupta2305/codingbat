public int centeredAverage(int[] nums) {
  int smallest=0;
  int largest = 0;
  smallest = nums[0];
  for (int i=0;i<nums.length;i++){
    if (smallest>nums[i]){
      smallest=nums[i];
    } else if(largest<nums[i]){
      largest=nums[i];
    }
  }
  int count_smallest=0;
  int count_largest=0;
  int sum =0;
  int count=0;
  for (int i=0;i<nums.length;i++){
    if(nums[i]==largest){
      count_largest++;
    } else if(nums[i]==smallest){
      count_smallest++;
    } else{
      sum+=nums[i];
      count++;
    } 
  }
  if(count_smallest>1){
    sum=sum+((count_smallest-1)*smallest);
    count = count + count_smallest-1;
  }
  
  if(count_largest>1){
    sum=sum+((count_largest-1)*largest);
    count = count + count_largest-1;
  }
  
  int ans = sum/count;
  return ans;
}
