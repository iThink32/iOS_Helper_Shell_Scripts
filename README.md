# iOS_Helper_Shell_Scripts
a repo that contains shell scripts that help in iOS development

## This readme is a one stop helper for all the scripts added in this repo.

### SelectDefaultXcode.sh

#### Info

This script is used to modify the xcode version in a module map embedded in a framework.This script is useful when you work with thrid party frameworks that have their own internal module maps but when your xcode version is not in sync with theirs. for eg their module map contain Xcode.app but your default Xcode may be named as Xcode9.3 on your mac.

#### Usage :-

```
sh SelectDefaultXcode.sh

or 

sh SelectDefaultXcode.sh path/to/framework

```

in the first case it will assume that your framework is in the current working directory , in the second it will work on the path of the framework specified.
