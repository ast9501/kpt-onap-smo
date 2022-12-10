# mariadb-galera

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] mariadb-galera`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree mariadb-galera`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init mariadb-galera
kpt live apply mariadb-galera --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
