public String startOz(String str) {
  if(str.length()>=2){
    if(str.substring(0,2).equals("oz")){
      return "oz";
    } else if (str.substring(0,1).equals("o")){
      return "o";
    } else if (str.substring(1,2).equals("z")){
      return "z";
    }
  } else if (str.length()>=1 &&str.substring(0,1).equals("o")){
      return "o";
    } 
  return "";
}
