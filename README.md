# Haensel-AMS-Data-Quality-challenge 

The objective of this task was to check data quality and answer the following questions:

- 	Are the costs in the 'api_adwords_costs' table fully covered in the 'session_sources' table? Any campaigns where you see issues?
- 	Are the conversions in the 'conversions' table stable over time? Any pattern?
- 	Double check conversions ('conversions' table) with backend ('conversions_backend' table), any issues?
- 	Are attribution results consistent? Do you find any conversions where the 'ihc' values don't make sense?
- 	Do we have an issue with channeling? Are the number of sessions per channel stable over time?
-   Any other issues?

All the answers of above questions can be found in "HAEMS_challenge.ipynb"

Overall, after exploring the database, I could say that there are inconsistencies in data collection from third party-sources and specially on particular time periods. Additionally, the session data has many different names for one particular channel.
