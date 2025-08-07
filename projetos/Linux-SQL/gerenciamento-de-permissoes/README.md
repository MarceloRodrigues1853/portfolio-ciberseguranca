# Gerenciamento de Permissões no Linux

Este diretório demonstra a utilização de comandos Linux para **verificar e alterar permissões de arquivos e diretórios**, como parte do meu portfólio de segurança cibernética.

## 🧠 Objetivo

Aplicar conhecimentos práticos de gerenciamento de permissões com o comando `chmod`, identificar permissões inadequadas e corrigi-las de acordo com um cenário realista.

---

## 📁 Estrutura do Projeto

O diretório `/home/researcher2/projects` contém os seguintes arquivos:

- `project_k.txt`
- `project_m.txt`
- `project_r.txt`
- `project_t.txt`
- `.project_x.txt` (arquivo oculto)
- Diretório: `drafts`

---

## 🔍 Verificação Inicial das Permissões

Para listar os arquivos, inclusive ocultos, usei o comando:

```bash
ls -la
```

📸 Saída do comando:
![exemplo2](/gerenciamento-de-permissoes/img/exemplo2.PNG)

### 🔐 Ajuste de Permissões dos Arquivos

📄 1. Remoção da permissão de escrita para "outros" no `project_k.txt`:

```bash
chmod o-w project_k.txt
```

📄 2. Remoção da permissão de leitura para "grupo" no `project_m.txt`:

```bash
chmod g-r project_m.txt
```

📸 Resultado após ajustes:
![exemplo3](/gerenciamento-de-permissoes/img/exemplo3.PNG)

🕵️‍♂️ Ajuste de Permissões em Arquivo Oculto
O arquivo `.project_x.txt` estava com permissões indevidas. Corrigido com:

```bash
chmod u-w,g-w,o-r .project_x.txt

chmod g+r .project_x.txt
```

📸 Antes e depois do ajuste:
![exemplo4](/gerenciamento-de-permissoes/img/exemplo4.PNG)

📁 Ajuste de Permissões em Diretório
Somente o usuário `researcher2` deve ter acesso ao diretório `drafts`.

```bash
chmod g+x drafts
Comando utilizado:

chmod g-x drafts
```

📸 Resultado:
![exemplo5](/gerenciamento-de-permissoes/img/exemplo5.PNG)

✅ Verificação Final
Após todos os ajustes, o diretório foi novamente inspecionado:

```bash
ls -la
```

📸 Permissões finais aplicadas:
![exemplo5](/gerenciamento-de-permissoes/img/exemplo5.PNG)

---

### 🧾 Conclusão

Este exercício demonstrou a habilidade de:

**Inspecionar** e **ajustar** permissões com `ls -la`

**Interpretar** a `string` de permissões de `10 caracteres`

**Utilizar** o comando `chmod` para ajustes em arquivos **visíveis, ocultos e diretórios**

**Garantir** que o `acesso` aos `recursos` esteja em **conformidade** com as **regras da organização**

Essas práticas reforçam a **importância do controle de acesso** no contexto da **cibersegurança**.

---
