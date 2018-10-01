# MiniJRE

## Description

Compact version of Oracle Java Runtime Environment.
Removed many seldom used files.

Results for __jre-8u171-windows-i586.tar.gz__:

|           | Size  |
|-----------|-------|
|Oracle JRE | 162Mb |
| Mini JRE  | __50Mb__  |

## Usage

* Download [JRE](https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html)
* Rename build.properties.template to build.properties
* Open build.properties and set jre.src=&lt;Path to JRE&gt;
* Run ant (If you don't have Apache Ant installed download it [here](https://ant.apache.org/bindownload.cgi))

Result will be in __.\build\jre__
