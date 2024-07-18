仅为备份 @Lotus6师傅的[ysoserial](https://github.com/Lotus6/ysoserial)

# ysoserial
ysoserial 图形化，探测 gadget，TomcatEcho，命令执行，冰蝎，哥斯拉内存马注入，加载字节码等
* 添加了帆软 JacksonSignedObject 链
* 添加了 su18 师傅文章里，所有 Transformer 链 org.mozilla.javascript.DefiningClassLoader defineClass 加载字节码的方式
* 添加了 pen4uin 师傅 JMG 内存马模块
* 集合 ysoserial-for-woodpecker 和 Y4er-ysoserial 的 poc
* JDK 版本：JDK 8u361
* (如果对您有帮助，感觉不错的话，请您给个大大的 ⭐️❗️)
<img width="786" alt="image" src="https://github.com/user-attachments/assets/0b91ba63-5fb7-4891-b289-c2358285c16e">

**V1.0版本**

1. Gadget

"URLDNS", "ROME", "C3P0", "C3P0_LowVer", "C3P0Tomcat", "Ceylon", "Click1", "CommonsBeanutils1", "CommonsBeanutils183NOCC", "CommonsBeanutils192NOCC", "CommonsBeanutils192WithDualTreeBidiMap", "CommonsCollections1", "CommonsCollections2", "CommonsCollections3", "CommonsCollections4", "CommonsCollections5", "CommonsCollections6", "CommonsCollections6Lite", "CommonsCollections7", "CommonsCollections8", "CommonsCollections9", "CommonsCollections10", "CommonsCollections11", "CommonsCollectionsK1", "CommonsCollectionsK2", "CommonsCollectionsK3", "CommonsCollectionsK4", "Fastjson1", "Fastjson2", "FindGadgetByDNS", "FindClassByDNS", "FindClassByBomb", "Groovy1", "Hibernate1", "Jackson1", "Jackson2", "JacksonSignedObject", "JavassistWeld1", "JBossInterceptors1", "Jdk7u21", "Jdk8u20", "JSON1", "Spring1", "Spring2", "MozillaRhino1", "MozillaRhino2", "Vaadin1"

2. Module

"RawCMD", "LinuxCMD", "WinCMD", "AutoCMD", "Dnslog", "Sleep", "HttpLog", "LoadClass", "LoadClassBase64", "LoadJar", "CodeFile", "CodeBase64", "Bcel", "BcelClassFile", "ScriptBase64", "ScriptFile", "JNDI", "Godzilla", "Behinder", "TomcatCmdEcho", "ZohoPMPTomcatEcho", "UploadFile", "UploadFileBase64"

3. Encode

"NORMAL","Base64", "Bin","GZIP+Base64"

3. DirtWrapper

"DIRTARRAY","DIRTLinkedList","DIRTTCRESET"

**参考**

https://github.com/frohoff/ysoserial

https://github.com/woodpecker-framework/ysoserial-for-woodpecker

https://github.com/pen4uin/java-memshell-generator

https://github.com/Y4er/ysoserial

https://github.com/xi3w3n/ysoserial
