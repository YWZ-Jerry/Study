1. mysql set character
  `SET character_set_client = utf8;`
  `SET character_set_connection = utf8;`
  `SET character_set_database = utf8;`
  `SET character_set_results = utf8;`
  `SET character_set_server = utf8;`
2. mysql command
   mysql -u root -p
    1、给root加个密码ab12。
    首先在DOS下进入目录mysql\bin，然后键入以下命令
        mysqladmin -u root -password ab12
    2、再将root的密码改为djg345。
        mysqladmin -u root -p ab12 password djg345
    show databases;
    use db;
    create database <数据库名>
    drop database <数据库名>--->  drop database if exists 数据库名;
    show tables;
    creat table <name>
    desc table (view table)
 3. mysql show command
    1. show tables或show tables from database_name; -- 显示当前数据库中所有表的名称。 
    2. show databases; -- 显示mysql中所有数据库的名称。 
    3. show columns from table_name from database_name; 或show columns from database_name.table_name; -- 显示表中列名称。 
    4. show grants for user_name; -- 显示一个用户的权限，显示结果类似于grant 命令。 
    5. show index from table_name; -- 显示表的索引。 
    6. show status; -- 显示一些系统特定资源的信息，例如，正在运行的线程数量。 
    7. show variables; -- 显示系统变量的名称和值。(show variables like '%char%';)
    8. show processlist; -- 显示系统中正在运行的所有进程，也就是当前正在执行的查询。大多数用户可以查看他们自己的进程，但是如果他们拥有process权限，就可以查看所有人的进程，包括密码。 
    9. show table status; -- 显示当前使用或者指定的database中的每个表的信息。信息包括表类型和表的最新更新时间。 
    10. show privileges; -- 显示服务器所支持的不同权限。 
    11. show create database database_name; -- 显示create database 语句是否能够创建指定的数据库。 
    12. show create table table_name; -- 显示create database 语句是否能够创建指定的数据库。 
    13. show engines; -- 显示安装以后可用的存储引擎和默认引擎。 
    14. show innodb status; -- 显示innoDB存储引擎的状态。 
    15. show logs; -- 显示BDB存储引擎的日志。 
    16. show warnings; -- 显示最后一个执行的语句所产生的错误、警告和通知。 
    17. show errors; -- 只显示最后一个执行语句所产生的错误。 
    18. show [storage] engines; --显示安装后的可用存储引擎和默认引擎。
    
