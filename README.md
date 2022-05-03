# cia-world-factbook
JSON country profiles plus media from the CIA World Factbook
* https://www.cia.gov/the-world-factbook/countries/
* Last export May 3rd, 2022

## dist 
Includes:
1. Countries
2. Dependencies 
3. Media
4. Export report

### Country files 
- Named with country's ISO-3 codes
- https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3
- e.g. USA.json is the profile file for the United States of America


### Dependencies files 
- Named with dependency's FIPS 2-digit code
- https://en.wikipedia.org/wiki/List_of_FIPS_country_codes
- e.g. IP.json is the profile file for Clipperton Island

### Media files
- Each directory contains the media associated with the country or dependency
- XXX.json or XX.json contains the metadata for all files
- 1 page PDF country summary plus photos, mp3s, and maps

### Export report
- Successes show countries and dependencies successfully exported
- Errors represent entities without downloadable JSON files

## cia_fips_to_iso.json
- Lists all countries and dependencies
- Contains country name, FIPS code, ISO code mapping and relevant notes


