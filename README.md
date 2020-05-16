# miniSQL-DBMS
深入编译原理：自己实现一个sql语句解析器

## 项目背景

设计并实现一个DBMS原型系统，可以接受基本的SQL语句，进行词法分析、语法分析，然后解释执行SQL语句，完成对数据库文件的相应操作，实现DBMS的基本功能。

加深编译原理基础知识的理解：词法分析、语法分析、语法制导翻译等；

加深相关基础知识的理解：数据库系统、数据结构、操作系统等。


## 希望实现的功能

至少实现以下sql语句

CREATE DATABASE   	创建数据库
USE DATABASE 		选择数据库
CREATE   TABLE		创建表
SHOW  TABLES  		显示表名
INSERT		 	插入元组
SELECT 		 	查询元组
UPDATE			更新元组
DELETE			删除元组
DROP	TABLE 		删除表
DROP	DATABASE		删除数据库
EXIT	 			退出系统


## 项目实现大纲

### 大致流程

1. 设计词法规则；
2. 设计语法规则；
3. 设计数据库物理存储结构；
4. 设计语义规则；
5. 编程实现。



