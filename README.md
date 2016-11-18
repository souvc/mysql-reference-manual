# MySQL 5.6参考手册

* Chapter 1 基本信息
     
   * 1.1 关于本手册
   * 1.2 拼写和语法约定
   * 1.3 概述的MySQL数据库管理系统     
   * 1.4 什么是新的MySQL 5.6
   * 1.5 MySQL的信息来源     
   * 1.6 如何报告错误或问题
   * 1.7 MySQL标准     
   * 1.8 学分     

* Chapter 2 MySQL的安装和升级

   * 2.1一般安装指导     
   * 2.2安装在Unix / Linux使用通用二进制代码MySQL
        * 在微软Windows 2.3安装MySQL     
   * 2.4  installing MySQL是OS X     
   * 2.5  installing是Linux下MySQL     
   * 2.6 安装MySQL使用牢不可破的Linux网络（ULN）
   * 2.7 安装在Solaris和OpenSolaris MySQL     
   * 2.8 安装MySQL在FreeBSD
   * 2.9 安装MySQL从源     
   * 2.10 安装后的设置和测试     
   * 2.11 升级MySQL或downgrading     
   * 2.12  Perl安装说明     

* Chapter 3 教程

   * 3.1连接到服务器和从服务器断开
   * 3.2进入查询
   * 3.3创建和使用数据库     
   * 3.4是对数据库和表的信息
   * 3.5使用mysql的批处理模式
       * 常见疑问3.6例     
   * 3.7使用MySQL和Apache

* Chapter 4 MySQL的程序

   * 4.1 概述MySQL程序
   * 4.2 使用MySQL的程序     
   * 4.3 MySQL服务器，服务器启动程序     
   * 4.4 MySQL安装相关程序     
   * 4.5 MySQL客户端程序     
   * 4.6 MySQL管理实用程序     
   * 4.7 MySQL程序开发工具     
   * 4.8 杂项程序     
   * 4.9 MySQL程序的环境变量

* Chapter 5 MySQL服务器管理

   * 5.1 MySQL服务器     
   * 5.2 MySQL数据目录
   * 5.3 MySQL数据库系统
   * 5.4 MySQL服务器的日志     
   * 5.5 MySQL服务器插件     
   * 5.6运行多个MySQL实例在一台机器上     
   * 5.7跟踪mysqld使用DTrace     

* Chapter 6 安全
    
   * 6.2 MySQL的权限系统   
   * 6.3 MySQL用户账户管理   
   * 6.4 使用安全连接  
   * 6.5 安全插件  

* Chapter 7 备份和恢复

   * 7.1 备份和恢复类型
   * 7.2 数据库备份方法
   * 7.3 实例的备份和恢复策略     
   * 7.4 使用mysqldump备份     
   * 在时间7.5点（增量）使用二进制日志恢复     
   * 7.6 MyISAM表的维护和故障恢复     


* Chapter 8 优化

   * 8.1 优化概述
   * 8.2 优化SQL语句     
   * 8.3 优化指标     
   * 8.4 优化数据库结构     
   * 8.5 优化InnoDB表     
   * 8.6 优化MyISAM表     
   * 8.7 优化内存表
   * 8.8 了解查询执行计划     
   * 8.9 控制查询优化器     
   * 8.10 缓冲和缓存     
   * 8.11 优化锁定操作     
   * 8.12 优化MySQL服务器     
   * 8.13 性能测试（基准）     
   * 8.14 检查线程信息     

* Chapter 9 语言结构

   * 9.1 文字值     
   * 9.2 架构对象名称     
   * 关键词9.3和保留字
   * 9.4 用户定义的变量
   * 9.5 表达式的语法
   * 9.6 如何语法

* Chapter 10 全球化

   * 10.1 字符集的支持     
   * 10.2 设置错误消息的语言
   * 10.3 添加一个字符集     
   * 10.4 添加整理到一个字符集     
   * 10.5 字符集配置
   * 10.6 MySQL服务器的时区支持     
   * 10.7 支持本地MySQL服务器

* Chapter 11 数据类型

   * 11.1 数据类型概述     
   * 11.2 数值类型     
   * 11.3 日期和时间类型     
      * 11.3.1日期，日期，和时间戳类型
      * 11.3.2时间类型
      * 11.3.3年型
      * 11.3.4年（2）的局限性和迁移到一年（4）
      * 11.3.5自动初始化和更新时间和日期
      * 11.3.6分数秒的时间值
      * 11.3.7之间的转换日期和时间类型
      * 在日期11.3.8两位数的年
   * 11.4 字符串类型     
   * 11.5 扩展空间数据     
   * 11.6 数据类型的默认值
   * 11.7 数据类型的存储要求
   * 11.8 为一列选择正确类型
   * 11.9 使用其他数据库引擎的数据类型

* Chapter 12 函数和操作符

   * 12.1 功能及操作参考
   * 12.2 类型转换表达式求值
     * （3）运营商     
   * 12.4 流程控制函数
   * 12.5 字符串函数     
   * 12.6 数值函数和操作符     
   * 12.7 日期和时间函数
   * 12.8 什么是历用MySQL？
   * 12.9 全文搜索功能     
   * 12.10 铸造的函数和操作符
   * 12.11 XML功能
   * 12.12 位函数和操作符
   * 12.13 加密和压缩功能
   * 12.14 信息函数
   * 12.15 空间分析功能     
   * 12.16 函数使用全局事务ID。
   * 12.17 MySQL企业加密功能     
   * 12.18 多功能
   * 12.19 集（组）功能     
   * 精密的数学时     


* Chapter 13 SQL语句的语法

   * 13.1 数据定义语句     
   * 13.2 数据处理。     
   * 13.3 事务和锁的陈述     
   * 13.4 复制。     
   * 13.5 编写的SQL语句的语法     
   * 13.6 复合语句语法     
   * 13.7 数据库管理报表     
   * 13.8 实用语句     

* Chapter 14 InnoDB存储引擎

   * 14.1 引言 InnoDB     
   * 14.2 InnoDB 和酸模式
   * 14.3 InnoDB 的多版本
   * 14.4 InnoDB 建筑     
   * 14.5 InnoDB 锁和事务模型     
   * 14.6 InnoDB 配置     
   * 14.7 InnoDB 表空间     
   * 14.8 InnoDB 表和索引     
   * 14.9 InnoDB 表压缩     
   * 14.10 InnoDB 格式的文件管理     
   * 14.11 InnoDB 行存储和列格式     
   * 14.12 InnoDB 的磁盘I/O和文件空间管理     
   * 14.13 InnoDB 和在线DDL     
   * 14.14 InnoDB 启动选项和系统变量
   * 14.15 information_schema InnoDB 表     
   * 14.16 InnoDB 集成MySQL性能模式     
   * 14.17 InnoDB 监视器     
   * 14.18 InnoDB 备份和恢复     
   * 14.19 InnoDB 和MySQL复制
   * 14.20 InnoDB Memcached插件     
   * 14.21 InnoDB 故障排除     

* Chapter 15 选择存储引擎

   * 15.1 设置的存储引擎
   * 15.2 MyISAM存储引擎     
   * 15.3 内存存储引擎
   * 15.4 CSV存储引擎     
   * 15.5 档案存储引擎
   * 15.6 黑洞的存储引擎
   * 15.7 合并存储引擎     
   * 15.8 联邦存储引擎     
   * 15.9 例存储引擎
   * 15.10 其他存储引擎
   * 15.11 概述MySQL存储引擎体系结构    

* Chapter 16 高可用性和可扩展性

   * 16.1使用ZFS复制     
   * 16.2使用MySQLmemcached     

* Chapter 17 复制

   * 17.1 复制配置     
   * 17.2 执行复制     
   * 17.3 复制解决方案     
   * 17.4 复制笔记与心得     

* Chapter 18 MySQL Cluster NDB 7.3和MySQL Cluster NDB 7.4

   * 18.1 MySQL集群概述     
   * 18.2 MySQL集群安装     
   * MySQL集群18.3配置     
   * 18.4 MySQL集群方案     
   * 18.5 MySQL集群管理     
   * 18.6 MySQL集群复制     
   * 18.7 MySQL集群发布说明

* Chapter 19 分区

   * 19.1 分区概述MySQL
   * 19.2 分区类型     
   * 19.3 分区管理     
   * 19.4 分区修剪
   * 19.5 分选择
   * 在分区19.6限制     

* Chapter 20 存储程序和视图

   * 20.1 定义的存储程序
   * 20.2 使用存储子程序（过程和函数）     
   * 20.3 使用触发器     
   * 20.4 使用事件调度器     
   * 20.5 使用视图     
   * 20.6 访问控制用于存储程序和视图
   * 20.7 二进制日志存储程序

* Chapter 21 information_schema表

   * 21.1 information_schema character_sets表
   * 21.2 information_schema排序表
   * 21.3 information_schema collation_character_set_applicability表
   * 21.4 information_schema列表
   * 21.5 information_schema column_privileges表
   * 21.6 information_schema引擎表
   * 21.7 information_schema事件表
   * 21.8 information_schema global_status和session_status表
   * 21.9 information_schema global_variables和session_variables表
   * 21.10 information_schema key_column_usage表
   * 21.11 information_schema optimizer_trace表
   * 21.12 information_schema参数表
   * 21.13 information_schema分区表
   * 21.14 information_schema插件表
   * 21.15 information_schema列表表
   * 21.16 information_schema分析表
   * 21.17 information_schema referential_constraints表
   * 21.18 information_schema程序表
   * 21.19 information_schema图式表
   * 21.20 information_schema schema_privileges表
   * 21.21 information_schema统计表
   * 21.22 information_schema表表
   * 21.23 information_schema表空间表
   * 21.24 information_schema table_constraints表
   * 21.25 information_schema table_privileges表
   * 21.26 information_schema触发器表
   * 21.27 information_schema user_privileges表
   * 21.28 information_schema意见表
   * 21.29 information_schema InnoDB表     
   * 21.30 MySQL集群information_schema表     
   * 21.31线程池information_schema表     
   * 21.32扩展显示报表

* Chapter 22 MySQL性能模式

   * 22.1 绩效模式快速启动
   * 22.2 绩效模式配置     
   * 22.3 绩效模式查询
   * 22.4 绩效模式仪器的命名约定
   * 22.5 性能模式状态监测
   * 22.6 绩效模式的原子和分子事件
   * 22.7 绩效模式声明摘要
   * 22.8 绩效模式一般特征表
   * 22.9 绩效模式表描述     
   * 22.10 性能模式选项和变量引用
   * 22.11 绩效模式命令选项
   * 22.12 绩效模式的系统变量
   * 22.13 性能模式状态变量
   * 22.14 性能模式和插件
   * 22.15 使用性能模式来诊断问题

* Chapter 23  连接器和API

   * 23.1 MySQL Connector/ODBC
   * 23.2 MySQL Connector/Net
   * 23.3 MySQL Connector/J
   * 23.4 MySQL Connector/C++
   * 23.5 MySQL Connector/C
   * 23.6 MySQL Connector/Python
   * 23.7 libmysqld, the Embedded MySQL Server Library     
   * 23.8 MySQL C API     
   * 23.9 MySQL PHP API
   * 23.10 MySQL Perl API
   * 23.11 MySQL Python API
   * 23.12 MySQL Ruby APIs     
   * 23.13 MySQL Tcl API
   * 23.14 MySQL Eiffel Wrapper

* Chapter 24 扩展的MySQL
* Chapter 25 MySQL企业版
* Chapter 26 MySQL Workbench
* 附录A MySQL 5.6的常见问题
* 附录B 错误，错误代码，及常见问题
* 附录C 限制和限制
* 附录E 索引
