日期和时间处理函数

日期和时间采用相应的数据类型和特殊的格式存储，以便能快速和
有效地排序或过滤，并且节省物理存储空间。

一般，应用程序不使用用来存储日期和时间的格式，因此日期和时
间函数总是被用来读取、统计和处理这些值。由于这个原因，日期和时
间函数在MySQL语言中具有重要的作用。


| Name          |   Description                                     |            中文          |
| ------------- |:-------------------------------------------------:| ------------------------:|
| ADDDATE()     | Add time values (intervals) to a date value       | 增加一个日期（天、周等） |
| ADDTIME()     | Add time                                          | 增加一个时间（时、分等） |               |
| CONVERT_TZ()	| Convert from one time zone to another             |   |
| CURDATE()	    | Return the current date | | 
| CURRENT_DATE(), CURRENT_DATE | 	Synonyms for CURDATE()  | | 
| CURRENT_TIME(), CURRENT_TIME	| Synonyms for CURTIME()| | 
| CURRENT_TIMESTAMP(), CURRENT_TIMESTAMP	| Synonyms for NOW()| | 
| CURTIME()| 	Return the current time| | 
|  DATE()| 	Extract the date part of a date or datetime expression| | 
