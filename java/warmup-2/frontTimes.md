public String frontTimes(String str, int n) {
   String ans=""; 
   for (int i=0;i<n;i++){
     if(str.length()>=3){
       ans+=str.substring(0,3);  
     } else{
       ans+=str; 
     }
   } 
   return ans; 
}
