# Criar o conteúdo do README.md em português
readme_content = """\
# Hardening de Rede

Este projeto faz parte do portfólio de Segurança Cibernética e apresenta uma análise prática sobre **Hardening de Rede** realizada durante o curso de certificação.

## 📌 Cenário

Uma organização de mídia social sofreu uma violação de dados significativa, expondo informações pessoais de usuários. A causa foram vulnerabilidades críticas como:

- Compartilhamento de senhas entre funcionários.
- Uso de senha padrão para administrador do banco de dados.
- Falta de regras de filtragem em firewalls.
- Ausência de autenticação multifator (MFA).

## 🔧 Ferramentas e métodos de proteção aplicados

1. **Autenticação multifator (MFA)**  
   Impede acesso com apenas senha. Exige verificação adicional como token, app autenticador ou biometria.

2. **Política de senhas fortes**  
   Criação de senhas com complexidade mínima e regras de troca e bloqueio após tentativas falhas.

3. **Atualização das regras de firewall**  
   Controle rigoroso do tráfego de entrada e saída, impedindo acessos indevidos.

## ✅ Resultados e Recomendações

Essas práticas ajudam a prevenir ataques de força bruta, engenharia social e invasões por vulnerabilidades conhecidas. A recomendação é revisar essas políticas quinzenalmente ou após qualquer incidente.

## 📁 Arquivos

- `Relatorio_Hardening_de_Rede_PTBR.docx` – Documento completo com análise e recomendações.
"""

# Salvar o README.md
readme_path = "/mnt/data/README_hardening_de_rede.md"
with open(readme_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

readme_path
