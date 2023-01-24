# nginx2

## Description
nginx tewas

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nginx2`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nginx2`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nginx2
kpt live apply nginx2 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
