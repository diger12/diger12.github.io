# .github.io
<html>
   <head>
       <title>Clock</title>
       <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
           <script language="JavaScript">
 
               function clock() {
 
                   now = new Date();
               hours = now.getHours();
               minutes = now.getMinutes();
               seconds = now.getSeconds();
               now_time = "" + hours;
               now_time += ((minutes < 10) ? ":0" : ":") + minutes;
               now_time += ((seconds < 10) ? ":0" : ":") + seconds;
 
               date = now.getDate();
               month = now.getMonth();
               switch (month) {
 
case 0:
               month = "January";
               break;
 
               case 1:
               month = "February";
               break;
 
               case 2:
               month = "Март";
               break;
 
               case 3:
               month = "April";
               break;
 
               case 4:
               month = "May";
               break;
 
               case 5:
               month = "June";
               break;
 
               case 6:
               month = "July";
               break;
 
               case 7:
               month = "August";
               break;
 
               case 8:
               month = "September";
               break;
 
               case 9:
               month = "October";
               break;
 
               case 10:
               month = "November";
               break;
 
               case 11:
               month = "December";
               break;
 
}
 
               year = now.getYear();
               den = now.getDay();
               switch (den) {
 
case 0:
               den = "Sunday";
               break;
 
               case 1:
               den = "Monday";
               break;
 
               case 2:
               den = "Tuesday";
               break;
 
               case 3:
               den = "Wednesday";
               break;
 
               case 4:
               den = "Thursday";
               break;
 
               case 5:
               den = "Friday";
               break;
 
               case 6:
               den = "Saturday";
               break;
 
}
               year = now.getYear() + 1900;
               now_date = den + "," + date + "," + month + "," + year;
               document.getElementById('clock_show').innerHTML = "<font face='Verdana' size='8'>" + now_date + "," + now_time + "</font>";
               setTimeout("clock()", 1000);
 
}
 
           </script><html>
   <head>
       <title>Clock</title>
       <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
           <script language="JavaScript">
 
               function clock() {
 
                   now = new Date();
               hours = now.getHours();
               minutes = now.getMinutes();
               seconds = now.getSeconds();
               now_time = "" + hours;
               now_time += ((minutes < 10) ? ":0" : ":") + minutes;
               now_time += ((seconds < 10) ? ":0" : ":") + seconds;
 
               date = now.getDate();
               month = now.getMonth();
               switch (month) {
 
case 0:
               month = "January";
               break;
 
               case 1:
               month = "February";
               break;
 
               case 2:
               month = "Март";
               break;
 
               case 3:
               month = "April";
               break;
 
               case 4:
               month = "May";
               break;
 
               case 5:
               month = "June";
               break;
 
               case 6:
               month = "July";
               break;
 
               case 7:
               month = "August";
               break;
 
               case 8:
               month = "September";
               break;
 
               case 9:
               month = "October";
               break;
 
               case 10:
               month = "November";
               break;
 
               case 11:
               month = "December";
               break;
 
}
 
               year = now.getYear();
               den = now.getDay();
               switch (den) {
 
case 0:
               den = "Sunday";
               break;
 
               case 1:
               den = "Monday";
               break;
 
               case 2:
               den = "Tuesday";
               break;
 
               case 3:
               den = "Wednesday";
               break;
 
               case 4:
               den = "Thursday";
               break;
 
               case 5:
               den = "Friday";
               break;
 
               case 6:
               den = "Saturday";
               break;
 
}
               year = now.getYear() + 1900;
               now_date = den + "," + date + "," + month + "," + year;
               document.getElementById('clock_show').innerHTML = "<font face='Verdana' size='8'>" + now_date + "," + now_time + "</font>";
               setTimeout("clock()", 1000);
 
}
 
           </script>
   </head>
 
   <body onLoad="clock()">
 
       <div id="clock_show"></div>
 
 


   </head>
 
   <body onLoad="clock()">
 
       <div id="clock_show"></div>
 
 

