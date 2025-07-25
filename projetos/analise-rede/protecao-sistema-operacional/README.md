readme_content = """
# 🛡️ Proteção do Sistema Operacional - Análise de Incidente

Este relatório documenta um incidente de segurança envolvendo o site `yummyrecipesforme.com`, comprometido após um ataque de força bruta. A atividade faz parte do curso de Certificação em Segurança Cibernética (Google).

## 📄 Cenário

Um ex-funcionário utilizou credenciais padrão para acessar o painel administrativo do site, injetou um script JavaScript malicioso e redirecionou visitantes para um site falso contendo malware (`greatrecipesforme.com`).

## 🔍 Análise

[Modelos para Análise](/modelo_dados/)

**Protocolos envolvidos:**

- DNS: resolução dos domínios `yummyrecipesforme.com` e `greatrecipesforme.com`.
- HTTP: carregamento das páginas e do conteúdo malicioso.
- TCP: transporte das comunicações web.

**Etapas observadas:**

1. Acesso ao site legítimo.
2. Download forçado de arquivo executável.
3. Execução do malware e redirecionamento para o site falso.

## 🧾 Documentação

- Análise feita com tcpdump em ambiente sandbox.
- Redirecionamento identificado via inspeção de tráfego DNS e HTTP.
- Código malicioso localizado no HTML da página.
- Arquivo malicioso analisado e confirmado como vetor de redirecionamento.

## 🔐 Medida recomendada

**Implementar autenticação de dois fatores (2FA)** para contas administrativas, junto com:

- Políticas de senha forte
- Limite de tentativas de login
- Monitoramento de acessos
- Remoção de contas inativas

## 📄 Arquivo do Relatório

- [Relatorio Completo](/Relatorio_Protecao_Sistema_Operacional_Completo.docx)

---

**Este projeto faz parte do meu portfólio de estudos em Segurança Cibernética, baseado no curso de Certificação Profissional do Google.**

---
