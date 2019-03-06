# AEM Parent Uber Jar POM

[ICF Next](http://www.icfnext.com/)

## Overview

Maven parent POM for AEM projects that defines a dependency management section containing the Adobe "Uber JAR" and additional dependencies that are provided by the OSGi container.

AEM projects that define this project as the parent will only need to specify a &lt;dependencies&gt; section containing the subset of dependencies in use and may omit the version and scope definitions.

## Compatibility

AEM Parent POM Version(s) | AEM Version
------------ | -------------
7.0.0 | 6.3.3, 6.4
6.4.2 | 6.4.2
6.4.1.1 | 6.4.1
6.4.1 | 6.4.0
6.4.0 | 6.4.0
6.3.2.2 | 6.3.2.2
6.3.2 | 6.3.2
6.3.1.2.1 | 6.3.1.2
6.3.1.2 | 6.3.1.2
6.3.1.1 | 6.3.1.1
6.3.0 | 6.3.0
6.2.0-SP1 | 6.2.1
6.2.0 | 6.2.0

## Versioning

Follows [Semantic Versioning](http://semver.org/) guidelines.