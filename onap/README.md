# onap

## Description
The onap part component of onap-based smo.

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] onap`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree onap`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init onap
kpt live apply onap --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/

## Recommand Install Order
1. strimzi
2. *-wrapper
3. aaf
4. mariadb, postgres
5. dmaap
6. a1policymanagement
7. dcaegen2-service
8. policy

## ToDo
* Fix: strimzi-kafka-operator pkg will failed to install CRDs if using `ConfigSync` to sync it
* onap pkg depencency 