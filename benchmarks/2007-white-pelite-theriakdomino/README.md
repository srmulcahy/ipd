# White et al., 2007 - Partial metling of metapelites

White, R. W., R. Powell, and T. J. B. Holland, 2007, Progress relating to calculation of partial melting equilibria for metapelites, Journal of metamorphic Geology, v. 25, p. 511-527, https://doi.org/10.1111/j.1525-1314.2007.00711.x.

## Calculations

- Thermodynamic database tcds55_p07.txt
- Calculated from TC 630-1000 and P (kb) 0.5 to 12
- Solution models: ternary feldspar (Holland and Powell, 2003); garnet, biotite, liquid (White et al., 2007); staurolite, cordierite, chlorite, and chloritoid (Holland and Powell, 1998), orthopyroxene, spinel, ilmenite (White et al., 2002); muscovite (Coggan and Holland, 2002)
- Conisder ST and ru, not considered by White et al., 2007

## Bulk Compositions

Bulk rock compositions in mol% from White et al., 2007 and for use in Perple_X.

|Fig. | H2O | SiO2 | Al2O3 | CaO | MgO | FeO | K2O | Na2O | TiO2 | O |
|:----|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Fig. 4 | 6.56 | 68.76 | 9.87 | – | 4.01 | 7.64 | 3.16| – | – | – |
|Fig. 6 | 6.66 | 70.09 | 8.95 | 0.24 | 3.64 | 6.93 | 2.87 | 0.57 | – | – |
|Fig. 7 | 6.66 | 70.09 | 8.95 |0.28 | 3.64 | 6.93 | 2.87 | 0.57 | – | – |

Bulk rock compostions converted to Theriak-Domino input format.

|Fig. | H2O | SiO2 | Al2O3 | CaO | MgO | FeO | K2O | Na2O | TiO2 | O |
|:----|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Fig. 4 | 10.791 | 57.495 | 16.508 | – | 3.354 | 6.388 | 5.285| – | – | – |
|Fig. 6 | 11.190| 58.877 | 15.038 | 0.235 | 3.058| 5.822 | 4.822 | 0.958 | – | – |
|Fig. 7 | 11.143 | 58.370 | 14.909 |0.235 | 3.034 | 5.941 | 4.773 | 0.941 | 0.535 | 0.168 |


## Notes

- All runs successfully reproduce White et al., figures. Above the solids differences exist for fields that include rutile and below the solidus for fields that include staurolite (not considered by White et al).

### Fig. 7

- Added more water to the Theriak-Domino bulk composition (11.143) from what was caclulated using the White et al bulk composition (11.093) because TD returned a Segment error just beyond the solidus, suggesting the bulk composition as caclulated was not water saturated at the solidus.
- Small fields in Fig. 7b of White et al not present on diagram.