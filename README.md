# tf-cert-prep

## Installation

```
TERRAFORM_VERSION="1.9.2"
brew install tfenv
tfenv install $TERRAFORM_VERSION
tfenv use $TERRAFORM_VERSION
tfenv pin
brew install warrensbox/tap/tgswitch
brew install tflint
tflint init
```

## Lint your code

```
tflint
```

