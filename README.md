maven-repository
================

Maven repository with artifacts some of my project depend on and could not be resolved otherwise 

Repository declaration:

    <repository>
        <id>r-h-repository</id>
        <name>Maven repository for artifacts which some r-h-projects depend on</name>
        <url>https://raw.github.com/r-h/maven-repository/master/snapshots</url>
    </repository>
    
**Note for Nexus users:** This is a raw GitHub repository, so there are some features that do not work.
Thanks to [galan](https://github.com/galan/maven-repository) and [sagemintblue](https://github.com/sagemintblue/sagemintblue-repositories#proxying-sagemintblue-repositories-with-nexus) for pointing this out. 

You have to disable the following features when setting up the Proxy-Repository:

* Download Remote Indexes: False
* Auto Blocking Enabled: False
* Allow File Browsing: False

# Available Artifacts

## [wicket-jsr303-validators](https://code.google.com/p/wicket-jsr303-validators/)

    <dependency>
        <groupId>com.zenika.wicket.contrib</groupId>
			<artifactId>wicket-jsr303-validators</artifactId>
			<version>1.0-SNAPSHOT</version>
    </dependency>

Released under [Apache License](http://www.apache.org/licenses/LICENSE-2.0), development seems to be ceased.

Native JSR-303 validation support is incorporated in [Wicket6](http://www.wicket-library.com/wicket-examples-6.0.x/bean-validation)

## [jqgrid](https://code.google.com/p/wiquery-plugins/)

    <dependency>
       <groupId>com.wiquery-plugins</groupId>
			<artifactId>jqgrid</artifactId>
			<version>1.2-SNAPSHOT</version>
    </dependency>

Released under [Apache License](http://www.apache.org/licenses/LICENSE-2.0), development seems to be ceased.

Alternatives might be [InMethodGrid](https://github.com/wicketstuff/core/wiki/InMethodGrid) or [Editable-Grid](https://github.com/wicketstuff/core/wiki/Editable-Grid) 
 