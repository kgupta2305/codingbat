public String doubleChar(String str) {
  String ans="";
  String temp="";
  for (int i=0;i<str.length();i++){
    temp+=str.substring(i,i+1);
    ans=ans + temp + temp;
    temp="";
  }
  return ans;
}
