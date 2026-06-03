# CanonicalAffiliations
This repository contains the current set of institutional identifiers used by SciX and ADS to map institutional affiliations in their search engine.

08 May 2026

These are files used by the ADS Abstract Service (ui.adsabs.harvard.edu)
to normalize institutional affiliations.  The following files are included:

- parent_child.tsv, a tab separated file containing:
  - `parent id`, `child id`, `abbreviated affiliation`, `canonical affiliation`

- country_parent_child.tsv, a tab separated file containing:
  - `ISO Country Code`, `country`, `parent id`, `child id`, `abbreviated affiliation`, `canonical affiliation`

- historically_black_colleges_universities.tsv, a tab separated file containing:
  - `child id`, `canonical affiliation`
  - Includes all federally-recognized US HBCUs as of September 15, 2025

- tribal_colleges_universities.tsv, a tab separated file containing:
  - `child id`, `canonical affiliation`
  - Includes only tribally-controlled institutions
  - Does not include public universities in the US with significant Native American/First Nations enrollment

- ROR_ADS.tsv, a tab separated file containing:
  - `ROR`, `ads_id` where ads_id might be a parent/child combination 

- README.md (this file) 

- Usage.txt (usage examples in the ADS)
 
If you want to discuss additional applications or see more of this work, please
get in touch.

Carolyn Stern Grant
NASA Astrophysics Data System
Harvard-Smithsonian Center for Astrophysics
cgrant@cfa.harvard.edu

