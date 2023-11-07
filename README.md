# UMD Libraries Fedora 4 Authentication Utilities

* [AuthTokenService](src/main/java/edu/umd/lib/fcrepo/AuthTokenService.java): Generate JWT auth tokens.
* [LdapRoleLookupService](src/main/java/edu/umd/lib/fcrepo/LdapRoleLookupService.java): Look up a
  user in an LDAP directory and return either "fedoraAdmin" or "fedoraUser", depending on the
  configured role mappings.

## Build

To build the utility

```sh
mvn clean package
```

## Deploy

To deploy the package to Nexus

```sh
mvn deploy
```
