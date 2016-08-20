# Bintray publishing scripts

Based on https://github.com/nuuneoi/JCenter

Additional features and changes:

* Removed dependancy on `local.properties` so you can use the global `gradle.properties` or some other way of storing credentials
* Added optional support for dry run, auto publish and override
* Added GPG support
* Added Maven sync support
