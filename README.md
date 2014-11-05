## Orbit Data Messages
[![Build Status](http://img.shields.io/travis/RazerM/orbit-data-messages.svg?style=flat-square)](https://travis-ci.org/RazerM/orbit-data-messages) [![Test Coverage](http://img.shields.io/codecov/c/github/RazerM/orbit-data-messages.svg?style=flat-square)](https://codecov.io/github/RazerM/orbit-data-messages) [![PyPI Version](http://img.shields.io/pypi/v/orbit-data-messages.svg?style=flat-square)](https://pypi.python.org/pypi/orbit_data_messages/) [![Python Version](http://img.shields.io/badge/python-3.4%2B-brightgreen.svg?style=flat-square)](https://www.python.org/download/releases/3.4.0/) [![MIT License](http://img.shields.io/badge/license-MIT-red.svg?style=flat-square)](https://raw.githubusercontent.com/RazerM/orbit-data-messages/master/LICENSE)



This package is for creating valid ASCII OPM, OMM, and OEM files using Python.

Currently, only the orbital parameter message (OPM) module has been implemented.

### Installation

```bash
$ pip3 install orbitdatamessages
```

### Testing

```bash
$ python3 setup.py test
```

### Usage

```python
import orbitdatamessages.orbital_parameter_message as opm
```