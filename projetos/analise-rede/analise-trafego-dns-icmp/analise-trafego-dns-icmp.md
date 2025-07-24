# Análise de Tráfego DNS e ICMP – Relatório de Incidente

Este projeto simula a investigação de um incidente de segurança envolvendo falha no acesso ao site `www.yummyrecipesforme.com`. A análise foi feita com base em registros coletados pela ferramenta `tcpdump`.

## 🧠 Objetivo
Demonstrar a capacidade de analisar registros de tráfego de rede, identificar protocolos envolvidos, interpretar mensagens de erro e propor ações corretivas – habilidades fundamentais para analistas de segurança cibernética.

## 🔍 Cenário

- Vários usuários relatam falha ao acessar o site `www.yummyrecipesforme.com`.
- Mensagem de erro recebida: `Destination port unreachable`.
- Foi utilizado `tcpdump` para capturar o tráfego de rede durante a tentativa de acesso.

## 🖼 Imagem do modelo de dados
![Modelo de Dados](/projetos/analise-rede/modelo_analise.png)

## 📈 Resultados da Análise

- O navegador tentou resolver o domínio usando DNS via UDP/53.
- O servidor DNS (`203.0.113.2`) respondeu com mensagens ICMP indicando que a **porta UDP 53 estava inacessível**.
- O erro se repetiu em todas as tentativas.

## ⚠️ Conclusão

O serviço DNS no host de destino estava inacessível, impedindo a resolução do nome do domínio e, por consequência, o acesso ao site. Isso pode ter sido causado por:

- Serviço DNS desligado ou inoperante
- Firewall/ACL bloqueando a porta 53
- Problemas de roteamento ou mitigação DDoS mal configurada

## ✅ Ações Recomendadas

- Verificar se o serviço DNS está em execução
- Checar regras de firewall e roteamento
- Habilitar fallback DNS por TCP
- Configurar monitoramento e redundância

## 📄 Relatório

O relatório completo da análise está disponível em:

- [Relatório Completo](`/projetos/analise-rede/Relatorio_Incidente_Seguranca_PTBR.docxrelatorio-analise-incidente-dns.docx`)

---

**Este projeto faz parte do portfólio de certificação em Segurança Cibernética do Google.**