# exprot_data_dictionary-mysql
导出mysql的数据字典为word文档的表格，用python实现。
需要安装三个库, pymysql docx lxml  
注意：docx这个库 存在python2和3不兼容的问题，如果直接pip下载可能出现导入报错的问题。可以卸载 pip3 uninstall docx  然后pip3 install python_docx-0.8.7-py2.py3-none-any.whl
这样就没问题了。
