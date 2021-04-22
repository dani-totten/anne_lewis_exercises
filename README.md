# Documentation
The purpose of this script is to aggregate data from 3 tables into a single summary table
The table pulls directly from the AWS buckets - these lines of code need to be kept up to date. Additionally, there working directory can be set/changed as a string variable at the beginning of the document. Code is commented throughout to explain what is being done.

# email communication
Hello client contact,

I've created a python script to aggregate data from the constituent information, constituent email addresses and constituent subscription status tables to create a table that summarizes key information about your constituents. This newly created table (people.csv) contains summary information about your constituents including their email, the source, whether they have unsubscribed, when their file was created and when the file was last updated. I linked together the original data tables using constituent IDS and constituent emails. If these columns are not reliable, please let me know because they are a key part of linking together the information from the three different tables. The purpose of this table is to have a single look-up for email addresses and general information about your constituent contacts.

This script also creates a second table (acquisition_table.csv) that describes how many new constituent contacts were acquired each day. This information is useful for viewing the trend of acquisitions over time and can help pinpoint acquisition spikes.

Please reach out if you have any questions or issues,
Dani
