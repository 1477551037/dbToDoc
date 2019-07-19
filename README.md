# dbToDoc
这是一个 “自动生成数据库文档”工具，运行org.sqlToDoc.DbDocUI类的main方法
org.sqlToDoc.DbDocBean 数据库连接配置
org.sqlToDoc.DBHelper.getTableAndColumnsCustomize 获取数据的方法

获取所需数据的sql：
1）
SELECT TABLE_NAME, TABLE_COMMENT FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_SCHEMA='dataName';
2）
select COLUMN_NAME, COLUMN_TYPE, COLUMN_KEY, COLUMN_COMMENT, IS_NULLABLE from information_schema.columns where table_schema = 'dataName' and table_name = 'tableName'


