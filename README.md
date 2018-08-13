### NetBackup API Code Samples

Contains code samples to invoke NetBackup REST API using different programming languages.

#### Disclaimer
These scripts are only meant to be used as a reference. Please do not use these in production.

#### Executing the snippets in PowerShell
Pre-requisites:
- NetBackup 8.1.1 or higher
- Powershell 5.0 or higher

Use the following commands to run the powershell samples.
- `.\Get-NB-Images.ps1 -nbmaster <masterServer> -username <username> -password <password>`
- `.\Get-NB-Jobs.ps1 -nbmaster <masterServer> -username <username> -password <password>`
- `.\Get-NB-Alerts.ps1 -nbmaster <masterServer> -username <username> -password <password>`

#### Executing the snippets in Python
Pre-requisites:
- NetBackup 8.1.1 or higher
- python 3.5 or higher
- python modules: `requests, texttable`

Use the following commands to run the python samples.
- `python -W ignore get_nb_images.py -nbmaster <masterServer> -username <username> -password <password>`
- `python -W ignore get_nb_jobs.py -nbmaster <masterServer> -username <username> -password <password>`
- `python -W ignore get_nb_alerts.py -nbmaster <masterServer> -username <username> -password <password>`

#### Executing the snippets in Perl
Pre-requisites:
- NetBackup 8.1.1 or higher
- See script README for perl requirements and usage

#### Executing the snippets using curl
Pre-requisites:
- NetBackup 8.1.1 or higher
- curl 7.51.0 or higher
- jq command-line parser (https://github.com/stedolan/jq/releases)

Use the following commands to run the curl samples.
- `./get_nb_jobs.sh -master <master_server> -username <username> -password <password>`
- `./get_nb_images.sh -master <master_server> -username <username> -password <password>`

#### Tools
The `tools` folder contains utilities that have proven useful in the development of projects using
NetBackup REST APIs, but do not provide any API usage examples.  Again, these tools are not for
production use, but they may be of some use in your work.
