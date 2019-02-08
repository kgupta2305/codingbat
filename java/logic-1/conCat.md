public String conCat(String a, String b) {
  return(a.length()>0)?
  ((b.length()>0)?
  (((a.substring(a.length()-1,a.length())).equals(b.substring(0,1)))?
  (a+b.substring(1,b.length())):(a+b)):a):b;
}
