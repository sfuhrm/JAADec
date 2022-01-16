# JAADec

This is a fork of https://github.com/DV8FromTheWorld/JAADec with the following changes:
* Maven-based building.
* Fixed Java deprecations.
* Rollout to Maven Central instead of shut-down jcenter.

The original project was licensed under Public Domain and as such this fork is also licensed under Public Domain. Use as you like!

JAAD is an AAC decoder and MP4 demultiplexer library written completely in Java. It uses no native libraries, is platform-independent and portable. It can read MP4 container from almost every input-stream (files, network sockets etc.) and decode AAC-LC (Low Complexity) and HE-AAC (High Efficiency/AAC+).

This library is available on Bintray's `jcenter` as a Maven/Gradle download.<br>
https://bintray.com/dv8fromtheworld/maven/JAADec/view
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
