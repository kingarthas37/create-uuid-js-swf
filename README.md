create-uuid-js-swf
============

####用flash ShareObject生成uuid，保存在cookie中

>场景：当在某些情况中，用户在浏览网页，而你需要通过js去生成并读取该用户的uuid（你自己清楚你需要干什么），而cookie由于存在跨域和可清除等问题，无法正确读取，在这种情形下，可以通过flash中的Share Object对象，帮你完成这项工作，关于Share Object可参考[此处](http://help.adobe.com/zh_CN/FlashPlatform/reference/actionscript/3/flash/net/SharedObject.html)
