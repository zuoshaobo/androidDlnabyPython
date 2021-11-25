# androidDlnabyPython
鉴于android的dlna投屏需要cling或者Platinum，比较复杂 还有点bug，主要本地投屏需要建立httpserver，而且还有android版本的影响，本仓库
通过python代码被android调用来完成dlna 图片或者电影的投屏

# 说明
本仓库基于https://github.com/zuoshaobo/starcore_for_android 和  https://github.com/lz-ang/AndroidMutualPython  和 https://github.com/cherezov/dlnap 整合而成，python脚本已经支
持电影和图片投屏到tv，android加入python支持调用该部分代码，具体在android的assets里面的mathtest.py, 需要将依赖的python so库拷贝到工程中，具体可以从https://github.com/zuoshaobo/starcore_for_android 
里面的android.python.3.9.0\python-3.9.0\armeabi-v7a\lib-dynload找
