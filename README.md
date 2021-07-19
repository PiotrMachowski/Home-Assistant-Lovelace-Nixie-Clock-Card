# Nixie Clock card

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://hacs.xyz/docs/faq/custom_repositories)
[![buymeacoffee_badge](https://img.shields.io/badge/Donate-Buy%20Me%20a%20Coffee-ff813f?style=flat)](https://www.buymeacoffee.com/PiotrMachowski)
[![paypalme_badge](https://img.shields.io/badge/Donate-PayPal-0070ba?style=flat)](https://paypal.me/PiMachowski)

This card displays a nixie tube clock. 

## Configuration options

| Key | Type | Required | Default | Description |
| --- | --- | --- | --- | --- |
| `type` | `string` | `true` | - | `custom:nixie-tube-clock` |
| `use_military` | `boolean` | `false` | `true` | Use 24h format |
| `hide_seconds` | `boolean` | `false` | `false` | Hides seconds |
| `mode` | `string` | `true` | - | Changes images of tubes. One of: `mode1`, `mode2`, `mode3`, `mode4` |

### Example configuration
```yaml
type: custom:nixie-clock-card
hide_seconds: false
use_military: false
mode: mode4
```

## Modes
`mode1`:

![mode1](https://github.com/PiotrMachowski/Home-Assistant-Lovelace-Nixie-Clock-Card/blob/master/images/mode1.png)

`mode2`:

![mode2](https://github.com/PiotrMachowski/Home-Assistant-Lovelace-Nixie-Clock-Card/blob/master/images/mode2.png)

`mode3`:

![mode3](https://github.com/PiotrMachowski/Home-Assistant-Lovelace-Nixie-Clock-Card/blob/master/images/mode3.png)

`mode4`:

![mode4](https://github.com/PiotrMachowski/Home-Assistant-Lovelace-Nixie-Clock-Card/blob/master/images/mode4.png)


## License of nixie tube images

Images of nixie tubes by Čestmír Hýbl, free for non-commercial use only.
[Project's website](http://cestmir.freeside.sk/projects/dhtml-nixie-display/)


<a href="https://www.buymeacoffee.com/PiotrMachowski" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
