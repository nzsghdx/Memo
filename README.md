# Memo
This is a memorandum.

## 输入法
微软拼音输入法下载地址：https://www.microsoft.com/zh-cn/download/details.aspx?id=28969  
QQ拼音: 

## 下载工具
PDM: https://github.com/persepolisdm/persepolis/releases    
Aira2: https://github.com/aria2/aria2/releases    
迅雷: 

## 字体
Adobe source-code-pro: https://github.com/adobe-fonts/source-code-pro/releases/tag/variable-fonts
>win10下字体安装失败(提示不是有效的字体文件,搜索到的各种解决办法对win10无效)微软中国官方暂时没有给出有效的解决办法

## 开发
### 前端
#### 浏览器
Blist: https://blisk.io/
>基于Chromium的网站开发浏览器,可实现桌面及移动端的实时页面预览.  
### 开发工具
开发工具
- JDK: http://www.oracle.com/technetwork/java/javase/downloads/index.html  
  >- 需要配置JAVA-HOME(安装目录),PATH(jdk的bin目录)和CLASSPATH(jre的lib目录)三个环境变量  
- IDEA: https://www.jetbrains.com/idea/download  
- MySql: https://dev.mysql.com/downloads/windows/  
- Maven: http://maven.apache.org/download.cgi 
  >- 需要配置MAVEN-HOME(安装目录)和PATH(安装目录\bin)两个环境变量  
  >- 修改本地repo库: 例如在安装目录 ```E:\apache-maven-3.5.2\conf\setting.xml```中新增如下语句   
     ```<localRepository>E:\maven_repo</localRepository>```   
     
  >- 修改远程repo库: 例如在安装目录 ```E:\apache-maven-3.5.2\conf\setting.xml```中新增如下语句 
  
        ```
        <mirror>
                <id>nexus-aliyun</id>
                <mirrorOf>*</mirrorOf>
                <name>Nexus aliyun</name>
                <url>http://maven.aliyun.com/nexus/content/groups/public</url>
         </mirror>
         ```
    
- SqlLiteexpert: http://www.sqliteexpert.com/download.html
