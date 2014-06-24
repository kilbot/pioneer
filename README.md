# Dill.js
[![Build Status](http://img.shields.io/travis/mojotech/dill.js.svg?style=flat
)](https://travis-ci.org/mojotech/dill.js)
[![Gitter chat](http://img.shields.io/badge/gitter-chat-blue.svg?style=flat
)](https://gitter.im/mojotech/dill.js)

### Integration tests made easy.

Dill.js provides an abstraction layer between your integration tests and your DOM markup, DRYing up your step definitions and consolidating how people interact with the DOM in tests.

![see it live](http://i.imgur.com/kTjwloS.gif)
[View our Getting Started Guide](docs/getting_started.md) |
[See an example repo.](https://github.com/samccone/dill.js-getting-started)

# Docs
* [Getting Started](docs/getting_started.md)

* [Widget](docs/widget.md)
* [Widget.List](docs/list.md)
* [Widget.View](docs/view.md)
* [Widget.Iframe](docs/iframe.md)

* [Globals](docs/globals.md)
* [Driver Configuration](#driver-configuration)


## Driver Configuration
You can customize which driver your tests use via the `--driver` command line flag. The default driver is chrome.

See http://selenium.googlecode.com/git/docs/api/javascript/class_webdriver_Capabilities.html for available options.
