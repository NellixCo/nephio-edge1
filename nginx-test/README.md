# nginx-test

## Description
nginx test example

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nginx-test`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nginx-test`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nginx-test
kpt live apply nginx-test --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
