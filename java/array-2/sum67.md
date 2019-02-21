public int sum67(int[] nums) {
  int sum=0;
  int count=0;
  boolean start=false;
  for(int i=0;i<nums.length;i++){
    if(nums[i]==6){
      count++;
      start=true;
    } else if ((nums[i]==7) && (count>0)){
      start=false;
      count=0;
    } else if(start!=true){
      sum+=nums[i];
    }
  }
  return sum;
}
