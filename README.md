# Maven在Eclipse中远程调试hadoop2.6.0项目
1.系统环境<br/>
调试：Win7，64bit<br/>
Cluster: Linux, Centos<br/>

2.创建hadoop项目命令<br/>
mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DgroupId=org.conan.myhadoop.mr -DartifactId=myHadoop -DpackageName=org.conan.myhadoop.mr -Dversion=1.0-SNAPSHOT -DinteractiveMode=false  -DarchetypeCatalog=internal


