# CCE Functionality Dashboard

## Project overview
This separate Power BI dashboard view focuses on cold-chain equipment functionality and related inventory indicators, including equipped sites, functionality rate, usable-capacity cards, and equipment age-band analysis.

## Analytical questions
- What proportion of assessed sites are equipped?
- How is functionality rate defined and calculated?
- How do equipment age bands relate to recorded functionality status?
- Are capacity indicators populated and calculated consistently?

## Tools
- Microsoft Power BI
- Microsoft Excel

## Dashboard features observed in the supplied screenshot
- Equipped Sites KPI
- Functionality Rate KPI
- Usable Capacity indicators
- Supply-chain-level, state, and functionality-status filters
- Equipment age-band visual
- State-level table

## Initial screenshot observations
The supplied screenshot displays:
- Equipped sites: **1,810**
- Assessed sites: **1,815**
- Functionality rate: **0.00%**
- Installed capacity label: **492,367 L** (as displayed; verify the exact unit and measure)
- A separate headline count of **2,836** is visible; its measure and filter context need confirmation.

These are preliminary screenshot transcriptions. They are not final findings until report filters, model definitions, and measures have been checked.

## Validation priorities
1. Confirm active page and visual-level filters.
2. Inspect the DAX measure used by the Functionality Rate card.
3. Confirm numerator, denominator, and treatment of blank statuses.
4. Verify the capacity measure and exact unit.
5. Record the reporting period and refresh date.
6. Check that cards and visuals respond to intended filters.

## Findings
**Pending validation.** Do not interpret a displayed 0.00% rate as a true programme result until the calculation and filter context are verified.

## Potential operational uses
Once measures are validated, this view may help users identify records requiring status verification, review equipment-age patterns, and monitor capacity indicators.

## Limitations and data protection
This documentation is based on a screenshot only. The original PBIX and source data are not included. Do not publish confidential facility-level data, source datasets, or restricted government information without explicit authorisation.
