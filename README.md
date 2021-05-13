## Freshchat Android SDK

## First time integration 
### [Integration Guide](https://support.freshchat.com/support/solutions/articles/50000000207)

#### Quick Steps
Project gradle file **build.gradle**
```
allprojects {
    repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
```

App Module gradle file **(app/build.gradle)** 
```
dependencies {
    implementation 'com.github.freshdesk:freshchat-android:{latestVersion}'
}
```

## Updating to newer versions of SDK
### [Changelog](https://github.com/freshdesk/freshchat-android/blob/master/CHANGELOG.md)


## Contact us
For any issues, queries or feature request, please reach out to us through support@freshchat.com
