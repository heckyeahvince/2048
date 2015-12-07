2048-android
============

Original: https://github.com/uberspot/2048-android

## To submit:

https://classroom.github.com/assignment-invitations/1a8d991a96375a455104d957baef3ee7 

## Sample Solution:

https://github.com/DeLaSalleUniversity-Manila/2048-melvincabatuan

## Submission Procedure with Git: 

```shell
$ cd /path/to/your/android/app/
$ git init
$ git add –all
$ git commit -m "your message, e.x. Assignment 1 submission"
$ git remote add origin <Assignment link copied from assignment github, e.x. https://github.com/DeLaSalleUniversity-Manila/secondactivityassignment-melvincabatuan.git>
$ git push -u origin master
<then Enter Username and Password>
```
 
 ## Videocapture:
-----------
[![screenshot](screenshot_001.png)](https://youtu.be/EUCsB4HbWwI)

 

## Build

    git clone --recursive https://github.com/uberspot/2048-android.git
    cd 2048-android/
    git submodule update --init --recursive
    ./gradlew build
    
Ex.
```shell
$ git clone --recursive https://github.com/uberspot/2048-android.git
Cloning into '2048-android'...
remote: Counting objects: 282, done.
remote: Total 282 (delta 0), reused 0 (delta 0), pack-reused 282
Receiving objects: 100% (282/282), 7.12 MiB | 119 KiB/s, done.
Resolving deltas: 100% (99/99), done.
Submodule 'assets/2048' (https://github.com/uberspot/2048.git) registered for path 'assets/2048'
Cloning into 'assets/2048'...
remote: Counting objects: 1167, done.
remote: Total 1167 (delta 0), reused 0 (delta 0), pack-reused 1167
Receiving objects: 100% (1167/1167), 536.59 KiB | 113 KiB/s, done.
Resolving deltas: 100% (702/702), done.
Submodule path 'assets/2048': checked out 'ae476ed10dda50e04c423db588a8d2cea8b893b2'

$ git submodule update --init --recursive

$ ./gradlew build
:preBuild UP-TO-DATE
:preDebugBuild UP-TO-DATE
:checkDebugManifest
:prepareDebugDependencies
:compileDebugAidl
:compileDebugRenderscript
:generateDebugBuildConfig
:generateDebugAssets UP-TO-DATE
:mergeDebugAssets
:generateDebugResValues
:generateDebugResources
:mergeDebugResources
:processDebugManifest
:processDebugResources
:generateDebugSources
:processDebugJavaRes UP-TO-DATE
:compileDebugJava
Note: /home/cobalt/AndroidStudioProjects/2048-android/src/com/uberspot/a2048/MainActivity.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
:compileDebugNdk UP-TO-DATE
:compileDebugSources
:preDexDebug
:dexDebug
:validateDebugSigning
:packageDebug
:zipalignDebug
:assembleDebug
:preReleaseBuild UP-TO-DATE
:checkReleaseManifest
:prepareReleaseDependencies
:compileReleaseAidl
:compileReleaseRenderscript
:generateReleaseBuildConfig
:generateReleaseAssets UP-TO-DATE
:mergeReleaseAssets
:generateReleaseResValues
:generateReleaseResources
:mergeReleaseResources
:processReleaseManifest
:processReleaseResources
:generateReleaseSources
:processReleaseJavaRes UP-TO-DATE
:compileReleaseJava
Note: /home/cobalt/AndroidStudioProjects/2048-android/src/com/uberspot/a2048/MainActivity.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
:compileReleaseNdk UP-TO-DATE
:compileReleaseSources
:lintVitalRelease SKIPPED
:preDexRelease
:dexRelease
:packageRelease
:assembleRelease
:assemble
:compileLint
:lint
Ran lint on variant release: 9 issues found
Ran lint on variant debug: 9 issues found
Wrote HTML report to file:/home/cobalt/AndroidStudioProjects/2048-android/build/outputs/lint-results.html
Wrote XML report to /home/cobalt/AndroidStudioProjects/2048-android/build/outputs/lint-results.xml
:preCompileDebugUnitTestJava
:preDebugUnitTestBuild UP-TO-DATE
:prepareDebugUnitTestDependencies
:processDebugUnitTestJavaRes UP-TO-DATE
:compileDebugUnitTestJava UP-TO-DATE
:compileDebugUnitTestSources UP-TO-DATE
:mockableAndroidJar
:assembleDebugUnitTest
:testDebug
:preCompileReleaseUnitTestJava
:preReleaseUnitTestBuild UP-TO-DATE
:prepareReleaseUnitTestDependencies
:processReleaseUnitTestJavaRes UP-TO-DATE
:compileReleaseUnitTestJava UP-TO-DATE
:compileReleaseUnitTestSources UP-TO-DATE
:assembleReleaseUnitTest
:testRelease
:test
:check
:build

BUILD SUCCESSFUL

Total time: 1 mins 20.833 secs
```

## Install

```shell
$ adb devices
adb server is out of date.  killing...
* daemon started successfully *
List of devices attached 
KROJAUPJD6U8QCT8	device

$ adb install 2048-android-release.apk
3829 KB/s (625867 bytes in 0.159s)
	pkg: /data/local/tmp/2048-android-release.apk
Success
```



##License

2048-android is licensed under the [MIT license.](https://github.com/uberspot/2048-android/blob/master/LICENSE)
