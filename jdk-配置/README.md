# java 环境变量的配置



首先，安装JDK，将 jdk 解压后的目录放在 `/usr/local/java` 中

然后，配置环境变量，将下列代码添加到文件 `/etc/proile` 的后面

最后，重启电脑，在 `bash` 输入命令 `java -version` 验证

```json
export JAVA_HOME=/usr/local/java/jdk1.8.0_171
export JRE_HOME=/usr/local/java/jdk1.8.0_171/jre
export PATH=$PATH:/usr/local/java/jdk1.8.0_171/bin
export CLASSPATH=./:/usr/local/java/jdk1.8.0_171/lib:/usr/local/java/jdk1.8.0_171/jre/lib  
```

