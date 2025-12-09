# Nanoleaf2

[![GitHub Release](https://img.shields.io/github/v/release/loebi-ch/nanoleaf2?style=flat-square)](https://github.com/loebi-ch/nanoleaf2/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Home Assistant](https://img.shields.io/badge/Home%20Assistant-Custom%20Integration-41bdf5?style=flat-square&logo=homeassistant)](https://www.home-assistant.io/)

A Home Assistant custom integration that replaces the core integration `nanoleaf` with support for Nanoleaf Essential devices and Screen Mirroring capability.

## Why This Integration?

Home Assistant's built-in [Nanoleaf](https://www.home-assistant.io/integrations/nanoleaf/) is outdated and not maintained anymore.
**Nanoleaf2** is a fork of the built-in integration, but provides the following further functionalities:

- **Nanoleaf Essentials** Nanoleaf released new devices that are based on a different API. `nanoleaf2` supports these new so called Nanoleaf Essentials devices.
- **Screen Mirroring** - Nanoleaf 4D Screen Mirror retrofits Ambilight to a TV. `nanoleaf2` supports to choose the Screen Mirror modes (1D, 2D, 3D, 4D) from the effects in Home Assistant.

As the predecessor is based on `aionanoleaf` for the API communication, `nanoleaf2` is based on the successor `aionanoleaf2` which supports the old API and also the new API for Nanoleaf Essentials.

It is backwards compatible.

## Installation

### Manual Installation

1. Download the latest release from [GitHub Releases](https://github.com/loebi-ch/nanoleaf2/releases)
2. Copy the `custom_components/nanoleaf2` folder to your `config/custom_components/` directory
3. Restart Home Assistant
4. Nanoleaf devices are automatically found
5. Follow the setup wizard to add new devices to your Home Assistant

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
