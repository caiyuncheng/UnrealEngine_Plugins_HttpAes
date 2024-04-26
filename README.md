1. 编辑-插件-已安装-http选项，然后打勾启用HttpAes，按照提示重启编辑器即可。
![image](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/Document/Resource/Step1.png)

2.蓝图使用方法
![image](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/Document/Resource/BP.jpg)

3.CPP使用方法

  3.1. 在.Build.cs文件
       PublicDependencyModuleNames.AddRange(new string[] { "HttpAes" });
       或者
       PrivateDependencyModuleNames.AddRange(new string[] { "HttpAes" });

  3.2. #include "HttpAesUtil.h"

  3.3 方法
  ![image](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/Document/Resource/Cpp.png)
