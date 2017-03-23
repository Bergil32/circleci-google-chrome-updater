# Circleci Use Chrome Stable Version

To force the use of the latest stable version of Chrome on Circle CI, define those lines in your circle.yml configuration file

```
dependencies:
  pre:
    - curl -s https://raw.githubusercontent.com/Bergil32/circleci-google-chrome-updater/master/use_chrome_stable_version.sh | bash
```

