# nginx-ale

## Description
nginx for ale

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nginx-ale`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nginx-ale`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nginx-ale
kpt live apply nginx-ale --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
