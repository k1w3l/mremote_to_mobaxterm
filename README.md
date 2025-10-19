# mremote_to_mobaxterm

Script para converter conexões Mremote para conexões MobaXterm.

🚀 Como usar

Copie o Connections.xml do mRemoteNG pra mesma pasta do script.

Execute no terminal (ou PowerShell):

python mremote_to_mobaxterm.py

######################################################################

Será criada a pasta:

./moba_sessions/

com vários arquivos .mxtsessions (um por conexão).

Copie tudo para:

C:\Users\<seu_usuário>\Documents\MobaXterm\slash\home\.moba\Sessions\

#######################################################################


Abra o MobaXterm → as sessões aparecerão automaticamente no painel esquerdo.

⚠️ Observações

Senhas não são migradas (Moba usa criptografia própria).

Nomes com caracteres especiais são “limpos” para evitar erros.

Suporta SSH, RDP e Telnet.

Compatível com Windows, Linux e macOS.
