
# Android Studio Note 
01 File - Setting - Appearance - System Setting - Http Proxy 设置代理 
02 Android Studio之导出JavaDoc出现编码GBK的不可映射字符 在Other command line arguments 添加 -encoding utf-8 -charset utf-8 
03 Error Loading Project: Cannot load 3 facets Details... File -> Settings - > Plugins -> Enable "Android Support" Plugin. 
04 Duplicate files copied in APK META-INF/LICENSE.txt 

android {  

packagingOptions {  
    exclude 'META-INF/DEPENDENCIES.txt'  
    exclude 'META-INF/LICENSE.txt'  
    exclude 'META-INF/NOTICE.txt'  
    exclude 'META-INF/NOTICE'  
    exclude 'META-INF/LICENSE'  
    exclude 'META-INF/DEPENDENCIES'  
    exclude 'META-INF/notice.txt'  
    exclude 'META-INF/license.txt'  
    exclude 'META-INF/dependencies.txt'  
    exclude 'META-INF/LGPL2.1'  
}

05 批量改变 方法参数位置 参数命名 添加 删除参数  选中参数 右键 Refactor - ChangeSignature
06 git 拉去别人代码的时候  需要手动刷新一下(Sync Progress with Gradle File)
