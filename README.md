# Kandy Link Android SDK

<p>
    <img alt="GitHub release" src="https://img.shields.io/github/v/release/kandy-io/kandy-link-android-sdk">
</p>

## Installation
To integrate Kandy Link Android SDK to your project add gradle dependencies as described below.

### Step 1
Add Kandy Link Android SDK maven repository url to your root level `build.gradle` file.

```
allprojects {
  ...
  repositories {
    ...
    maven {
      url "https://raw.githubusercontent.com/Kandy-IO/kandy-link-android-sdk/master/dist/"
    }
  }
}
```

### Step 2
Add dependency of Kandy Link Android SDK to your app level `build.gradle` file.

```
implementation 'com.kandy.mobile:kandylinkmobilesdk:5.3.0'
```

That's all! You can use Kandy Link Android SDK after you sync gradle.

## Installation for versions before 5.0.0
Versions before 5.0.0 will require manual installation. To download an older version, switch to tag of that specific version. Then download the MobileSDK-4.x.x.zip file under "dist" directory.

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

* `Tutorials`: Choose your configuration ( [Kandy-US](https://kandy-io.github.io/kandy-link-android-sdk/tutorials/?SUBSCRIPTIONFQDN=spidr-ucc.genband.com&WEBSOCKETFQDN=spidr-ucc.genband.com&ICESERVER1=turns:turn-ucc-1.genband.com:443?transport=tcp&ICESERVER2=turns:turn-ucc-2.genband.com:443?transport=tcp) | [Kandy-EMEA](https://kandy-io.github.io/kandy-link-android-sdk/tutorials/?SUBSCRIPTIONFQDN=spidr-em.genband.com&WEBSOCKETFQDN=spidr-em.genband.com&ICESERVER1=turns:turn-em-1.genband.com:443?transport=tcp&ICESERVER2=turns:turn-em-2.genband.com:443?transport=tcp) )
