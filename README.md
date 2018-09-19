# EncryptString

#### 项目介绍
近期互联网上频频爆出网站数据库被脱裤，造成大量的敏感数据的失窃和丢失，给很多企业带来重大损失，本加密解密组件（jar包）可以帮助开发者，快速对应用中的敏感数据进行加密解密，尽可能的帮助开发人员提高应用的安全性，防止重大损失，密钥由用户输入，请妥善保管好您的密钥字符串。

#### 软件架构
Java JDK 1.8



#### 使用说明

将jar包导入项目的lib目录下
在Java文件中直接调用
加密方法：EncryptUntil.Encrypt(key, contentString)
解密方法：EncryptUntil.Deencrypt(key, encryptionString)

上述两个方法的返回值类型都是String类型，支持对中文、英文、中文标点、英文标点以及特殊符号等加解密。


#### 参与贡献

作者：eaglet
来自邪恶八进制 


