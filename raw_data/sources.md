#   Raw Data Sources

##  ffi_data.json

### Source: Freedom For Immigrants (formerly CIVIC)

[https://www.freedomforimmigrants.org/map](https://www.freedomforimmigrants.org/map)

### Methodology

*   Examined Network tab in browser inspector at above URL for GeoJSON file loading
*   Obtained url: https://b.freedomforimmigrants.org/mdb/ws-proxy.php?orig_path=public/geojson/facilities&active=true&g287=true
*   Above URL can be manipulated to pull more data, for example set "&active=false" for a .json file of inactive facilities.

### Processing

*   Imported downloaded file as .json into VSCode, formatted using Intellisense (Shift+Alt+F)

### Notes

*   Excellent resource, foundation for this project.
*   Provides comprehensive information about legislative agreements (Section 287(g)), mailing addresses, facility-specific policies.

## ICE_Facility_List_11-06-2017-web.xlsx

### Source: National Immigrant Justice Center

https://immigrantjustice.org/ice-detention-facilities-november-2017


### Methodology

*   Simple download

### Processing
None

### Notes

Useful to validate information. Contains inspection records accurate to 2017.

Excellent explanations of abbreviations to be used elsewhere when compiling a codebook.

##  FY##-detentionstats.xlsx

### Source: ICE Detention Management
https://www.ice.gov/detain/detention-management

### Methodology

*   Simple download

### Processing

*   Renaming FY22 file to remove camelcase.

### Notes
*   While worksheets inside file may have similar names, formatting varies, so not useful for programmatic parsing.

##  FY23-detentionstats08032023.xlsx

### Source: ICE Detention Management

https://www.ice.gov/detain/detention-management

### Methodology

*   Simple download

### Processing

*   Rename file

### Notes

* YTD information, retrieved Aug 4th, 2023.

#   TODO:

*   Pull Global Detention Project dataset
