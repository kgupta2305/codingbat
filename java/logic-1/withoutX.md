public String withoutX(String str) {
  return(str.length()>=2)?((str.substring(0,1).equals("x"))?
  ((str.substring(str.length()-1,str.length()).equals("x"))?
  (str.substring(1,str.length()-1)):
  str.substring(1,str.length())):
  ((str.substring(str.length()-1,str.length()).equals("x"))?
  (str.substring(0,str.length()-1)):
  str)):
  ((str.length()==1) 
  && (str.equals("x")))?
  "":
  str;
}
