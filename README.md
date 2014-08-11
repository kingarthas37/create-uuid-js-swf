create-uuid-js-swf
============

#####用flash ShareObject生成uuid，保存在cookie中

>场景：用户在浏览每一个网页，而你需要通过js去生成并读取该用户的uuid，并在每一次用户访问网页时你需要侦测到他的uuid,而cookie由于存在跨域问题，无法正确读取，在这种情形下，可以通过flash中的Share Object对象，帮你完成这项工作，关于Share Object可参考[http://help.adobe.com/zh_CN/FlashPlatform/reference/actionscript/3/flash/net/SharedObject.html](http://help.adobe.com/zh_CN/FlashPlatform/reference/actionscript/3/flash/net/SharedObject.html)

注，由于flash对跨域存在一定限制，所以需要在调用flash时申明{'allowScriptAccess':'always'}，以及在as中添加：
Security.allowDomain('*');
Security.allowInsecureDomain("*");
