public String lastChars(String a, String b) {
  return(a.length()==0)?
  ("@"+((b.length()==0)?
  "@":
  (b.substring(b.length()-1,b.length())))):
  ((a.substring(0,1) + ((b.length()==0)?
  "@":
  (b.substring(b.length()-1,b.length())))));
}
