# Eclipse Copyright Generator

This is an Eclipse extension to help generating / updating copyright.

## Description

Fork of [Eclipse Copyright Generator project](https://github.com/jmini/Eclipse-Copyright-Generator) on Github, which is a fork of the [Eclipse Copyright Generator project](http://sourceforge.net/projects/eclipsecopyrigh/) on sourceforge.

Initial work by Eric Wuillai. Contributors: Jeremie Bresson, Matthew Krupcale, Roger Chen.

## Build

This project uses [Tycho](https://github.com/eclipse-tycho/tycho) with [Maven](https://maven.apache.org/) to build. It requires Maven 3.9.0 or higher version.

Dev build:

```
mvn clean verify
```

Release build:

```
mvn clean org.eclipse.tycho:tycho-versions-plugin:set-version -DnewVersion=2.0.0 verify
```



