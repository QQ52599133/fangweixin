#打开项目根目录下config.gradle文件
ext {
    //App安装到手机上的名字
    app_name = "淘宝"
    //是否从本地加载网页
    isLocal = "false"
    //应用包名
    application_id = "com.peakchao.webapp"
    //isLocal = "true"：说明从本地加载网页，你只需将你的网页源码放到项目app/src/main/assets目录下即可
    //isLocal = "false"：说明不从本地加载网页，而是从加载下面web_url
    web_url = "http://demo.wex5.com/taobao/index.html?device=m"
}
#App桌面图标替换路径：app/src/main/res/drawable-xxhdpi/ic_launcher.jpg

