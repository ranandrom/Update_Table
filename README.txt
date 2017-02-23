sv用该程序前请仔细阅读：

1.该程序为V1.1.0版本，主要实现生信更新表的数据处理功能，最后会在当前目录下生成一个tsv格式文档，其内容与该Excel表内容一致。

2.该程序支持Excel的xls和xlsx两个格式版本。

3.该程序的运行环境是linux系统+java1.8版本以上。

4.该程序的使用方法为：java -jar Update_Table_V1.1.0.jar xxxx(输入参数)
其中输入参数为：
1.【-I/-i 指定的有效路径】：如果不输入时，默认为：/Src_Data1/analysis/Ironman/161231_E00490_0087_AHF75NALXX/Ironman-CR003。
2.【-F/-f 带路径的文件名】：需要处理的Excel表。
3.【-O/-o 带路径的文件名】：需要生成的tsv格式文件名。
