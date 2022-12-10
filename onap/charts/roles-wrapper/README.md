# roles-wrapper

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] roles-wrapper`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree roles-wrapper`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init roles-wrapper
kpt live apply roles-wrapper --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
