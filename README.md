# kpt-onap-smo

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] kpt-onap-smo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree kpt-onap-smo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init kpt-onap-smo
kpt live apply kpt-onap-smo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
