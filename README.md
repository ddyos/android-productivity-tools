# android-productivity-tools
Collect productivity tools for Android application development.

收集一些提高Android开发效率的工具。

## 代码生成
### findViewById
现在有很多框架可以通过注解去简化绑定xml中的控件的过程,不过有时候项目中并不方便引入这些框架,下面是一些可以生成findViewById语句的工具：

1.[http://android.lineten.net/layout.php](http://android.lineten.net/layout.php)

可选特性:支持生成Android Annotations注解代码(将懒进行到底)

2.[https://www.buzzingandroid.com/tools/android-layout-finder/](https://www.buzzingandroid.com/tools/android-layout-finder/)

可选特性: 支持针对ViewHolder , Adapter生成代码

### json
下面是一些根据json生成实体类(POJO)的工具：

1.[jonfhancock/JsonToJava](https://github.com/jonfhancock/JsonToJava)

可选特性:可以通过url提供json , 支持 Implement Parcelable ,Include Gson Annotations ,Override toString() 

2.[http://www.jsonschema2pojo.org/](http://www.jsonschema2pojo.org/)

可选特性:支持 Jackson , Gson ,Include hashCode and equals,Include toString 等

3.[http://bejson.com/json2javapojo/](http://bejson.com/json2javapojo/)

可选特性:json格式化校验,xml转json等

### Parcelable
Parcelable是官方推荐的序列化方式，效率比Serializable高，但使用起来较麻烦，下面是一些简化工具：

1.[johncarl81/parceler](https://github.com/johncarl81/parceler)

通过注解和工具类简化Parcelable的使用

2.[baoyongzhang/ParcelableGenerator](https://github.com/baoyongzhang/ParcelableGenerator)

通过注解简化Parcelable的使用

3.[mcharmas/android-parcelable-intellij-plugin](https://github.com/mcharmas/android-parcelable-intellij-plugin)

Android Studio插件，用于生成Parcelable代码

