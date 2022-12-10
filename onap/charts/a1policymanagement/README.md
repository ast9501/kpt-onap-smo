# a1policymanagement

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] a1policymanagement`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree a1policymanagement`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init a1policymanagement
kpt live apply a1policymanagement --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
