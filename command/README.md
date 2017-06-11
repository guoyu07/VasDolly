## ApkChannelPackage命令行
 命令行工具即：jar文件下`ApkChannelPackage.jar`，可以通过help查看具体命令：
 ``` java
 java -jar ApkChannelPackage.jar help
 ```

 目前支持以下操作：

 ### 获取指定APK的签名方式
 ``` java
 java -jar ApkChannelPackage.jar get -s /home/user/test.apk
 ```
 ### 获取指定APK的渠道信息
 ``` java
 java -jar ApkChannelPackage.jar get -c /home/user/test.apk
 ```
 ### 通过指定渠道字符串添加渠道信息
 ``` java
 java -jar ApkChannelPackage.jar put -c "channel1,channel2" /home/user/base.apk /home/user/
 ```
 ### 通过指定渠道文件添加渠道信息
 ``` java
 java -jar ApkChannelPackage.jar put -c channel.txt /home/user/base.apk /home/user/
 ```