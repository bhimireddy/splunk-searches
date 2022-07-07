# splunk-searches
most handy Splunk searches
To check what indexes you have access to
|tstats count by index sourcetype where index=*
OR use stats which is expensive than | tstats
index=* | stats count by index
