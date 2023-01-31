[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)  [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/IvanVojtko/)

# Google Fit Sensor Component

Based on

- <https://github.com/IvanVojtko/googlefit-homeassistant>

Creates Google Fit sensors.
At the moment, the component provides following measurements:

- steps
- distance
- time
- calories
- weight
- height
- sleep
- heartrate
- oxygen
- blood pressure
- nutrition
- hydratation
- BMR

# Installation

## HACS - Recommended
- Have [HACS](https://hacs.xyz) installed, this will allow you to easily update.
- Add `https://github.com/AFumi39/googlefit-homeassistant` as a [custom repository](https://github.com/AFumi39/googlefit-homeassistant) with Type: Integration
- Click Install under "Google Fit" integration.
- Restart Home-Assistant.

## Manual
- Copy directory `custom_components/google_fit` to your `<config dir>/custom_components` directory.
- Configure.
- Restart Home-Assistant.

## Example configuration.yaml

In order to add this component as is, add a new sensor:

```yaml
sensor:
  - platform: google_fit
    name: Google Fit
```

## Google Fit credentials

Follow these instructions: <https://github.com/IvanVojtko/googlefit-homeassistant/blob/master/README.md#google-fit-credentials>
