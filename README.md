# xheep_opentitan_spi_host
Fork from OpenTitan SPI Host with X-HEEP specific improvements

This repository contains a modified version of the SPI HOST from OpenTitan:

```
git clone https://github.com/lowRISC/opentitan.git
cd opentitan/
git checkout 611d56f934a36991b1a61b46690243373e6806fe
```

and then the `spi_host.patch` has been applied.

To reproduce it, copy the `spi_host.patch` in the OpenTitan folder,
then:

```
cp spi_host.patch opentitan
cd opentitan/
git apply spi_host.patch
```

Only the files needed for the `X-HEEP` projects are kept.
