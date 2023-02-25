Bom Vamos Começar colocando o Choco no seu Computador
<br>
Abra seu cmd com:
<br>
<strong>
<em>
- Windows + R
</em>
</strong>

coloque cmd e com o atalho Ctrl + Shirt + Enter, já executando o cmd no modo de administrador.
<br>
Logo em seguida coloque no seu cmd:
- ```@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"```

Instalado o Choco, vamos instalar o Chocolatey
<br>
no cmd coloque:
<br>
``` choco install chocolatey ```
<br>
- `` " Caso não instale reinici o computador e tente novamente. " ``

Depois da instalação do Chocolatey, vamos instalar o Dart
<br>
no cmd coloque:
<br>
``` choco install dart-sdk ```
<br>
- `` " Caso não instale reinici o computador e tente novamente. " ``

Instalado o Dart e o Chocolatey na sua máquina, vamos instalar o dart no VSCode.
<br>
No menu extenções instale o Dart no seu VSCode.
<br>
Depois da instalação do Dart, Abra um arquivo novo chamado " HelloWord.dart " 
<br> 
Depois coloque esse código no arquivo:
<br>
- ```void main(){```
   <br>```print("Hello Word")```
<br>```}```

Caso não apareça " Hello Word " reinstale o Dart e o Chocolatey