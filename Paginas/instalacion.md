# ***Instalación de Chocolatey***
Para instalar Chocolatey, abra PowerShell desde el menú Inicio. A continuación, copie y pegue la siguiente línea de script y presione enter:

>> Set-ExecutionPolicy Bypass -Scope Process -Force;
iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
