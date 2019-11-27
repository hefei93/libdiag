# libdiag

**集成libdiag方式**

1. 在项目根目录文件“build.gradle”中添加，
   
   ```java
      allprojects {
         repositories {
     maven { url "https://raw.githubusercontent.com/zdeps/diag/master" }
     maven { url "https://raw.githubusercontent.com/zdeps/libdiag/master" }
     }
     }
   ```

2. 在app文件“build.gradle”中添加，
   
   ```java
      dependencies {
      implementation 'com.zkobd:libdiag:1.016'
      //1.016指当前版本，用户可以自己决定需要的版本
   }
   ```
