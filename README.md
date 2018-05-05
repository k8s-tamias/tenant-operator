
## Tenant Operator For Kubernetes

The Tenant Operator is a controller for Kubernetes which allows the definition of quotas and restrictions for groups of users within a Kubernetes cluster. These quotas may span multiple namespaces, thus providing an extension to the isolation of users and quotas which is part of the core kubernetes system.

Currently this repository only contains a schema definition of the Tenant CRD. We are preparing a code drop to add functionality that implements the necessary behaviour.

The intended behaviour is described in the Google Doc [Kubernetes Tenant Controller](https://docs.google.com/document/d/1auNOT2Hpguaxcqg8dX6JLLw5-RYQ0Abp6_-OcUP4pbI/edit?usp=sharing). Please feel free to comment, should you have questions or suggestions.

## Contributing

Contributions are welcome! See [Contributing](CONTRIBUTING.md) to get started.

## Report a Bug

For filing bugs, suggesting improvements, or requesting new features, help out by opening an [issue](https://github.com/k8s-tamias/tenant-operator/issues).

## Licensing

The operator kit is under the Apache 2.0 license.

