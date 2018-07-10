# add_min_in_to-timestamp

       String myTime = "14-10-2018 14:10";
       
       SimpleDateFormat df = new SimpleDateFormat("dd-MM-YYYY HH:mm");
       
       Date d = df.parse(myTime); 
       
       Calendar cal = Calendar.getInstance();
       
       cal.setTime(d);
       
       cal.add(Calendar.MINUTE, 10);
       
       String newTime = df.format(cal.getTime());
       
