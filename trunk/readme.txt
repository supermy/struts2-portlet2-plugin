	mvnʹ��˵��
	http://www.ibm.com/developerworks/cn/opensource/os-maven2/
	����mvn��Ĭ��λ�ã�����localRepository=D:\env_maven\repository�趨��Ȼ�����������

	
	
1.����Դ��
http://svn.apache.org/repos/asf/struts/sandbox/trunk/struts2-portlet2-plugin/
2.pom�趨 
����pom.xml
3.����eclipse
	mvn eclipse:eclipse
���빤�̺�ᷢ��eclipse��"�Ҳ���M2_REPO"�Ĵ�����ʵ���Ǹ���������������ָ����ı��ؿ⡣��linux��windows��Ĭ�ϵĶ�����$HOME/.m2/repository��

�Ѹñ�������eclipse������Ϊ��
Window -> Preferences -> Java -> Build Path -> Classpath Variables -> New��Name����M2_REPO��Path����/home/���û�/.m2/repository	
	
4.���Դ��	
	mvn test:test
	mvn package
	