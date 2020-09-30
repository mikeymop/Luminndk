# Lumin NDK

A small Android project that implements the Polar SDK in Android and passes the values over JNI Bridge to the native environment.

### Setup Development env

* [Polar SDK](https://github.com/polarofficial/polar-ble-sdk)
* [Android SDK]()

Install Android sdk into `/home/$USER` and export the relevant environment variables.

```
export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.265.b01-1.fc32.x86_64/jre"
export GRADLE_HOME="/home/$USER/Android/studio/gradle/gradle-4.4/bin"
export ANDROID_HOME=/home/$USER/Android/Sdk/
export ANDROID_SDK_ROOT="/home/$USER/Android"
```


### Contributing



### Notes

* [C++ Headers Notes](http://www.math.uaa.alaska.edu/~afkjm/csce211/handouts/SeparateCompilation.pdf)
* [Android JNI Notes](https://androidpedia.net/en/tutorial/8674/android-java-native-interface--jni-)
* [Android NDK Notes](https://androidpedia.net/en/tutorial/492/android-ndk)
* [Callback Android -> JNI](https://stackoverflow.com/questions/13377168/how-to-create-callbacks-between-android-code-and-native-code)
