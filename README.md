![Image text](https://raw.githubusercontent.com/Deepblue1996/DpWorkAX/master/ic_logo.png)

<a href="http://developer.android.com/index.html"><img src="https://img.shields.io/badge/platform-android-green.svg"></a>
[![](https://jitpack.io/v/Deepblue1996/Bun.svg)](https://jitpack.io/#Deepblue1996/Bun)
<a href="https://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/license-apache-green.svg"></a>

DpWorkAX is an Android application development framework that is simple, convenient and comprehensive(support for Android X was added to original DpWork)

Adopt - single Activity+ multi Fragment frame design

Support for adaptive layouts, high custom popup support, network layer Dove, image frame glide,
OpenGL audio media playback, utility class set, built-in internationalization language selection, support advanced anti - flashback mechanism

Welcome to QQ group: 257015764

### See using sample source code - <a href="https://github.com/Deepblue1996/DpWorkDemo">java-AndroidStudio2.3.3</a>/<a href="https://github.com/Deepblue1996/QiaoQiao">kotlin-AndroidStudio3.0+/瞧瞧</a>

[[中文文档]](https://github.com/Deepblue1996/DpWorkAX/blob/master/README_CN.md)

## How do I use DpWork

One:

Create and open the Application(custom name) Class,

Inheritance DpWorkApplication

Two:

Create and open the WorkCore(custom name) Class,

Inheritance DpWorkCore

Three:

Create and open the FirstScreen(custom name) Class,

Inherit BaseScreen and add the main entry annotation @DpMainScreen to the header

<pre><code>@DpMainScreen
</code></pre>

## Basic deployment

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
	    repositories {
            maven { url "https://maven.aliyun.com/repository/google" }
            maven { url "https://maven.aliyun.com/repository/public" }
            maven { url "https://maven.aliyun.com/repository/central" }
		    maven { url 'https://jitpack.io' }
		    maven { url 'https://wosk.top' }
	    }
	}

	app build.gradle

    buildFeatures{
        viewBinding = true
    }

Step 2. Add the dependency

	Android Studio 3.0 +:

    implementation 'com.deep:DpWorkAX:1.6.2'

Step 3. For confusion, refer to proguard-rules.pro here

Step 4. Gradle

## LICENSE

<pre><code>Copyright 2018 Deepblue

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</code></pre>


