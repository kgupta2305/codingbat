public String comboString(String a, String b) {
  String sht = (a.length()>b.length())?b:a;
  String lng = (a.length()<b.length())?b:a;
  return (sht+lng+sht);
  
}
