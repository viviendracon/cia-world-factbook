# cia-world-factbook
JSON country profiles from the CIA World Factbook
* Last export Apr 25, 2022

## dist 
Includes:
1. Countries
2. Dependencies 
3. Export report

### Country files 
- Named with country's ISO-3 codes
- https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3
- e.g. USA.json is the profile file for the United States of America


### Dependencies files 
- Named with dependency's FIPS 2-digit code
- https://en.wikipedia.org/wiki/List_of_FIPS_country_codes
- e.g. IP.json is the profile file for Clipperton Island

### Export report
- Successes show countries and dependencies successfully exported
- Errors represent entities without downloadable JSON files

## cia_fips_to_iso.json
- Lists all countries and dependencies
- Contains country name, FIPS code, ISO code mapping and relevant notes


