# CUBA Gradle Plugin

[![license](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg?style=flat)](http://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/cuba-platform/cuba-gradle-plugin.svg?branch=master)](https://travis-ci.org/cuba-platform/cuba-gradle-plugin)
[![Join the chat at https://gitter.im/cuba-platform/cuba](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/cuba-platform/cuba)

[CUBA Platform](https://www.cuba-platform.com) is a high level framework for rapid development of enterprise applications with rich web interface.

CUBA Gradle Plugin is required to build the platform and applications.

For more information see [github.com/cuba-platform/cuba](https://github.com/cuba-platform/cuba).

## Build and install

In order to build the project from source, you need to install the following:
* Java 8 Development Kit (JDK)
* [Gradle](https://gradle.org) (tested on 3.1, but newer versions may also work)

Open terminal and run the following command to build and install the plugin into your local Maven repository (`~/.m2`):
```
    gradlew install    
```

## Development

We use IntelliJ Idea IDE for development.

1. Generate IntelliJ Idea project files:
```
   gradlew idea
```

2. Open the .ipr file and start working on the project