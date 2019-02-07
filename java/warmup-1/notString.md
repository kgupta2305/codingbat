public String notString(String str) {
  if (str.length()>2){
    String strin = str.substring(0,3);
  if(strin.equals("not")){
    return str;
  } else {
    return "not " + str;
  }
  } else {
    return "not " + str;
  }
  
}
