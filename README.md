# AEM Parent POM (Uber JAR)

[Olson Digital](http://www.digitalatolson.com/)

## Overview

Maven parent POM for AEM projects that defines a dependency management section containing the Adobe "Uber JAR" and additional dependencies that are provided by the OSGi container.

AEM projects that define this project as the parent will only need to specify a &lt;dependencies&gt; section containing the subset of dependencies in use and may omit the version and scope definitions.

## Versioning

Follows [Semantic Versioning](http://semver.org/) guidelines.