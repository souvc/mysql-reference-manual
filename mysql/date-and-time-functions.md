日期和时间处理函数

日期和时间采用相应的数据类型和特殊的格式存储，以便能快速和
有效地排序或过滤，并且节省物理存储空间。

一般，应用程序不使用用来存储日期和时间的格式，因此日期和时
间函数总是被用来读取、统计和处理这些值。由于这个原因，日期和时
间函数在MySQL语言中具有重要的作用。


| Name          |   Description                                    |           Description    |
|:--------------|:-------------------------------------------------|:-------------------------|
| ADDDATE()     | 增加一个日期（天、周等） |
| ADDTIME()     | 增加一个时间（时、分等） |               |
| CONVERT_TZ()	| 转换datetime值dt，从 from_tz 由给定转到 to_tz 时区给出的时区，并返回的结果值。 如果参数无效该函数返回NULL |
| CURDATE()	    | 返回当前日期为'YYYY-MM-DD“或YYYYMMDD格式的值，根据该函数是否用在字符串或数字语境中| 
| CURRENT_DATE(), CURRENT_DATE |  CURDATE() 函数的同义词| 
| CURRENT_TIME(), CURRENT_TIME	| CURTIME() 函数的同义词| 
| CURRENT_TIMESTAMP(), CURRENT_TIMESTAMP	| NOW() 函数的同义词| 
| CURTIME()|返回当前时间以“HH:MM:SS'或'HHMMSS' 格式的值| 
| DATE()|提取日期或日期时间表达式expr中的日期部分。  | 
| DATE_ADD()	| 日期运算|
| DATE_FORMAT()	| 按照格式的字符串格式的日期值|
| DATE_SUB()	| 日期运算|
| DATEDIFF()	| 可以使用 DateDiff 来计算两个日期之间相隔几日，或计算从今天起到年底还有多少个星期|
| DAY()	        | DAYOFMONTH() 函数的同义词   
| DAYNAME()     | 返回日期的星期名称。|
| DAYOFMONTH()  | 返回日期的月中的天，范围为0〜31。|
| DAYOFWEEK()	| 返回日期星期索引 (1 = Sunday, 2 = Monday, ., 7 = Saturday). 这些索引值对应于ODBC标准。|
| DAYOFYEAR()	| 返回年份为日期的天，范围为1至366。
| EXTRACT()| 	| 截取日期|
| FROM_DAYS()	| 给定一天数N，返回日期值。
| FROM_UNIXTIME()	| 返回表示UNIX_TIMESTAMP参数作为'YYYY-MM-DD HH:MM:SS'或YYYYMMDDHHMMSS格式的一个日期时间值|
| GET_FORMAT()	| Return a date format string| 
| HOUR()	| 返回时间的小时部分。返回值的范围为0至23的小时值。然而，TIME值的范围实际上要大得多，所以HOUR可以返回大于23的值。|
| LAST_DAY	| 需要一个日期或日期时间值，并返回该月的最后一天对应的值。 如果该参数是无效的，则返回NULL。|
| LOCALTIME(), LOCALTIME	|  NOW() 函数的同义词|
| LOCALTIMESTAMP, LOCALTIMESTAMP()	| NOW() 函数的同义词|
| MAKEDATE()	| 返回的日期，给定年份和天 - 年值。 dayofyear必须大于0，否则结果为NULL。|
| MAKETIME()	| 返回从给小时，分钟和第二个参数计算出的时间值。|
| MICROSECOND()	| 返回时间或日期时间表达式expr的微秒，这个数字范围为 0 到 999999。|
| MINUTE()	| 返回时间的分钟，范围为0至59。|
| MONTH()	| 返回日期的月份，取值范围为0〜12。|
| MONTHNAME()	| 返回日期对应月份的全名。|
| NOW()   | 返回当前日期和时间|
| PERIOD_ADD()	|  添加一个周期到一个年月|
| PERIOD_DIFF()	|  返回两个时期之间的月数|
| QUARTER()	| 从一个日期参数返回季度|
| SEC_TO_TIME()	| 转换秒为“HH:MM:SS'的格式|
| SECOND()	| 返回秒 (0-59)|
| STR_TO_DATE() | 转换一个字符串为日期|
| SUBDATE() | 当调用三个参数时，它就是 DATE_SUB() 的代名词|
| SUBTIME() | 相减时间|
| SYSDATE()| 返回函数执行时的时间|
| TIME()	| 提取表达式传递的时间部分|
| TIME_FORMAT()| 格式化为时间|
| TIME_TO_SEC()| 将参数转换成秒并返回|
| TIMEDIFF()	|相减时间|
| TIMESTAMP()	| 带一个参数，这个函数返回日期或日期时间表达式。有两个参数，参数的总和|
| TIMESTAMPADD() | 添加一个时间间隔到datetime表达式|
| TIMESTAMPDIFF()| 从日期时间表达式减去的间隔|
| TO_DAYS()	| 返回日期参数转换为天|
| TO_SECONDS()	| | 
| UNIX_TIMESTAMP() | 返回一个UNIX时间戳|
| UTC_DATE()	| 返回当前UTC日期|
| UTC_TIME()	| 返回当前UTC时间|
| UTC_TIMESTAMP()| 返回当前UTC日期和时间|
| WEEK()	| 返回周数|
| WEEKDAY()| 返回星期的索引|
| WEEKOFYEAR()	| 返回日期的日历周 (1-53)|
| YEAR()	| 返回年份|
| YEARWEEK()| 返回年份和周|



