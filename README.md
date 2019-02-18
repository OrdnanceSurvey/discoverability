# discoverability
Initially the home for 'code' related to the Geo6 Data Discoverability Project

In particular, the column definitions for the partners' catalogue (CSV) files.

Note: following the Brownfield Site Register pattern, the CSV schema uses the definitions at https://csvlint.io/ which was developed by ODI.  This is turn uses the frictionless Json Table Schema ( https://frictionlessdata.io/specs/table-schema/ ). This is distinct from the W3C's CSV on the web (https://www.w3.org/TR/tabular-data-primer/#column-info) - but has precedent at data.gov.uk.

Turns out this is due to CSVLint predating W3C even starting their work. Apparently, CSVLint does support the CSV on the Web schema files, but I'm told the error reporting isn't as clear as when using their 'native' schema files.

To do in JSON file:
- change GC_Theme column name to Geospatial_Commission_Theme
- 
