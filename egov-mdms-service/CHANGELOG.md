

# Changelog
All notable changes to this module will be documented in this file.

## 1.3.0 - 2020-05-29

- Added typescript definition generation plugin
- Upgraded to `tracer:2.0.0-SNAPSHOT`
- Upgraded to spring boot `2.2.6-RELEASE`
- Upgraded to spring-kafka `2.3.7.RELEASE`
- Upgraded to spring-integration-kafka `3.2.0.RELEASE`
- Upgraded to jackson-dataformat-yaml `2.10.0`
- Upgraded to jackson-databind `2.10.0`
- Removed the spring-integration-java-dsl because from Spring Integration 5.0, the 
  'spring-integration-java-dsl' dependency is no longer needed. The Java DSL has 
  been merged into  the core project.

## 1.2.0

- Removed reload consumers
- Removed `start.sh` and `Dockerfile`
- Remove reload endpoints
- Remove all unused dependencies
- Migrated to the latest Spring Boot `2.2.6`
- Upgraded to tracer `2.0.0`

## 1.1.0

- Added support for partial files using `isMergeAllowed` flag in the config file. By default, merge is `false`

## 1.0.0

- Base version
