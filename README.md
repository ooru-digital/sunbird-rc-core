# Sunbird Registry and Credentials

![Build](https://github.com/Sunbird-RC/sunbird-rc-core/actions/workflows/maven.yml/badge.svg)


Sunbird RC is an open-source software framework for rapidly building electronic
registries, enable atestation capabilities, and build verifiable credentialling
with minimal effort.

Registry is a shared digital infrastructure which enables authorized data
repositories to publish appropriate data and metadata about a user/entity along
with the link to the repository in a digitally signed form. It allows data
owners to provide authorized access to other users/entities in controlled manner
for digital verification and usage.


## Installation and Setup

See
[the installation and getting started guide](https://docs.sunbirdrc.dev/developer-documentation/installation-guide).

More documentation can be found [here](https://docs.sunbirdrc.dev/).

## [Help / Discussion](https://github.com/Sunbird-RC/community/discussions)

## License

This repository's contents are licensed under the MIT license. See the
[license file](./LICENSE) for more details.


# Credflow-sunbird-rc-2.0.0

## Installation and Setup

1. Need to set up the vault by uisng script `setup_vault.sh`
2. Need to update the `VAULT_TOKEN` in `.env`. 
3. Run only vault, db and keycloak through `docker-compose -f docker-compose.yml up -d vault db keycloak`
4. Unseal vault by uisng `keys.txt`. 
5. Run all the containers `docker-compose -f docker-compose.yml up -d`

Postman collections: 

    Refer: docs