# Mai Voron 2.4

## Printer
- 350x350
- CNC parts (except anything on the X axis)
- Updated as of 2025-06-27

## Steps for future upgrade
- Install MainsailOS from: https://docs-os.mainsail.xyz/getting-started/raspberry-pi-os-based
- Clone: https://github.com/thanhhaimai/dotfiles
- Clone: https://github.com/thanhhaimai/voron
- `cd dotfiles/rpi && ./setup.sh`
- `ln -s ~/voron/printer.cfg ~/printer_data/config/printer.cfg`
- `ln -s ~/voron/crowsnest.conf ~/printer_data/config/crowsnest.conf`
