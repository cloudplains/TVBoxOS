
# 修改tvbox源代码

1、修改软件名称地址
app/src/main/res/values/strings.xml

2、修改版本号地址
app/src/main/AndroidManifest.xml

3、修改图标、背景地址

你的地址/app/src/main/res

drawable/app_bg.png为背景，把原来的删掉，自己上传一个新的；

drawable-hdpi/app_icon.png为图标1，把原来的删掉，自己上传一个新的；

drawable-xhdpi/app_icon.png为图标2，把原来的删掉，自己上传一个新的；

drawable-xxhdpi/app_icon.png为图标3，把原来的删掉，自己上传一个新的；

drawable-xxxhdpi/app_icon.png为图标4，把原来的删掉，自己上传一个新的；

4、修改内置源地址

第130行app/src/main/java/com/github/tvbox/osc/api/ApiConfig.java

       


