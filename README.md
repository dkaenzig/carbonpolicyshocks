
# Carbon Policy Shocks

This repository hosts the carbon policy surprises and estimated carbon policy shocks from:

Känzig, Diego R. (2026).  
*The Unequal Consequences of Carbon Pricing.*  
Conditionally accepted at American Economic Review.  
Ungated version: https://dkaenzig.github.io/diegokaenzig.com/Papers/kaenzig_jmp_unequal_consequences_carbon_pricing.pdf

## Data

The surprises and shocks are stored in the file  

[carbonPolicyShocks.xlsx](carbonPolicyShocks.xlsx)

The file contains the following sheets:

#### Daily

| Variable | Description |
|----------|-------------|
| Surprise | Daily carbon policy surprises measured as the euro change in the carbon price relative to the prevailing wholesale electricity price, purged of macroeconomic, financial, and oil market news. |

#### Monthly

| Variable | Description |
|----------|-------------|
| Surprise | Monthly carbon policy surprises obtained by summing daily surprises within each month. |
| Shock | Carbon policy shock identified using an external instruments VAR, where the surprise series serves as an instrument for the energy price residual. |

#### Notes

Carbon policy shocks based on an earlier version of the paper (April 2023) are available in the [legacy](legacy) folder.

#### VAR Dataset

The repository also includes the dataset used in the **baseline VAR** specification:

[dataCPS.xlsx](dataCPS.xlsx)

This file contains data on the HICP energy, GHG emissions, HICP headline, industrial production, the two-year rate, the unemployment rate, the EUROSTOXX50 and the Brent crude price. For more details, see Appendix A.2.


## License

The data are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt the data provided appropriate credit is given. If you use these data, please cite the following paper:

Känzig, Diego R. (2026).  
*The Unequal Consequences of Carbon Pricing.*  
[NBER WP 31221](https://www.nber.org/papers/w31221)

```bibtex
@techreport{kanzig2023unequal,
  title       = {The Unequal Economic Consequences of Carbon Pricing},
  author      = {K{\"a}nzig, Diego R.},
  institution = {National Bureau of Economic Research},
  type        = {NBER Working Paper},
  number      = {31221},
  year        = {2026},
  url         = {https://www.nber.org/papers/w31221}
}
```

## Contact

If you have any questions, please contact me at [dkaenzig@northwestern.edu](mailto:dkaenzig@northwestern.edu).

