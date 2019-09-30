# Kandy Link Android SDK

## Installation
To integrate Kandy Link Android SDK to your project add gradle dependencies as described in above.

### Step 1
Add Kandy Link SDK Maven url to your root level `build.gradle` file.

```
allprojects {
   	repositories {
   	...
      	 maven {
       	     url "https://raw.githubusercontent.com/Kandy-IO/kandy-link-android-sdk/master/dist/"
      	  }   
   	 	...
  	}
}
```

### Step 2
Add dependcy of Kandy Link Android SDK to your app level `build.gradle` file.

```
implementation 'com.kandy.mobile:kandylinkmobilesdk:{version}'
```

That's all! You can use Kandy Link Android SDK after you sync gradle.

## Compatibility
Compatible Android OS versions :

* Android 4.1+ - Android 10.0

Tested on :

* Nexus 5, Samsung Note 3, Samsung Note 5, Samsung S7, LG G2, LG G3, LG G5, LG G6, HTC Desire 626, HTC One A9, HTC 10, SONY XPERIA Z5, SONY XPERIA XZ, General Mobile GM 5+

Compatible KandyLink Server versions :

* Kandy Link 4.4 + patch 4

* Kandy Link 4.5 MR1 + Patch 6

* Kandy Link 4.6

## Reference

The information about tutorials and documents can be found in the links below

* `Documents`: [API Docs](https://kandy-io.github.io/kandy-link-android-sdk/docs)

* `Tutorials`: [User Guide](https://kandy-io.github.io/kandy-link-android-sdk/tutorials/)
