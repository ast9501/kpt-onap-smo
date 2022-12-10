# repository-wrapper

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] repository-wrapper`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree repository-wrapper`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init repository-wrapper
kpt live apply repository-wrapper --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
