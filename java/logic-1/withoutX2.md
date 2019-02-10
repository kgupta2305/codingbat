public String withoutX2(String str) {
  return(str.length()>=2 && str.substring(0,1).equals("x"))?
  ((str.substring(0,2).equals("xx"))?
  (str.substring(2,str.length())):(str.substring(1,str.length()))):
  ((str.length()==1)?(str.equals("x")?"":str):((str.length()==0)?"":
  ((str.substring(1,2).equals("x"))?
  (str.substring(0,1) + str.substring(2,str.length())):
  str))); 
}
