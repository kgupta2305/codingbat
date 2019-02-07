public boolean makeBricks(int small, int big, int goal) { 
  if(small>0){
    if(big>0 && goal>=5){
      goal=goal-5;
      big=big-1;
      return makeBricks(small,big,goal);
    } else{
      if (goal-small <= 0){
        return true;
      } else{
        return false;
      }
    }
  } else{
    if(goal/5 <= big){
      return true;
    } else {
      return false;
    }
  }
}
