# Keycloak auth plugin

## Dependencies

* JDK
* maven

## Extensions

All keycloak extensions should be placed in subdirectories of this directory,
e.g. `keycloak-isambard-auth-plugin`.

## Building the extensions

You can build each extension by changing into that extension's directory
and running `mvn clean install`. For example:

```
cd keycloak-isambard-auth-plugin
mvn clean install
```

This will place the JAR file into the `target` directory of the extension.

Simply copy this into the correct location for keycloak, and it will be
available for use.

