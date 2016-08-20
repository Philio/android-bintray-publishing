# Bintray publishing scripts

Based on https://github.com/nuuneoi/JCenter

Additional features and changes:

* Removed dependancy on `local.properties` so you can use the global `gradle.properties` or some other way of storing credentials
* Removed some of the optional `pkg` properties as these can just be set via Bintray site when adding a new repo/package
* Added support for dry run, auto publish and override
* Added version specific properties like description and release date
* Added GPG support
* Added Maven sync support
