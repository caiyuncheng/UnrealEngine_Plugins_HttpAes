[中文文档](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/README_ZH.md)，[English Document](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/README.md)


>
> Please note that before purchasing, please verify whether the encryption and decryption results are consistent with expectations
>
> [Encryption, decryption test result link](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/TestData.md)
>


### 1.Edit-Plugin-Installed-http option, then check to enable HttpAes, and restart the editor as prompted.

![image](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/Document/Resource/Step1.png)

### 2.How to use blueprints

![image](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/Document/Resource/BP.jpg)

### 3.How to use CPP

  #### 3.1. In the .Build.cs file

       PublicDependencyModuleNames.AddRange(new string[] { "HttpAes" });

       or

       PrivateDependencyModuleNames.AddRange(new string[] { "HttpAes" });


  #### 3.2. #include "HttpAesUtil.h"

  #### 3.3 method

  ![image](https://github.com/caiyuncheng/UnrealEngine_Plugins_HttpAes/blob/main/Document/Resource/Cpp.png)
