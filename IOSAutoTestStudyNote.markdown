# Jenkis
![Jenkis icon](http://jenkins-ci.org/sites/default/files/images/headshot.png)

**Web site**: <http://jenkins-ci.org/>

**Summary**: Jenkins (原名 Hudson) 是一个开源项目，提供了一种易于使用的持续集成系统，使开发者从繁杂的集成中解脱出来，专注于更为重要的业务逻辑实现上。同时 Jenkins 能实施监控集成中存在的错误，提供详细的日志文件和提醒功能，还能用图表的形式形象地展示项目构建的趋势和稳定性。

Jenkins 的安装非常简单，只需要从 Jenkins 的主页上下载最新的 jenkins.war 文件然后运行 java -jar jenkins.war。同时，还可以点击 Jenkins 页面上的 launch 按钮完成下载和运行 Jenkins。
<http://www.ibm.com/developerworks/cn/java/j-lo-jenkins/>

**Key words**: 持续集成（Continuous integration）; 敏捷（Agile）; 

**Learned after used**:

1. 部署十分简单。可通过 ```java -jar jenkins.war```命令直接部署，或使用对应平台的安装器进行安装。不需要预先拥有数据库或网站服务（如tomcat）。
2. 所有设置均可直接在web GUI界面进行。设置保存在```.jankis```文件中，不需要数据库即可保证重启后也可保存设置。
3. 可使用插件。拥有大量插件可保证与各种测试工具、代码管理库、开发工具集合，进行自动编译、测试等。

**Existed Questions**:

* 需要使用开发者账户进行code sign方可编译。使用的release或debug进行编译需要证书签名。（其实也不算问题，真机调试都需要证书的）

***

# Appium
![Appium icon](http://appium.io/img/appium-logo.png)

**Web site**: <http://appium.io/>

**Summary**: Appium is an open source test automation framework for use with native and hybrid mobile apps. It drives iOS and Android apps using the WebDriver JSON wire protocol.
Appium是一个开源的，适用于原生或混合移动应用应用（ hybrid mobile apps ）的自动化测试平台. Appium应用WebDriver: JSON wire protocol驱动安卓和iOS移动应用.

**Key words**: WebDrive ; Native and Hybrid mobile apps; 

**Learned after used**: none yet. 
