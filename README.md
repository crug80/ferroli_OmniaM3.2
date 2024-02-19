# Ferroli Omnia M 3.2

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![Community Forum][forum-shield]][forum]
[![License][license-shield]](LICENSE)

_Integration to integrate with [ferroli_omnia_m32][ferroli_omnia_m32]._

**This integration will set up the following platforms.**

Platform | Description
-- | --
`binary_sensor` | Show something `True` or `False`.
`sensor` | Show info from blueprint API.
`switch` | Switch something `True` or `False`.

## Installation

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `ferroli_omnia_m32`.
1. Download _all_ the files from the `custom_components/ferroli_omnia_m32/` directory (folder) in this repository.
1. Place the files you downloaded in the new directory (folder) you created.
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Ferroli Omnia M 3.2"

## Configuration is done in the UI

<!---->

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

***

[ferroli_omnia_m32]: https://github.com/crug80/ferroli_OmniaM3.2
[commits-shield]: https://img.shields.io/github/commit-activity/y/crug80/ferroli_OmniaM3.2
[commits]: https://github.com/crug80/ferroli_OmniaM3.2/commits/main/
[exampleimg]: example.png
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/
[license-shield]:https://img.shields.io/github/license/crug80/ferroli_OmniaM3.2
#[releases-shield]: https://img.shields.io/github/release/ludeeus/integration_blueprint.svg?style=for-the-badge
[releases]: https://github.com/crug80/ferroli_OmniaM3.2/releases
