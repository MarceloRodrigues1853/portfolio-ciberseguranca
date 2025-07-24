# 🛡️ Análise de Ataque DoS - SYN Flood

Este projeto apresenta a investigação de um incidente de segurança ocorrido em um servidor web que foi alvo de um ataque de negação de serviço (DoS) do tipo **SYN Flood**.

## 🎯 Cenário

Um cliente relatou falhas no acesso ao site da empresa, e foi identificada uma lentidão excessiva e erros de "tempo limite de conexão". A equipe de segurança capturou os pacotes com um sniffer de rede e analisou o tráfego.

## Modelo de Dados
[modelo_daos](/projetos/analise-rede/analise-syn-flood/modelo_dados/)

## 🔎 Resultado da Análise

- O servidor web recebeu uma quantidade anormal de pacotes TCP SYN vindos de um único endereço IP.
- O ataque simulava o início de conexões TCP sem completá-las.
- Isso esgotou os recursos do servidor, impedindo novas conexões legítimas.
- Logs revelaram mensagens de erro como `504 Gateway Timeout` e `RST, ACK`.

## 🚨 Tipo de Ataque Identificado

**SYN Flood (Denial of Service - DoS)**  
Um ataque em que o invasor envia um grande volume de pacotes SYN para esgotar os recursos do servidor, impedindo o estabelecimento de conexões reais.

## 💥 Impacto

- O site ficou inacessível para funcionários e visitantes legítimos.
- A performance do servidor foi comprometida.
- Houve perda de disponibilidade e confiança no serviço.

## 🔐 Ações Corretivas Tomadas

- O servidor foi temporariamente tirado do ar para recuperação.
- Foi aplicado bloqueio de IP no firewall.
- Recomendou-se configurar mecanismos de mitigação mais robustos como:
  - **SYN cookies**
  - **Limitação de taxa de conexões**
  - **Soluções de proteção DDoS**

## 📄 Arquivo do Relatório

- `Relatorio_Incidente_DoS_SynFlood_PTBR.docx`

---

**Este projeto faz parte do meu portfólio de estudos em Segurança Cibernética, baseado no curso de Certificação Profissional do Google.**

