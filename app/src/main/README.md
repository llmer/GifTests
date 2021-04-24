1.在工程的build.gradle中添加如下
````buildscript {
       repositories {
            mavenCentral()
        }
    }
    allprojects {
        repositories {
            mavenCentral()
        }
}
````
2.在app的build.gradle中添加依赖

```implementation 'pl.droidsonroids.gif:android-gif-drawable:1.2.1'
```
3.布局文件中就可以直接写你需要加载的gif图片即可
```<pl.droidsonroids.gif.GifImageView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content" 
    android:src="@drawable/jingyu" />
```

