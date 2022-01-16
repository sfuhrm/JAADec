# JAADec

![Maven Central](https://img.shields.io/maven-central/v/de.sfuhrm/jaad)


This is a fork of https://github.com/DV8FromTheWorld/JAADec with the following changes:
* Adjusted Maven-based building to work with Maven Central.
* Requires JDK 8 now since building for older targets is no longer working with current JDKs.
* Fixed Java deprecations.
* Fixed Javadoc errors.
* Removed the Gradle build (DRY).
* Rollout to Maven Central instead of shut-down [jcenter](https://blog.gradle.org/jcenter-shutdown).

The credits go to the original author [in-somnia](https://sourceforge.net/u/in-somnia/profile/) who put this into the [public domain](https://sourceforge.net/p/jaadec/code/157/).

The original project was licensed under Public Domain and as such this fork is also licensed under Public Domain. Use as you like!

JAAD is an AAC decoder and MP4 demultiplexer library written completely in Java. It uses no native libraries, is platform-independent and portable. It can read MP4 container from almost every input-stream (files, network sockets etc.) and decode AAC-LC (Low Complexity) and HE-AAC (High Efficiency/AAC+).

<p>
For Gradle:

```groovy

dependencies {
  compile 'de.sfuhrm:jaad:0.8.7'
}
```
<p>
For Maven:

```xml
<dependencies>
  <dependency>
    <groupId>de.sfuhrm</groupId>
    <artifactId>jaad</artifactId>
    <version>0.8.7</version>
  </dependency>
</dependencies>
```
