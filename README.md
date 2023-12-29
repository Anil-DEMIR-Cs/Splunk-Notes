# Splunk-Notes


General Information About Splunk

Splunk has 4 segments

1) Input
2) Parsing
3) Indexing
4) Search

1- Input: Splunk accepts many source of data. e.g:
 - File monitor inputs
 - Winevent monitor inputs
 - TCP / UDP inputs
 - HEC inputs
 - Scripted inputs

File Monitor Inputs: It will monitor particular file. Once new lines are written down to this file, it will start reading and forward it further.

Winevent Monitor Inputs: Windows event monitor inputs. It will monitoring Windows events.

TCP/UDP Inputs: If any data seen over TCP and UDP it will listen, read, and forward it further.

HEC Inputs: HTTP Event Collector, which lists on HTTP responses and then forward it further.

Scripted Inputs: It will execute particular script whatever will be the result of it, it will send it further.

2- Parsing: Splunk Software breaks the data stream into individual events.

*** There are event genarator tools outthere for practising splunk

*** We can use Splunk with other tools
- For Web Traffic we can use ZSCALER
- For Firewall we can use PALOALTO NETWORKS
- For Device Monitoring we can use CROWDSTRIKE
- For User Activity we can use SPLUNK
