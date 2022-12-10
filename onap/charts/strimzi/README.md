# strimzi

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] strimzi`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree strimzi`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init strimzi
kpt live apply strimzi --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
