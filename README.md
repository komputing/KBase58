### How to add

Add it in your root build.gradle at the end of repositories:

```
allprojects {
    repositories {
    ...
    maven { url 'https://jitpack.io' }
    }
}
```
Add the dependency

```
dependencies {
    implementation 'com.github.komputing:KBase58:0.4'
}
```
