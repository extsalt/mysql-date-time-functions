# Mysql Date Time Functions

https://mariadb.com/kb/en/date-time-functions/

#### Now
`select now();` -- date and time, timestamp

#### Current date
`select curdate();` -- current date

#### Time in 24-hour format
`select curtime();` -- time in 24-hour format

`select year(now());` --year

`select month(now());` --month

`select day(now());` --day

`select hour(now());` --hour

`select minute(now());` --minute

`select second(now());` --second

`select dayname(now());` -- name of day

`select date(now());` -- date in YYYY-MM-DD

 `select curtime();` --get current time

 `select current_timestamp();` --get current timestamp

 `SELECT DATEDIFF('2007-12-31 23:59:59','2007-12-30');` --date difference

 `SELECT '2008-12-31 23:59:59' + INTERVAL 1 SECOND;` -- perform date airthmatic

 `SELECT INTERVAL 1 DAY + '2008-12-31';` --perform date airthmatic

 `SELECT DATE_FORMAT('2009-10-04 22:23:00', '%W %M %Y');` --https://mariadb.com/kb/en/date_format/

 `SELECT DAYNAME('2007-02-03');` --get day name

 `SELECT DAYOFMONTH('2007-02-03');` --day of month

 `SELECT DAYOFWEEK('2007-02-03');` --day of week	

 `SELECT DAYOFYEAR('2018-02-16');` --day of year

 `SELECT TIMESTAMP('2003-12-31');` -- create a timestamp

 `select time(now());`--time from current timestamp
