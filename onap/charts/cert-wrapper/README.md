# cert-wrapper

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] cert-wrapper`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree cert-wrapper`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init cert-wrapper
kpt live apply cert-wrapper --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
