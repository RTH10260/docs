hubiC
====

> hubiC, the online storage solution, was developed by the OVH group, a French company specialised in data hosting. Datacentres in France: Roubaix, Gravelines and Strasbourg.

## Connecting

hubiC is using [OpenStack Swift](index.md) APIs for its storage service but requires additional authentication using OAuth 2.0 to access the service.

### OAuth 2.0 Authentication

Connect using the OAuth 2.0 connection profile:

- {download}`Download<http://profiles.cyberduck.io.s3.amazonaws.com/hubiC.cyberduckprofile>` the *hubiC Cyberduck Connection Profile* or install it from *Preferences… → Profiles*.

### Gateway for Authentication

Use the [Openstack Swift (v1) profile](index.md) together with an authentication gateway.

- [HubiC to OpenStack Swift Gateway](https://github.com/oderwat/hubic2swiftgate)
- [Node hubiC Swift Authentication](https://github.com/gierschv/node-hubic-swiftauth)

## Known Issues

- Interoperability with hubiC (OVH) (Issue [#7764](https://github.com/iterate-ch/cyberduck/issues/7764))