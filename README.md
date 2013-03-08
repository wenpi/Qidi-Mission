启迪课堂教育平台 Qidi-Mission
======

介绍 Expain
===
启迪课堂教育平台致力于为教师和学生提供一套完善的线上、线下教育平台。<br/>
平台搭建完成后仅需浏览器即可直接访问，采用最新的HTML5/Ajax技术，保证访问的流畅一致性。<br/>


需求 Requirement
===
- apache 非必须，但必须配备其他服务器处理软件 <br/>
* PHP 5.1 or higher<br/>
* Mysql 5 or heigher 或者其他PHP PDO支持的数据库 <br/>

安装 Installation
===
0.配置好服务端环境。<br/>
1.将所有文件上传到服务器。<br/>
2.修改data/configs/frame.ini.php文件。<br/>
  修改数据库访问用户名和密码，其他参数根据你的实际情况修改。<br/>
3.使用第三方软件如phpmyadmin，创建对应的数据库和表。<br/>
  执行data/configs/install.sql内的sql代码，创建相关数据表内容。<br/>
4.登录相应的地址即可。<br/>

安全可选步骤<br/>
*可以将data和lib放到其他安全目录中。<br/>
  修改网站根目录下frame.php文件中的DIR_DATA和DIR_LIB到对应路径即可。<br/>


更新日志 Update Log
===
-2013.3.8<br/>
 *简化Readme.md介绍内容。<br/>
-2013.1.30<br/>
  *在博客上公开发布了该系统，同时修订了介绍内容。<br/>
-2012.12.25<br/>
  *在github上将该平台开源化，该平台已经成功运行。除一些较小的Bug尚未修复外，已经基本完善。<br/>
  *对readme进行了完善。<br/>
