# Carbon policy shocks
Repository hosing the carbon policy surprises and estimated carbon policy shocks from Känzig (2025).

The surprises and shocks are stored in the [carbonPolicyShocks.xlsx](carbonPolicyShocks.xlsx) file. The file contains the following sheets:

## Daily

| Variable | Description |
|----------|-------------|
| Surprise | Daily carbon policy surprises measured as euro change in carbon price, relative to prevailing wholesale electricity price, purged from macro, financial, and oil market news. |

## Monthly

| Variable | Description |
|----------|-------------|
| Surprise | Monthly carbon policy surprises, aggregated by summing over daily surprises. |
| Shock    | Carbon policy shock, identified using the external instruments VAR using the surprise series as an instrument for the energy price residual. |

## Notes

The original carbon policy shocks based on the previous version of the paper (April, 2023) can be found in the [legacy](legacy) folder.

If you have any questions, please contact me at [dkaenzig@northwestern.edu](mailto:dkaenzig@northwestern.edu).

