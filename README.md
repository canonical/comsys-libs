# Commercial Systems libraries for Operator Framework Charms

## Description

The `comsys-libs` charm provides a set of [charm libraries] which offers convenience methods
for interacting with Canonical's internal data platform.

This charm is **not meant to be deployed** itself, and is used as a mechanism for hosting libraries
only.

## Usage

This charm is not intended to be deployed. It is a container for standalone charm libraries, which
can be managed using `charmcraft fetch-lib`
([ref. link](https://discourse.charmhub.io/t/how-to-find-and-use-a-charm-library/5780)), after
which they may be imported and used as normal charms. For example:

`charmcraft fetch-lib charms.comsys_libs.v0.kubernetes_statefulset_patch`

Following are the libraries available in this repository:

- `kubernetes_statefulset_patch` - Library to manage the Kubernetes resources at a container level.


## Contributing

Please see the [Juju SDK docs](https://juju.is/docs/sdk) for guidelines on enhancements to this
charm following best practice guidelines, and `CONTRIBUTING.md` for developer guidance.


[charm libraries]: https://juju.is/docs/sdk/libraries
[relations]: https://juju.is/docs/sdk/relations
