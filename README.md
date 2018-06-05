# RH-SSO Parent

RH-SSO parent project to define dependencies.

## Versioning

Synchronized with RH-SSO versioning.

## Deployment on Maven repository

 ```bash
 mvn clean deploy -Pnexus
 ```

**Nexus** maven profile defines:

    <nexus.url.release>${nexus.url}/content/repositories/releases</nexus.url.release>
    <nexus.url.snapshot>${nexus.url}/content/repositories/snapshots</nexus.url.snapshot>

## Author

Malys for [Lyra](https://lyra.com).

