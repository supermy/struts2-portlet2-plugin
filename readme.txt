	mvn使用说明
	http://www.ibm.com/developerworks/cn/opensource/os-maven2/
	更改mvn的默认位置，进行localRepository=D:\env_maven\repository设定，然后错误消除。

	
	
1.下载源码
http://svn.apache.org/repos/asf/struts/sandbox/trunk/struts2-portlet2-plugin/
2.pom设定 
覆盖pom.xml
3.配置eclipse
	mvn eclipse:eclipse
导入工程后会发现eclipse报"找不到M2_REPO"的错误，其实这是个环境变量，就是指向你的本地库。在linux和windows下默认的都是在$HOME/.m2/repository。

把该变量加入eclipse，方法为：
Window -> Preferences -> Java -> Build Path -> Classpath Variables -> New，Name输入M2_REPO，Path输入/home/名用户/.m2/repository	
	
4.测试打包	
	mvn test:test
	mvn package
	