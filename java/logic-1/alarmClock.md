public String alarmClock(int day, boolean vacation) {
  return(vacation)?
  ((day>=1 && day<=5)?"10:00":"off"):
  ((day>=1 && day<=5)?"7:00":"10:00");
}
