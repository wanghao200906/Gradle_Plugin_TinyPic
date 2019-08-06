# Gradle_Plugin_TinyPic
- 这是一个用于压缩png图片的gradle插件。
- 使用的是tinypng的api
- 需要注册获取apikey，在这个网站注册https://tinypng.com/developers 
- 获取的api 可以每个月免费压缩500张图片
- 使用api需要进行依赖
```
    implementation 'com.tinify:tinify:1.6.2'
```

- 运行很简单
```
      ./gradlew tinyTask 

```
