## GitHub下载配置

在C:\Windows\System32\drivers\etc\hosts这个文件中加入：

`199.232.96.133 raw.githubusercontent.com`

199.232.96.133是你在www.ipaddress.com查询的结果。

Linux下也是修改host，这里过多赘述

## java8以及8之前的版本运行使用

`java -jar WkerIDE.jar -g`

## java9以及9之之后的版本运行使用

`java --add-opens java.base/jdk.internal.loader=ALL-UNNAMED --add-opens jdk.zipfs/jdk.nio.zipfs=ALL-UNNAMED -jar WkerIDE.jar -g`

## GitHub配置

配置好GitHub的token之后会在config文件下多出来一个文件，这个文件不要泄露，里面有你配置好的token信息，被泄露的话呢token也会被泄露。

## 官方源

官方源会经常性的更新脚本和支持库。

https://github.com/Wker666/Demo

## 后记

目前测试没有发现问题，如果发现bug请联系WKer:3311736869（QQ）