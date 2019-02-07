boolean doubleX(String str) {
   int count=0; 
   for (int i=0;i<str.length()-1;i++){ 
     if(str.substring(i,i+1).equals("x")){
       if(str.substring(i+1,i+2).equals("x")){
       return true; 
     } else{
       return false;
     } 
     } else{
       
     }
      } return false; 
}
