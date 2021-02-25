# Web-LogPoison
Python script to help automate performing log file poisoning from various sources (web, ssh, mail logs, etc.)

# How to Use
Once you are able to view logs from the LFI vulnearbility, simply copy the URL (do not include http(s)://) into the tool as the parameter and logpoisoner will attempt to poison the log file for code execution.


# Sample
When you start the script, it is expecting the full URL 
![Starting the Script](intro.png)


# Poison the Log File
Once you have the URL, simply paste it in and logpoisoner will attemp to poison the log file
![Poisoning](example.png)

# RCE with LogPoisoner
![RCE](RCE.png)
