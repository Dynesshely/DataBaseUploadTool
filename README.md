# DataBaseUploadTool
A simple tool run on command line. It allows you to upload your local file onto your Data Base

## How to use

-------------------------------------------------------------
Data Source - 数据库服务器地址，例如：www.baidu.com 或是 直接使用 IP 地址<br>
Port - 要连接的端口号<br>
Data Base - 初始连接时数据库名称<br>
Pooling - 填 false 即可<br>
Char Set - 连接用字符集 推荐 utf8<br>
User - 要登录的用户名<br>
Password - 用户的登陆密码<br>
-------------------------------------------------------------
Source File Path - 要从本地上传的文件路径，必须是绝对路径<br>
Data Base - 要上传的数据库名称<br>
Table - 要上传的表名称<br>
Column name - 上传到的列名称<br>
Condition - 条件，例如：WHERE id = 123 不需要在末尾追加分号<br>
-------------------------------------------------------------

## Notice

This tool requires the [Library](), if you want to compile this project, you need add that Library.
And you need install the MySqlConnection in NuGet for this project.
