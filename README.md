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
