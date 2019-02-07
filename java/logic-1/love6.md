public boolean love6(int a, int b) {
  return(a==6||b==6)?true:
  ((a+b==6)?true:
  (Math.abs(a-b)==6)?true:false
  );
}
