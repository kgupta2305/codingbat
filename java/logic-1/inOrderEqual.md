public boolean inOrderEqual(int a, int b, int c, boolean equalOk) {
  if(equalOk){
    if(a<=b && b<=c){
      return true;
    } else{
      return false;
    }
  } else{
    if(b>a && b<c){
      return true;
    } else{
      return false;
    }
  }
}
