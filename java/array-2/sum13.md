public int sum13(int[] nums) {
  int ans=0;
  int sum=0;
  if(nums.length==0){
    return 0;
  } else{
    for(int i=0;i<nums.length;i++){
      if(nums[i]==13){
        i++;
      } else{
        sum+=nums[i];
      }
    }
    return sum;
  }
}
