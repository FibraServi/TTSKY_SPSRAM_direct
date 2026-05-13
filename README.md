# Sky130 Tiny Tapeout Single Port SRAM

This is design for a single port SRAM block with pins connected directly to TT tile pins. It's 128 words of 8 bits which fits in a 1x1 tile.

## Build the LibreLane Design

Install LibreLane: https://librelane.readthedocs.io/en/stable/installation/nix_installation/index.html

Enable a Nix shell: `nix-shell`

Build the design: `librelane config.yaml`

View the design in OpenROAD: `librelane config.yaml --last-run --flow OpenInOpenROAD`
