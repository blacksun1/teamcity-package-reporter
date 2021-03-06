# teamcity-package-reporter

[![Build Status](https://snap-ci.com/blacksun1/teamcity-package-reporter/branch/master/build_image)](https://snap-ci.com/blacksun1/teamcity-package-reporter/branch/master)
[![Dependency Status](https://david-dm.org/blacksun1/teamcity-package-reporter.svg)](https://david-dm.org/blacksun1/teamcity-package-reporter)
[![devDependency Status](https://david-dm.org/blacksun1/teamcity-package-reporter/dev-status.svg)](https://david-dm.org/blacksun1/teamcity-package-reporter#info=devDependencies)

## How to install

```bash
npm install -g teamcity-package-reporter
```

## How to use

Change directory into a folder with an existing package.json file and then execute `teamcity-package-reporter`. It will report the following paramaters to TeamCity:

* `PACKAGE_NAME`: The packages name attribute.
* `PACKAGE_DESCRIPTION`: The packages description attribute.
* `PACKAGE_VERSION`: The packages version attribute.
* `PACKAGE_LICENSE`: The packages license attribute.

Therefore, to use it, make sure that you add parameters with the same names in TeamCity and then execute the command as one of your build tasks.
