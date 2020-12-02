# rsa_decrypt_wework_chat_java
封装企业微信回话rsa解密方法。

[企业微信获取会话内容文档链接]https://work.weixin.qq.com/api/doc/90000/90135/91774


### Example

```javascript

String privateKeyObj = RSAUtil.getPrivateKey(privateKey)
String str  = RSAUtil.decryptRSA(ncrypt_random_key, privateKeyObj);


