## Sandpiper keyboard PCB and enclosure design files

This repo contains the PCB files for sandpiper project.

## Notes

- This PCB is optional and is not required to be able to run sandpiper. It merely contains a custom USB keyboard that fits into the provided enclosure.
- The enclosure is also optional. Sandpiper does not requre an enclosure to function and can be booted from pretty much any Xynq7020 board with 512Mbytes of memory, an etnernet and USB controller, plus some HDMI connector leading to the FPGA pins. For boards with more memory than 512Mbytes the device tree and SDK has to be updated to shift device addresses to the last 32Mbytes of memory. This also means th driver has to be rebuilt with those addresses (in the future driver will read them from the devic tree so there won't be a need to rebuild it)
- The enclosure is designed to be printed in one big piece for the top and bottom halves (plus the side connection pieces) Recommended material is PETG-strong as it is very unlikely to warp. Other materials might also work but print at your own risk or split the design manually, as there's no built-in measures in the design to avoid warping.