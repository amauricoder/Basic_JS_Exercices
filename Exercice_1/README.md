Write a JavaScript program to display the current day and time in the following format.
Sample Output : Today is : Tuesday.
Current time is : 10 PM : 30 : 38

**Explanation** 
''https://www.w3resource.com/javascript-exercises/javascript-basic-exercise-1.php''

Declaring a JavaScript date : In JavaScript Date objects are based on a time value that is the number of milliseconds since 1 January, 1970 UTC. You can declare a date in the following ways :

new Date();
new Date(value);
new Date(dateString);
new Date(year, month[, day[, hour[, minutes[, seconds[, milliseconds]]]]]);

The getDay() method is used to get the day of the week for the specified date according to local time, where 0 represents Sunday. The value returned by getDay() is an integer corresponding to the day of the week: 0 for Sunday, 1 for Monday, 2 for Tuesday, and so on.

The getHours() method is used to get the hour for a given date, according to local time. The value returned by getHours() is an integer between 0 and 23.

The getMinutes() method is used to get the minutes in the specified date according to local time. The value returned by getMinutes() is an integer between 0 and 59.

The getSeconds() method is used to get the seconds in the specified date according to local time. The value returned by getSeconds() is an integer between 0 and 59.

AM and PM : AM stands for 'ante meridiem', which means 'before noon' in Latin, while PM stands for 'post meridiem', which means 'after noon' in Latin.
12-Hour Periods : Nowadays most clocks are 12-hour clocks â€“ they divide the 24 hours in a day into two 12-hour periods.
Ante meridiem: Before noon - Between midnight (0:00) & noon (12:00)
Post meridiem: After noon Between noon (12:00) & midnight (0:00)