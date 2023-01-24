# nginx

## Description
nginx k8s package

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nginx`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nginx`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nginx
kpt live apply nginx --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
