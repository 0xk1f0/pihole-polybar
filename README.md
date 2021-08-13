# pihole-polybar
A module for polybar, which outputs various pihole status messages via API calls

# Installation

1. Paste the module code into your polybar configuration
2. Place pihole-status.sh in a folder of your choice and copy the filepath
3. Replace the placeholder filepath in the module code with your actual filepath to the script

## Module

```bash
[module/pihole-polybar]
type = custom/script
exec = ~/yourFilePath
interval = 120
format = pihole:  <label>
label-font = 1
```
