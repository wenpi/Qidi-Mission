启迪课堂教育平台 Qidi-Mission
======

介绍 Expain
===
启迪课堂教育平台致力于提供一套在线课堂考试系统，主要面向人群是教师和学生。<br/>
教师可以利用这款系统，在自己的终端上面进行课堂考试教育；学生可以也同样可以在终端中完成测验。<br/>
平台运行于服务器，所有数据均可以实现同步。客户浏览不需要安装任何软件，直接访问相应的地址即可。<br/>
注意，该平台需要较好的网络环境，如果不需要多端访问，你可以直接将平台配置到你的终端上以实现更好的浏览体验。<br/>
在初次访问的时候，平台会加载全部题库，同样在访问对应题库时系统会自动加载题库下所有的题目，这一操作可能会要求较高的网络环境。<br/>

需求 Requirement
===
*PHP 5.1 <br/>
*Mysql 5或sqlite等PHP::PDO支持的数据库 <br/>
-apache 不是特别需要，也可以使用其他的服务端做处理 <br/>

安装 Installation
===
0.配置好服务端环境。<br/>
1.将所有文件上传到服务器。<br/>
2.修改data/configs/frame.ini.php文件。<br/>
  将其中的数据库访问用户名和密码修改为你已经创建好的用户名和密码，除此之外其他参数也可以根据你的具体环境进行修改。<br/>
3.使用第三方软件如phpmyadmin，创建对应的数据库。<br/>
4.执行data/configs/install.sql内的sql代码，创建相关数据表内容。<br/>
5.登录相应的地址即可。<br/>

安全可选步骤<br/>
*安装完成后，你可以修改data和lib所在路径。<br/>
  将这两个文件夹剪切到其他目录，然后修改网站根目录下frame.php文件中的DIR_LIB和DIR_DATA到对应路径即可。<br/>


更新日志 Update Log
===
-2012.12.25<br/>
  *在github上将该平台开源化，该平台已经成功运行。除一些较小的Bug尚未修复外，已经基本完善。<br/>
  *对readme进行了完善。<br/>
