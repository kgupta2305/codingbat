public String everyNth(String str, int n) {
  String ans="";
  for(int i=0;i<str.length();i++){
      //System.out.println(str.substring(i,i+1));
    ans +=str.substring(i,i+1);
    i+=n-1;
  }
  return ans;
}
