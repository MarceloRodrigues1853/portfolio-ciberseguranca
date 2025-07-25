# 🛡️ Análise de Relatório de Incidente - Aplicação do NIST CSF

Este repositório contém uma análise de incidente de segurança cibernética utilizando a estrutura NIST Cybersecurity Framework (CSF). O relatório simula um vazamento de dados causado por phishing, seguido de acesso não autorizado e manipulação de registros em um banco de dados de clientes.

## 📌 Resumo do Incidente

Nesta manhã, uma estagiária relatou ao time de TI que não conseguia acessar sua conta na rede interna. No entanto, os logs mostravam que sua conta estava ativa e acessando o banco de dados de clientes.

Após investigação, descobriu-se que a estagiária havia recebido um e-mail de phishing solicitando suas credenciais. Isso possibilitou que um invasor acessasse o sistema, alterasse e excluísse dados. Também foi detectado vazamento de informações sensíveis.

---

## 🧩 Análise com base no NIST CSF

### 🔍 1. Identificar

- Auditoria realizada em sistemas e dispositivos
- Credenciais da estagiária foram capturadas e usadas por um invasor
- Dados foram acessados, alterados e possivelmente excluídos

### 🛡️ 2. Proteger

Ações implementadas:

- Autenticação multifator (MFA)
- Limite de 3 tentativas de login
- Treinamento obrigatório sobre segurança de credenciais
- Nova configuração de firewall
- Investimento em sistema de prevenção de intrusos (IPS)

### 🔎 3. Detectar

Ferramentas utilizadas:

- Registro de logs do firewall
- IDS (sistema de detecção de intrusos) para monitoramento do tráfego de entrada

### 🧯 4. Responder

- Desativação da conta da estagiária
- Treinamento imediato com toda a equipe
- Comunicação com clientes e autoridades sobre o incidente

### 🔄 5. Recuperar

- Restauração do backup da noite anterior
- Orientação para que colaboradores reintroduzam dados modificados pela manhã

---

## 📚 Reflexões

Este incidente reforça a importância de políticas de segurança fortes, treinamento contínuo sobre phishing e a necessidade de múltiplas camadas de proteção para fortalecer a segurança da organização.

---

## 🗂️ Estrutura dos Arquivos

📁 relatorio-incidente-nist/
├── 📁 modelo-dados/
├── Relatorio_Incidente_NIST_PTBR.docx
└── README.md

## 📚 Referências

- NIST Cybersecurity Framework: [https://www.nist.gov/cyberframework](https://www.nist.gov/cyberframework)
- Curso de Certificação em Segurança Cibernética - Google (Coursera)

---

> ⚠️ Este material é de caráter educacional e faz parte do portfólio de estudos em segurança cibernética.
