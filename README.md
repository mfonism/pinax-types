![](http://pinaxproject.com/pinax-design/patches/pinax-types.svg)

# Pinax Types

[![](https://img.shields.io/pypi/v/pinax-types.svg)](https://pypi.python.org/pypi/pinax-types/)

[![CircleCi](https://img.shields.io/circleci/project/github/pinax/pinax-types.svg)](https://circleci.com/gh/pinax/pinax-types)
[![Codecov](https://img.shields.io/codecov/c/github/pinax/pinax-types.svg)](https://codecov.io/gh/pinax/pinax-types)
[![](https://img.shields.io/github/contributors/pinax/pinax-types.svg)](https://github.com/pinax/pinax-types/graphs/contributors)
[![](https://img.shields.io/github/issues-pr/pinax/pinax-types.svg)](https://github.com/pinax/pinax-types/pulls)
[![](https://img.shields.io/github/issues-pr-closed/pinax/pinax-types.svg)](https://github.com/pinax/pinax-types/pulls?q=is%3Apr+is%3Aclosed)

[![](http://slack.pinaxproject.com/badge.svg)](http://slack.pinaxproject.com/)
[![](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)


## Table of Contents

* [About Pinax](#about-pinax)
* [Overview](#overview)
  * [Supported Django and Python versions](#supported-django-and-python-versions)
* [Documentation](#documentation)
  * [Installation](#installation)
* [Change Log](#change-log)
* [Contribute](#contribute)
* [Code of Conduct](#code-of-conduct)
* [Connect with Pinax](#connect-with-pinax)
* [License](#license)


## About Pinax

Pinax is an open-source platform built on the Django Web Framework. It is an ecosystem of reusable
Django apps, themes, and starter project templates. This collection can be found at http://pinaxproject.com.


## pinax-types

### Overview

#### Supported Django and Python versions

Django \ Python | 2.7 | 3.4 | 3.5 | 3.6
--------------- | --- | --- | --- | ---
1.11 |  *  |  *  |  *  |  *  
2.0  |     |  *  |  *  |  *


## Documentation

The ``pinax-types`` documentation is currently under construction. If you would like to help us write documentation, please join our Pinax Project Slack team and let us know! 
We recently did a Pinax Hangout on ``pinax-types``, you can read the recap blog post and find the video here http://blog.pinaxproject.com/2016/04/28/recap-april-pinax-hangout/

### Installation

To install pinax-types:

```shell
    $ pip install python-dateutil pinax-types
```

Add `pinax.types` to your `INSTALLED_APPS` setting:

```python
    INSTALLED_APPS = (
        ...
        "pinax.types",
        ...
    )
```
   
## Change Log   
   
### 1.0.0

* Add Django 2.0 compatibility testing
* Drop Django 1.8, 1.9, 1.10, and Python 3.3 support
* Convert CI and coverage to CircleCi and CodeCov
* Add PyPi-compatible long description
* Move documentation to README.md


## Contribute

For an overview on how contributing to Pinax works read this [blog post](http://blog.pinaxproject.com/2016/02/26/recap-february-pinax-hangout/)
and watch the included video, or read our [How to Contribute](http://pinaxproject.com/pinax/how_to_contribute/) section.
For concrete contribution ideas, please see our
[Ways to Contribute/What We Need Help With](http://pinaxproject.com/pinax/ways_to_contribute/) section.

In case of any questions we recommend you join our [Pinax Slack team](http://slack.pinaxproject.com)
and ping us there instead of creating an issue on GitHub. Creating issues on GitHub is of course
also valid but we are usually able to help you faster if you ping us in Slack.

We also highly recommend reading our blog post on [Open Source and Self-Care](http://blog.pinaxproject.com/2016/01/19/open-source-and-self-care/).


## Code of Conduct

In order to foster a kind, inclusive, and harassment-free community, the Pinax Project
has a [code of conduct](http://pinaxproject.com/pinax/code_of_conduct/).
We ask you to treat everyone as a smart human programmer that shares an interest in Python, Django, and Pinax with you.


## Connect with Pinax

For updates and news regarding the Pinax Project, please follow us on Twitter [@pinaxproject](https://twitter.com/pinaxproject)
and check out our [Pinax Project blog](http://blog.pinaxproject.com).


## License

Copyright (c) 2012-2018 James Tauber and contributors under the [MIT license](https://opensource.org/licenses/MIT).
