# Uganda Elections Related Open Data Resources 

This is a collection of data resources for Uganda Elections 

1. 2016 Elections Polling Station Data
   - [Excel](voter_register_summary_2016.xls)
   - [CSV](voter_register_summary_2016.csv)
   - [JSON](voter_register_summary_2016.json)

2. 2020 Elections Polling Station Data 
   - [Excel](voter_register_summary_2020.xls)
   - [CSV](voter_register_summary_2020.csv)
   - [JSON](voter_register_summary_2020.json)

NOTES:
========
1. The CSV file is used as the primary source of data with the JSON format being generated using the following commands 
- `csvjson --snifflimit 0 voter_register_summary_2016.csv >  voter_register_summary_2016.json`
- ` csvjson --snifflimit 0 voter_register_summary_2020.csv >  voter_register_summary_2020.json`
2. The Excel is generated by opening the CSV and saving as Microsoft Excel 94-2004 Workbook (.xls)