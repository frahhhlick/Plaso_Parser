# Logstash Plaso Parser
This is a Logstash Ingestion Parser for Plaso timeline files, designed to parse the CSV into additional useful fields. Registry Keys, users, event codes, file paths, executables and more are parsed into individual fields that can be searched via Kibana. '

# How-To
The script takes a variable for "TIMELINE_PATH", telling it where to look for the CSV files. There are two methods to set this variable:
1. export TIMELINE_PATH=<path> on the Host System
2. Add the variable to a Logstash .env file

# Improvement Requests
Please send improvement requests and issues to scarl33t.forensics@gmail.com

# Plaso Github Repo: https://github.com/log2timeline/plaso
