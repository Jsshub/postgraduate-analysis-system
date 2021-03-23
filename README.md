# postgraduate-analysis-system
This is a dynamic analysis system for postgraduate entrance examination

该系统是使用python以及Kafka、flink、flume、hive、sqoop、mysql、tomcat、hdfs、shell、等技术共同编译的，用于动态抓取数据的，实时数据分析系统。
爬取百度指数上关于考研、分数线、专业、数学、英语、政治的全国搜索量和各个省份搜索量的数据

编写python代码爬取数据
爬取百度指数上关于考研、分数线、专业、数学、英语、政治的全国搜索量和各个省份搜索量的数据

指定为前一天上传共享文件中的区域数据到hive
 将hive中的表上传到MySQL上
编写脚本，利用sqoop将hive中的表上传到MySQL
定时上传全国数据，定时上传区域数据，定时运行sql，定时上传数据到MySQL

实时部分
使用Kafka，flink，redis、flume、实时的获取数据和计算。
