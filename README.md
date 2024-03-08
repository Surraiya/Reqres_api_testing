# Reqres_api_testing
GENERATE TEST RUN REPORT USING NEWMAN.
Process of Test Run Report creation:
Newman is used to generate test run reports. Newman htmlextra
reporter is used here.
1. Go to JSON file directory.
2. In CMD run command (newman run &quot;path/to/your-collection.json&quot; -r
htmlextra --reporter-htmlextra-title &quot;Title Name of the Report&quot;)
3. This will generate the report in the same directory under newman
folder.
