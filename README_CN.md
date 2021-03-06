![Image text](https://raw.githubusercontent.com/Deepblue1996/DpWorkAX/master/ic_logo.png)

<a href="http://developer.android.com/index.html"><img src="https://img.shields.io/badge/platform-android-green.svg"></a>
[![](https://jitpack.io/v/Deepblue1996/Bun.svg)](https://jitpack.io/#Deepblue1996/Bun)
<a href="https://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/license-apache-green.svg"></a>

DpWorkAX是一款Android应用程序开发框架, 简单，便捷，集合(原DpWork 增加支持Android X)

采用 - 单Activity+ 多Fragment框架设计

支持自适应布局，高自定义弹窗支持，网络层Dove，图片框架glide,
openGL音频媒体播放，实用工具类集合，内置国际化语言选择，支持高级防闪退机制等

注意: 新版本以后不再更新媒体版本，可以下载wlmedia-1.0.0-beta11.aar，自行引入 (MusicLibUtil保留，可以参考使用)

欢迎加入QQ群: 257015764

### 查看使用示例源码 - <a href="https://github.com/Deepblue1996/DpWorkDemo">java-AndroidStudio2.3.3</a>/<a href="https://github.com/Deepblue1996/QiaoQiao">kotlin-AndroidStudio4.0+/瞧瞧</a>

[[English document]](https://github.com/Deepblue1996/DpWorkAX/blob/master/README.md)

## 如果使用

第一步:

创建并打开 Application(自定义名字) Class,

继承 DpWorkApplication

第二步:

创建并打开 WorkCore(自定义名字) Class,

继承 DpWorkCore

第三步:

创建并打开 WorkCore(自定义名字) Class,

继承 DpWorkCore, 头部添加主入口注解@DpMainScreenKt，入口类参数

<pre><code>@DpMainScreen(*::class)
</code></pre>

## 基础配置

要在构建中加入Git项目:

步骤1.

在根Gradle中, repositories里添加:

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

步骤2. 添加依赖关系

	Android Studio 4.0 +:

    implementation 'com.deep:DpWorkAX:1.6.5'

步骤3. 使用混淆，可参考这里的 proguard-rules.pro

步骤4. Gradle

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

