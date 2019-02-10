public String minCat(String a, String b) {
  return(a.length()>0 && b.length()>0)?
  ((a.length()==b.length())?
  (a+b):
  ((a.length()>b.length())?
  (a.substring(a.length()-b.length(),a.length()) + b):
  (a + b.substring(b.length()-a.length(),b.length())))):
  "";
}
