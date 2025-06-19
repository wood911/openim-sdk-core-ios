# openim-sdk-core-ios

### iOS in podfile
```ruby
install! 'cocoapods', :deterministic_uuids => false
pod 'OpenIMSDKCore', :git => 'https://github.com/wood911/openim-sdk-core-ios.git'
```

### Android in build.gradle
```groovy
repositories {
    maven {
        url = uri("https://maven.pkg.github.com/wood911/openim-sdk-core-ios")
    }
    google()
    mavenCentral()
}

dependencies {
    implementation 'io.openim:core-sdk:3.8.3-patch7@aar'
}
```