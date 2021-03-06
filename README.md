# Breadcrumb Toolbar 
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-BreadcrumbToolbar-green.svg?style=true)](https://android-arsenal.com/details/1/4155)

Breadcrumb Toolbar provides a nested view interaction embedded into the vanilla Toolbar.

![alt tag](https://cloud.githubusercontent.com/assets/4641831/17498901/d62a645a-5dd2-11e6-9cab-e1d589126afb.gif)

Download
--------

Grab via Maven:
```xml
<dependency>
  <groupId>com.rokpetek.breadcrumbtoolbar</groupId>
  <artifactId>breadcrumb-toolbar</artifactId>
  <version>1.0</version>
  <type>pom</type>
</dependency>
```
or Gradle:
```groovy
compile 'com.rokpetek.breadcrumbtoolbar:breadcrumb-toolbar:1.0'
```

## Usage
When adding a new fragment the toolbar is notified to add an item on its "breadcrumb" stack. You can use it with the animated drawer hamburger icon or without. Sample app is included.

## Compatibility

- Library: SDK 14+ (ICS)
- Sample app: SDK 24+ (N), Java 8

## Support

- RTL support (right to left)

## Bintray
Publish to bintray (parameters located in local.properties)
```bash
$ ./gradlew clean build bintrayUpload -PbintrayUser=BINTRAY_USERNAME -PbintrayKey=BINTRAY_KEY -PdryRun=false
```
