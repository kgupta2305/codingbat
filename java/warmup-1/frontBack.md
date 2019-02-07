public String frontBack(String str) {
  String temp,start = "";
  String fin ="";
  if (str.length()>1){
    temp = str.substring(0,1);
    start = str.substring(str.length()-1);
    fin = start + str.substring(1,str.length()-1) + temp;
    return fin;
  } else{
    return str;
  }
}
