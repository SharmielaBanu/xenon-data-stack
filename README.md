# xenon-data-stack
######collecting system metrics######
#post configuration of elasticsearch, topbeat to tranfer required data to elasticsearch (topbeat.yml configuration file) and kibana connected to elasticsearch index
#run elastic.bat
#run localhost:5601 in your browser
#index will be loaded in kibana
#from windows powershell run topbeat
PS C:\Program Files\Topbeat> PowerShell.exe -ExecutionPolicy UnRestricted -File ./install-service-topbeat.ps1
#data can be visualised in kibana
#logfiles can be viewed in topbeat Logs folder
