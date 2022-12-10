# dcaegen2-services

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] dcaegen2-services`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree dcaegen2-services`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init dcaegen2-services
kpt live apply dcaegen2-services --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
