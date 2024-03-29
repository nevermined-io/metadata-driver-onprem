[![banner](https://raw.githubusercontent.com/nevermined-io/assets/main/images/logo/banner_logo.png)](https://nevermined.io)

# Metadata On-Premise Driver

> 💧 Metadata On-Premise Driver Implementation
> [nevermined-io](https://nevermined.io)

[![PyPI](https://img.shields.io/pypi/v/nevermined-metadata-driver-onprem.svg)](https://pypi.org/project/nevermined-metadata-driver-onprem/)
[![Python package](https://github.com/nevermined-io/metadata-driver-onprem/workflows/Python%20package/badge.svg)](https://github.com/nevermined-io/metadata-driver-onprem/actions)

---

## Table of Contents

- [Metadata On-Premise Driver](#metadata-on-premise-driver)
  - [Table of Contents](#table-of-contents)
  - [Setup](#setup)
  - [Testing](#testing)
  - [New Version](#new-version)
  - [Attribution](#attribution)
  - [License](#license)

---

## Setup

You don't have to set any Brizo configuration settings or other configuration settings to use on-premise storage with Brizo. You just need to make sure that Brizo can resolve the file URLs. For more details, see [the tutorial about setting up on-premise storage](https://docs.oceanprotocol.com/tutorials/on-premise-for-brizo/).


## Testing

Automatic tests are setup via Travis, executing `tox`.
Our tests use the pytest framework.

## New Version

The `bumpversion.sh` script helps to bump the project version. You can execute the script using as first argument {major|minor|patch} to bump accordingly the version.

## Attribution

This project is based in the Ocean Protocol [osmosis-on-premise-driver](https://github.com/oceanprotocol/osmosis-on-premise-driver).
It keeps the same Apache v2 License and adds some improvements. See [NOTICE file](NOTICE).

## License

```
Copyright 2020 Keyko GmbH
This product includes software developed at
BigchainDB GmbH and Ocean Protocol (https://www.oceanprotocol.com/)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
