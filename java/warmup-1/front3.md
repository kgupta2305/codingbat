public String front3(String str) {
  String fin = "";
  if(str.length()>=3){
    fin = str.substring(0,3);
    return fin+fin+fin;
  } else{
    return str+str+str;
  }
}
