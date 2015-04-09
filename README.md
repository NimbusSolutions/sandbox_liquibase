# sandbox_liquibase
trying out liquibase to manage db versions.

# prerequist environment
* mysql running
* mysql workbencch
* maven

# xml changelog config
Using some of the [best practices](http://www.liquibase.org/bestpractices.html) the project contains a _liquibase.properties_ which point to the changelog files. There is a master changelog file that includes each change log.

# json & yaml changelog config
Almost identical to the xml config but an extra snakeyaml dependency is needed in the plugin definition in the POM
