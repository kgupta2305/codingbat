public String deFront(String str) {    
  return(str.length()>=2)?
  (
    (str.substring(0,1).equals("a"))?
      ((str.substring(1,2).equals("b"))?
        (str.substring(0,str.length())):
        (str.substring(0,1) + str.substring(2,str.length()))):
      ((str.substring(1,2).equals("b"))?
        (str.substring(1,2)+str.substring(2,str.length())):
        (str.substring(2,str.length())))):
    "";
}
