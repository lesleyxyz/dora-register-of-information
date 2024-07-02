# Unprotected Register of Information (DORA)
The official password-protected excel file can be found [here](https://www.eba.europa.eu/activities/direct-supervision-and-oversight/digital-operational-resilience-act/preparation-dora-application)

Unfortunately there is little flexibility possible to experiment with e.g. formula's, so I decided to make it easy for you and remove password protection :)

## How to
1) First convert the .xlsb file to .xlsx using Excel
2) Second rename the .xlsx file to .zip
4) In `xl\workbook.xml`, remove the `<workbookProtection ... />` tag
5) In all `xl\worksheets\sheet*xml` files, remove the `<sheetProtection ... />` tag
6) Rename the .zip back to .xlsx
7) Profit :)

## Contact
me@lesley.eu
