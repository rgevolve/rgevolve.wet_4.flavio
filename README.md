# rgevolve.wet_4.flavio

Package providing Renormalization Group Evolution matrices for the
**WET-4** in the **flavio** basis, following the
[wcxf](https://wcxf.github.io/) conventions for Wilson coefficient
bases.

It is a sub-package of the **rgevolve** ecosystem — a set of Python
namespace packages for fast renormalization group evolution of Wilson
coefficients in the SMEFT and the WET using the evolution matrix
formalism. See the [rgevolve organization](https://github.com/rgevolve)
for the full ecosystem and the
[`rgevolve` meta-package](https://github.com/rgevolve/rgevolve) for
installation in lockstep with the core and all companions.

<!-- BEGIN: auto-generated from data.h5 by .github/scripts/generate-readme.py — do not edit by hand -->

## Contents

This distribution bundles RG evolution matrices precomputed at
**4 scales** between **1.3** and
**4.2** GeV:

| scale (GeV) |
| ----------- |
| 1.3 |
| 2 |
| 2.75 |
| 4.2 |

Matrices are organised into **81 sectors** covering a total
of **1859 Wilson coefficients** (counting the real and imaginary
parts of complex coefficients separately):

| sector | # Wilson coefficients |
| ------ | --------------------- |
| `cdenue` | 10 |
| `cdenumu` | 10 |
| `cdenutau` | 10 |
| `cdmunue` | 10 |
| `cdmunumu` | 10 |
| `cdmunutau` | 10 |
| `cdtaunue` | 10 |
| `cdtaunumu` | 10 |
| `cdtaunutau` | 10 |
| `csenue` | 10 |
| `csenumu` | 10 |
| `csenutau` | 10 |
| `csmunue` | 10 |
| `csmunumu` | 10 |
| `csmunutau` | 10 |
| `cstaunue` | 10 |
| `cstaunumu` | 10 |
| `cstaunutau` | 10 |
| `cu` | 176 |
| `cucu` | 16 |
| `dF=0` | 341 |
| `etauemu` | 12 |
| `ffnuinui` | 42 |
| `ffnumunue` | 28 |
| `ffnumunutau` | 28 |
| `ffnutaunue` | 28 |
| `mue` | 128 |
| `muemutau` | 12 |
| `muenuenumu` | 4 |
| `muenuenutau` | 4 |
| `muenuinui` | 12 |
| `muenumunue` | 4 |
| `muenumunutau` | 4 |
| `muenutaunue` | 4 |
| `muenutaunumu` | 4 |
| `mutau` | 128 |
| `mutaunuenumu` | 4 |
| `mutaunuenutau` | 4 |
| `mutaunuinui` | 12 |
| `mutaunumunue` | 4 |
| `mutaunumunutau` | 4 |
| `mutaunutaunue` | 4 |
| `mutaunutaunumu` | 4 |
| `sd` | 176 |
| `sdemu` | 16 |
| `sdetau` | 16 |
| `sdmue` | 16 |
| `sdmutau` | 16 |
| `sdnuinui` | 12 |
| `sdnumunue` | 8 |
| `sdnumunutau` | 8 |
| `sdnutaunue` | 8 |
| `sdsd` | 16 |
| `sdtaue` | 16 |
| `sdtaumu` | 16 |
| `taue` | 128 |
| `tauenuenumu` | 4 |
| `tauenuenutau` | 4 |
| `tauenuinui` | 12 |
| `tauenumunue` | 4 |
| `tauenumunutau` | 4 |
| `tauenutaunue` | 4 |
| `tauenutaunumu` | 4 |
| `udenue` | 10 |
| `udenumu` | 10 |
| `udenutau` | 10 |
| `udmunue` | 10 |
| `udmunumu` | 10 |
| `udmunutau` | 10 |
| `udtaunue` | 10 |
| `udtaunumu` | 10 |
| `udtaunutau` | 10 |
| `usenue` | 10 |
| `usenumu` | 10 |
| `usenutau` | 10 |
| `usmunue` | 10 |
| `usmunumu` | 10 |
| `usmunutau` | 10 |
| `ustaunue` | 10 |
| `ustaunumu` | 10 |
| `ustaunutau` | 10 |

<!-- END: auto-generated -->

## Installation

```bash
pip install rgevolve.wet_4.flavio
```

To install the core package together with all available EFT/basis
companion packages at once, use the meta-package:

```bash
pip install rgevolve
```

## License

`rgevolve.wet_4.flavio` is licensed under the MIT License — see [`LICENSE`](LICENSE).
