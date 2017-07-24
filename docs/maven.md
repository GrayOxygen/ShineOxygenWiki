# maven常用
 
mvn archetype:generate  构建项目  
mvn clean       项目清理  
mvn compile     项目源代码的编译  
mvn test        项目单元测试的编译  
mvn package     项目打包  
mvn install             发布项目提交到本地仓库  
mvn deploy              发布项目到  
mvn jetty:run ：        启动jetty容器    
mvn eclipse:clean ：    清除eclipse的一些系统设置                 
mvn eclipse:eclipse ：  生成 Eclipse 项目文件 
mvn dependency:tree   查看依赖树  
mvn assembly:assembly 需要配assembly插件，可用于把指定文件进行打包 tar.gz,zip包  
指定maven参数：  
-DskipTests=true        默认不走单元测试  
-Dmaven.test.skip=true  不执行测试用例，也不编译测试用例类
-P local                选择资源文件类型 local,需在pom开启资源配置  

(-DskipTests，不执行测试用例，但编译测试用例类生成相应的class文件至target/test-classes下。)