# aaf

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] aaf`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree aaf`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init aaf
kpt live apply aaf --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
