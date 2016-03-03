# Easy routes plugin for [JOSM](https://josm.openstreetmap.de)

[![Build Status](https://img.shields.io/travis/floscher/easy-routes/gradle.svg?style=flat-square)](https://travis-ci.org/floscher/easy-routes)
[![latest release](https://img.shields.io/github/release/floscher/easy-routes.svg?style=flat-square)](https://github.com/floscher/easy-routes/releases/latest)
![License](https://img.shields.io/badge/license-GPLv2-blue.svg?style=flat-square)

## Setup instructions

Running JOSM with the plugin loaded:
```shell
./gradlew.bat runJosm # On Windows
./gradlew runJosm     # On other OSs
```

Building the plugin:
```shell
./gradlew.bat build # On Windows
./gradlew build     # On other OSs
```
Then you'll find the built jar-file in the `build/libs/` directory and reports in `build/reports/`.

Developing with Eclipse:
```shell
./gradlew.bat eclipse # On Windows
./gradlew eclipse     # On other OSs
```
After that simply import the project into Eclipse "as an existing project".
