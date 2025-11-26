# Conheça o Python Situação:



## Como funciona a programação

**A programação** é um processamento que pode ser usado para criar um conjunto específico de instruções para um computador executar tarefas. Existem programas de computadores em toda parte. Computadores, telefones celulares e muitos outros dispositivos eletrônicos recebem instruções de programas de computador. 

Há várias linguagens de programação usadas para criar programas de computador. Python é uma delas. As linguagens de programação são convertidas em números binários, que são uma série de 0s e 1s que representam as operações que a unidade central de processamento (CPU) do computador deve executar. Cada instrução corresponde a uma operação específica, como somar dois números ou carregar um valor da memória.

Seria muito demorado para os seres humanos se comunicarem dessa forma. Linguagens de programação como Python facilitam a escrita de códigos porque você pode usar menos Sintaxe ao instruir os computadores a realizar processos complexos.

## Como usar o Python para programar

Python é uma linguagem de programação de uso geral que pode ser usada para resolver uma variedade de problemas. Por exemplo, ela pode ser usada para criar sites, realizar Análise de dados e automatizar tarefas.

O código Python deve ser convertido por meio de um interpretador antes que o computador possa processá-lo. Um **interpretador** é um programa de computador que traduz o código Python em instruções executáveis, linha por linha. 

### **Versões do Python**

Existem várias versões do Python. Neste curso, você está usando o Python 3. Ao usar o Python, é importante manter o controle da versão que está usando. Há diferenças na sintaxe de cada versão. **Sintaxe** refere-se às regras que determinam o que é estruturado corretamente em uma linguagem de computador.

## Python na segurança cibernética

Na segurança cibernética, o Python é usado especialmente para automação. **Automação** é o uso da tecnologia para reduzir o esforço humano e manual na execução de tarefas comuns e repetitivas. Estas são algumas áreas específicas da segurança cibernética nas quais o Python pode ser usado para automatizar tarefas específicas:

- Análise de registros
- Análise de malware
- Gerenciamento de listas de controle de acesso
- Detecção de intrusão
- Verificações de conformidade
- Varredura de rede de computadores

## Principais lições

Python é uma linguagem de programação ou, em outras palavras, uma linguagem usada para criar instruções para um computador concluir tarefas. As linguagens de programação são convertidas em números binários que uma máquina pode entender. É importante estar ciente de que há várias versões do Python e que elas têm diferenças de sintaxe. O Python é especialmente útil na segurança cibernética para automatizar tarefas repetitivas.



# Ambientes Python Situação:



Você pode executar o Python em uma variedade de ambientes. Esses ambientes incluem notebooks, ambientes de desenvolvimento integrado (IDEs) e a linha de comando. Esta leitura apresentará a você esses ambientes. Ela se concentrará principalmente nos notebooks, pois é assim que você interagirá com o Python neste curso.

## Notebooks

Uma maneira de escrever códigos Python é por meio de um notebook. Neste curso, você interagirá com o Python por meio de notebooks. Um **notebook** é uma interface on-line para escrever, armazenar e executar códigos. Ele também permite que você documente informações sobre o código. O conteúdo do Notebook aparece em uma célula de código ou em uma célula de markdown.

### **Células de código**

As células de código destinam-se a escrever e executar código. Um Notebook fornece um mecanismo para executar essas células de código. Geralmente, esse mecanismo é um botão de reprodução localizado dentro da célula. Quando você executa o código, sua saída aparece após o código.

### **Células Markdown**

As células Markdown destinam-se a descrever o código. Elas permitem que você formate o texto na linguagem markdown. A linguagem markdown é usada para formatar texto simples em editores de texto e editores de código. Por exemplo, você pode indicar que o texto deve estar em um determinado estilo de Cabeçalho.

### **Ambientes de notebook comuns**

Dois ambientes comuns de notebook são o [Notebook Jupyter](https://jupyter.org/about) e o [Google Colaboratory](https://colab.sandbox.google.com/) (ou Google Colab). Eles permitem que você execute várias linguagens de programação, inclusive Python.

## Ambientes de desenvolvimento integrado (IDEs)

Outra opção para escrever código Python é por meio de um **ambiente de desenvolvimento integrado (IDE),** ou um software de aplicativo para escrever código que fornece assistência à edição e ferramentas de correção de erros. Os ambientes de desenvolvimento integrado (IDE) incluem uma interface gráfica de usuário (GUI) que oferece aos programadores uma Variedade de opções para personalizar e criar seus programas.

## Linha de comando

A linha de comando é outro ambiente que permite a execução de programas Python. Anteriormente, você aprendeu que uma **interface de linha de comando (CLI)** é uma interface de usuário baseada em texto que usa comandos para interagir com o computador. Ao digitar comandos na linha de comando, você pode acessar todos os arquivos e diretórios salvos no disco rígido, inclusive os arquivos que contêm o código Python que deseja executar. Também é possível usar a linha de comando para abrir um editor de arquivos e criar um novo arquivo Python.

## Principais conclusões

Os analistas de segurança podem acessar o Python por meio de uma variedade de ambientes, incluindo notebooks, ambientes de desenvolvimento integrado (IDE) e a linha de comando. Neste curso, você usará notebooks, que são interfaces on-line para interação com o código. Os notebooks contêm células de código para escrever e executar código, bem como células de markdown para descrições de texto simples.



# Mais informações sobre tipos de dados Situação:



Anteriormente, você explorou os tipos de dados em Python. Um **tipo de dados** é uma categoria para um tipo específico de item de dados. Você se concentrou em dados do tipo string, lista, float, inteiro e booleano. Esses são os tipos de dados com os quais você trabalhará neste curso. Esta leitura ampliará esses tipos de dados. Ela também apresentará três tipos adicionais.

## String

Em Python, **os dados de string** são dados que consistem em uma sequência ordenada de caracteres. Os caracteres em uma String podem incluir letras, números, símbolos e espaços. Esses caracteres devem ser colocados entre aspas. Todas essas são strings válidas:

- `"updates needed"`
- `"20%"`
- `"5.0"`
- `"35"`
- `"**/ **/**"` 
- `""`

**Observação:** O último item (`""`), que não contém nada entre as aspas, é chamado de string vazia.

Você pode usar a função `print()` para exibir uma string. Você pode explorar isso executando este código:

````python
print("updates needed")
````



O código imprime `"updates needed"`. 

Você pode colocar Strings entre aspas duplas (`""`) ou aspas simples (`''`). O código a seguir demonstra que a mesma mensagem é impressa quando a cadeia de caracteres está entre aspas simples:

````py
print("updates needed")
````



**Observação:** Escolher um tipo de aspas e usá-lo de forma consistente facilita a leitura de seu código. Este curso usa aspas duplas.

## Lista

Em Python, **a lista de dados** é uma estrutura de dados que consiste em uma coleção de dados em formato sequencial. Os elementos de listas podem ser de qualquer tipo de dados, como strings, inteiros, booleanos ou até mesmo outras listas. Os elementos de uma lista são colocados entre colchetes, e cada elemento é separado por uma vírgula. As listas a seguir contêm elementos de vários tipos de dados:

- `[12, 36, 54, 1, 7]`
- `["eraab", "arusso", "drosas"]`
- `[True, False, True, True]`
- `[15, "approved", True, 45.5, False]`
- `[]`

**Observação:** O último item[], que não contém nada dentro dos colchetes, é chamado de lista vazia.

Você também pode usar a função print() para exibir uma lista:

````py
print([12, 36, 54, 1, 7])
````



Isso exibe uma lista que contém os inteiros 12, 36, 54, 1, e 7.

### **Inteiro**

Em Python, **os dados inte** iros são dados que consistem em um número que não inclui um ponto decimal. Todos esses são exemplos de dados inteiros:

- `-100` 
- `-12`
- `-1`
- `0`
- `1`
- `20`
- `500` 

Os números inteiros não são colocados entre aspas. Você pode usar a função `print()` para exibir um número inteiro. Quando você executa esse código, ele exibe 5:

````py
print(5)
````



Você também pode usar a função `print()` para realizar operações matemáticas com números inteiros. Por exemplo, este código adiciona dois números inteiros:

````py
print(5 + 2)
````



O resultado é `7`. Você também pode subtrair, multiplicar ou dividir dois números inteiros.

## Flutuante

**Dados float** são dados que consistem em um número com um ponto decimal. Todos os itens a seguir são exemplos de dados float:

- `-2.2`
- `-1.34`
- `0.0`
- `0.34`

Assim como os dados inteiros, os dados flutuantes não são colocados entre aspas. Além disso, você também pode usar a função print() para exibir dados flutuantes ou para realizar cálculos matemáticos com dados flutuantes. Você pode executar o código a seguir para analisar o resultado desse cálculo:

````py
print(1.2 + 2.8)
````



A saída é `4.0`.

**Observação:** Dividir dois valores inteiros ou dois valores flutuantes resulta em saída flutuante quando você usa o símbolo `/`:

````py
print(1/4)
print(1.0/4.0)
````



A saída de ambos os cálculos é o valor float de `0.25`.

Se você quiser retornar um número inteiro de um cálculo, deverá usar o símbolo `//`:

````py
print(1//4)
print(1.0//4.0)
````



Ele arredondará para o número inteiro mais próximo. No caso de `print(1//4)`, a saída é o valor inteiro de 0 porque o uso desse símbolo arredonda o cálculo de `.25` para o número inteiro mais próximo. No caso de `print(1.0//4.0)`, a saída é o valor float de `0.0` porque ele mantém o Tipo de dados float dos Valores no cálculo e também arredonda para o número inteiro mais próximo.

## Booleano

Dados booleanos são dados que só podem ter um de dois valores: `True` ou `False`.

Não se deve colocar os valores booleanos entre aspas. Quando você executa o código a seguir, ele exibe o valor booleano de `True`:

````py
print(True)
````



Você também pode retornar um valor booleano comparando números. Como 9 não é maior que 10, esse código é avaliado como `False`:

````py
print(9 > 10)
````



## Tipos de dados adicionais

Neste curso, você trabalhará com os tipos de dados string, lista, inteiro, float e booleano, mas há outros tipos de dados. Esses tipos de dados adicionais incluem dados de tupla, dados de dicionário e dados de conjunto.

### **Tupla**

**Os dados de tupla** são uma estrutura de dados que consiste em uma coleção de dados que não podem ser alterados. Como as listas, as tuplas podem conter elementos de vários tipos de dados. 

Uma diferença entre dados de tupla e dados de lista é que é possível alterar os elementos em uma lista, mas não é possível alterar os elementos em uma tupla. Isso pode ser útil em um contexto de segurança cibernética. Por exemplo, se os identificadores de software forem armazenados em uma tupla para garantir que não serão alterados, isso pode garantir que uma lista de controle de acesso bloqueará apenas o software pretendido.

A sintaxe de uma tupla também é diferente da sintaxe de uma lista. Uma tupla é colocada entre parênteses em vez de colchetes. Todos esses são exemplos do tipo de dados tupla:

- `("wjaffrey", "arutley", "dkot")`
- `(46, 2, 13, 2, 8, 0, 0)`
- `(True, False, True, True)`
- `("wjaffrey", 13, True)`

**Dica profissional:** As tuplas são mais eficientes em termos de memória do que as listas, portanto, são úteis quando se trabalha com uma grande quantidade de dados.

### **Dicionário**

**Os dados de dicionário** são dados que consistem em um ou mais Pares chave-valor. Cada chave é mapeada para um valor. Dois pontos (`:`) são colocados entre a chave e o valor. As vírgulas separam os pares chave-valor de outros pares chave-valor, e o dicionário é colocado entre colchetes (`{}`).

Os dicionários são úteis quando você deseja armazenar e recuperar dados de forma previsível. Por exemplo, o dicionário a seguir mapeia o nome de um edifício para um número. O nome do edifício é o VALUE e o número é a chave. Dois pontos são colocados após a chave.

````py
{ 1: "East",

 2: "West",

 3: "North",

 4: "South" }
````



### **Conjunto**

Em Python, **Conjunto de dados** são dados que consistem em uma coleção não ordenada de Valores únicos. Isso significa que dois valores em um conjunto não podem ser iguais.

Os elementos em um conjunto são sempre colocados entre colchetes e separados por vírgula. Esses elementos podem ser de qualquer tipo de dados. Este exemplo de conjunto contém strings de nomes de usuário:

`{"jlanksy", "drosas", "nmason"}`

## Principais conclusões

É importante que os analistas de segurança que programam em Python estejam familiarizados com vários tipos de dados Python. Os tipos de dados com os quais você trabalhará neste curso são string, lista, inteiro, Flutuante e Booleano. Os tipos de dados adicionais incluem tupla, dicionário e conjunto de dados. Cada tipo de dado tem sua própria finalidade e sua própria Sintaxe.



# Atribuir e reatribuir variáveis em Python Situação:



Anteriormente, você explorou as variáveis e como atribuí-las e reatribuí-las em Python. Nesta leitura, você ampliará sua compreensão sobre esses tópicos. Você também aprenderá sobre a prática geral de nomear variáveis para evitar erros de sintaxe e melhorar a legibilidade do código.

## O que são variáveis?

Em uma linguagem de programação, uma **variável** é um contêiner que armazena dados. É um local de armazenamento nomeado na memória de um computador que pode conter um valor. Ela armazena os dados em um tipo de dados específico, como inteiro, string ou booleano. O valor armazenado em uma variável pode mudar.

Você pode pensar nas variáveis como caixas com rótulos. Mesmo quando você altera o conteúdo de uma caixa, o rótulo da caixa permanece o mesmo. Da mesma forma, quando você altera o valor armazenado em uma variável, o nome da variável permanece o mesmo.

Os analistas de segurança que trabalham em Python usarão uma variedade de variáveis. Alguns exemplos incluem variáveis para tentativas de login, listas de permissões e endereços.

## Trabalho com variáveis

Em Python, é importante saber como atribuir variáveis e como reatribuí-las.

### **Atribuição e reatribuição de variáveis**

Se você quiser criar uma variável chamada username e atribuir a ela o valor "nzhao", coloque a variável à esquerda do sinal de igual e seu valor à direita:

`# Assign 'username'`

`username = "nzhao"`

Se mais tarde você redefinir esse nome de usuário para "zhao2", ainda se referirá a esse contêiner de variável como `username`.

`# Reassign 'username'`

`username = "zhao2"`

Embora o conteúdo tenha mudado de `"nzhao"` para `"zhao2"`, a variável `username` permanece a mesma. 

**Observação:** você deve colocar `"nzhao"` e `"zhao2"` entre aspas porque são strings. O Python atribui automaticamente um tipo de dados a uma variável quando ela é executada. Por exemplo, quando a variável `username` contém a string `"nzhao"`, é atribuído a ela um tipo de dados string.

### **Atribuição de variáveis a variáveis**

Usando um processo semelhante, você também pode atribuir variáveis a outras variáveis. No exemplo a seguir, a variável `username` é atribuída a uma nova variável `old_username`:

`# Assign a variable to another variable`

`username = "nzhao"`

`old_username = username`

Como `username` contém o valor de cadeia de caracteres de `"nzhao"` e `old_username` contém o valor de `username`, `old_username` agora contém um valor de `"nzhao"`.

### **Juntando tudo**

O código a seguir demonstra como um nome de usuário pode ser atualizado. A variável `username` recebe um valor inicial, que é então armazenado em uma segunda variável chamada `old_username`. Depois disso, a variável `username` é reatribuída a um novo valor. Você pode executar esse código para obter uma mensagem sobre o nome de usuário anterior e o nome de usuário atual:

````py
username = "nzhao"
old_username = username
username = "zhao2"
print("Previous username:", old_username)
print("Current username:", username)
````



## Práticas recomendadas para nomear variáveis

Você pode nomear uma variável quase como quiser, mas há algumas diretrizes que devem ser seguidas para garantir a sintaxe correta e evitar erros:

- Use somente letras, números e sublinhados nos nomes das variáveis. Exemplos válidos: `date_3, username, interval2`
- Lembre-se de que os nomes de variáveis em Python diferenciam maiúsculas de minúsculas. Todas essas variáveis são diferentes: `time, Time, TIME, timE`.
- Não use as palavras-chave ou funções incorporadas do Python para nomes de variáveis. Por exemplo, as variáveis não devem ser nomeadas como `True, False`, ou `if`.

Além disso, você deve seguir estas diretrizes estilísticas para facilitar a leitura e a compreensão do seu código por você e por outros analistas de segurança:

- Separe duas ou mais palavras com sublinhados. Exemplos válidos: `login_attempts*,* invalid_user,status_update`
- Evite variáveis com nomes semelhantes. Essas variáveis podem ser facilmente confundidas umas com as outras: `start_time, starting_time, time_starting`.
- Evite nomes desnecessariamente longos para as variáveis. Por exemplo, não dê às variáveis nomes como `variable_that_equals_3`.
- Os nomes devem descrever os dados e não ser palavras aleatórias. Exemplos válidos: `num_login_attempts, device_id, invalid_usernames`

**Observação**: Recomenda-se usar sublinhados para separar várias palavras em variáveis, mas outra convenção que você pode encontrar é colocar a primeira letra de cada palavra em maiúscula, exceto a primeira palavra. Exemplo: `loginAttempt`

## Principais conclusões

É importante que os analistas de segurança tenham uma compreensão fundamental das variáveis. As variáveis são contêineres de dados. São atribuídos a elas valores e também podem ser reatribuídos a outros valores ou variáveis. É útil lembrar as práticas recomendadas para nomear variáveis a fim de criar um código mais funcional e legível.



# Mais sobre condicionais em Python Situação:



Anteriormente, você explorou as instruções condicionais e como elas são úteis na automatização de tarefas em Python. Até agora, você se concentrou nas palavras-chave if e else. Nesta leitura, você as revisará e aprenderá outra palavra-chave, elif. Você também aprenderá como aplicar os operadores and, or e not às suas condições.

## Como funcionam as declarações condicionais

Uma **instrução condicional** é uma instrução que avalia o código para determinar se ele atende a um conjunto específico de condições. Quando uma condição é atendida, ela é avaliada como um valor booleano de True e executa as ações especificadas. Quando a condição não é atendida, ela avalia um valor booleano de False e não executa as ações especificadas. 

Nas instruções condicionais, a condição geralmente se baseia em uma comparação de dois valores. Esta tabela resume os operadores de comparação comuns usados para comparar valores numéricos.

| **operador** | **uso**              |
| :----------- | :------------------- |
| >            | maior que            |
| <            | menor que            |
| >=           | maior ou igual a     |
| <=           | menor que ou igual a |
| ==           | igual a              |
| !=           | diferente de         |

**Observação:** os operadores igual a (==) e não igual a (!=) também são comumente usados para comparar dados internos.

## declarações if

A palavra-chave if inicia uma instrução condicional. É um componente necessário de qualquer instrução condicional. No exemplo a seguir, if inicia uma instrução que diz ao Python para imprimir uma mensagem "OK" quando o código de status de resposta HTTP for igual a 200:

if status == 200:

  print("OK")

Esse código consiste em um Cabeçalho e um Corpo.

### **Cabeçalho de uma instrução if**

A primeira linha desse código é o cabeçalho. No cabeçalho de uma instrução if, a Palavra-chave if é Seguida pela condição. Aqui, a condição é que a variável status seja igual a um valor de 200. A condição pode ser colocada entre parênteses:

if (status == 200):

  print("OK")

Em casos como este, colocar parênteses em torno das condições em Python é opcional. Talvez você queira incluí-los se isso ajudar na legibilidade do código. No entanto, essa condição será processada da mesma forma se for escrita sem parênteses.

Em outras situações, como o Python avalia as condições entre parênteses primeiro, os parênteses podem afetar a forma como o Python processa as condições. Você lerá mais sobre uma dessas situações na seção desta leitura em not.

**Observação:** Você deve sempre colocar dois pontos (:) no final do cabeçalho. Sem essa sintaxe, o código produzirá um erro.

**O corpo de uma instrução if**

Após o Cabeçalho de uma instrução if, vem o corpo da instrução if. Isso informa ao Python qual ação ou ações devem ser executadas quando a condição for avaliada como True. Neste exemplo, há apenas uma ação, imprimir "OK" na tela. Em outros casos, pode haver mais linhas de código com ações adicionais.

**Observação:** Para que o corpo da instrução if seja executado como pretendido, ele deve ser recuado mais do que o Cabeçalho. Além disso, se houver várias linhas de código dentro do corpo, todas elas deverão ser recuadas de forma consistente.

## Continuação de condicionais com else e elif

No exemplo anterior, se o código de status HTTP da resposta não fosse igual a 200, a condição seria avaliada como False e o Python continuaria com o restante da programação. No entanto, também é possível especificar ações alternativas com else e elif.

### **instruções else**

A Palavra-chave else precede uma seção de código que só é avaliada quando todas as condições que a precedem dentro da Instrução condicional são avaliadas como False.

No exemplo a seguir, quando o código de status de resposta HTTP não é igual a 200, ele imprime uma mensagem alternativa de "check other status":

if status == 200:

  print("OK")

else:

  print("check other status")

**Observação:** Assim como em if, , são necessários dois pontos (:) após else, e o corpo que segue o Cabeçalho else é recuado.

### **declarações elif**

Em alguns casos, você pode ter várias ações alternativas que dependem de novas condições. Nesse caso, você pode usar elif. A Palavra-chave elif precede uma condição que só é avaliada quando as condições anteriores são avaliadas como False. Diferentemente do que ocorre com else, pode haver várias instruções elif seguindo if.

Por exemplo, talvez você queira imprimir uma mensagem se o código de status de resposta HTTP for 200, uma mensagem se for 400 e outra se for 500. O código a seguir demonstra como você pode usar elif para isso:

if status == 200:

  print("OK")

elif status == 400:

  print("Bad Request")

elif status == 500:

  print("Internal Server Error") 

O Python verificará primeiro se o valor de status é 200 e, se for avaliado como False, ele passará para a primeira instrução elif. Lá, ele verificará se o valor de status é 400. Se for avaliado como True, ele imprimirá "Bad Request", mas se for avaliado como False, ele passará para a próxima instrução elif.

Se você quiser que o Código imprima outra mensagem quando todas as condições forem avaliadas como False, poderá incorporar else após o último elif. Neste exemplo, se chegar à instrução else, ele imprimirá uma mensagem para verificar o status:

if status == 200:

  print("OK")

elif status == 400:

  print("Bad Request")

elif status == 500:

  print("Internal Server Error")

else:

  print("check other status")

Assim como em if e else, é importante colocar dois pontos (:) após o cabeçalho elif e recuar o código que segue esse cabeçalho.

**Observação:** o Python processa várias instruções elif de forma diferente de várias instruções if. Quando ele chega a uma instrução elif que é avaliada como True, ele não verifica as instruções elif seguintes. Por outro lado, o Python executará todas as instruções if.

## Operadores lógicos para várias condições

Em alguns casos, talvez você queira que o Python execute uma ação com base em uma condição mais complexa. Talvez você precise que duas condições sejam avaliadas como True. Ou, você pode exigir que apenas uma das duas condições seja avaliada como True. Ou talvez você queira que o Python execute uma ação quando uma condição for avaliada como False. Os operadores and, or e not podem ser usados nesses casos.

### **e**

O operador and exige que ambas as condições em ambos os lados do operador sejam avaliadas como True. Por exemplo, todos os códigos de resposta de status HTTP entre 200 e 226 estão relacionados a respostas bem-sucedidas. Você pode usar and para unir uma condição de ser maior ou igual a 200 com outra condição de ser menor ou igual a 226:

`if status >= 200 and status <= 226:`

   `print("successful response")`

Quando ambas as condições forem True, a mensagem "successful response" será impressa.

### **ou**

O operador or exige que apenas uma das condições de cada lado do operador seja avaliada como True. Por exemplo, tanto um código de status 100 quanto um código de status 102 são respostas informativas. Usando or, você pode pedir ao Python para imprimir uma mensagem "informational response" quando o código for 100 ou 102:

`if status == 100 or status == 102:`

   `print("informational response")`

Apenas uma dessas condições precisa ser atendida para que o Python imprima a mensagem.

### **não**

O operador **not** nega uma determinada condição de modo que ela seja avaliada como False se a condição for **True** e como True se for False. Por exemplo, se você quiser indicar que o Python deve verificar o código de status quando ele estiver fora da programação bem-sucedida, poderá usar not:

`if not(status >= 200 and status <= 226):`

   `print("check status")`

Python primeiro verifica se o valor de status é maior ou igual a 200 e menor ou igual a 226 e, em seguida, por causa do operador not, ele inverte isso. Isso significa que ele imprimirá a mensagem se status for menor que 200 ou maior que 226.

**Observação:** nesse caso, os parênteses são necessários para que o código aplique not a ambas as condições. O Python avaliará primeiro as condições dentro dos parênteses. Isso significa que ele avaliará primeiro as condições em cada lado do operador and e, em seguida, aplicará not a ambas.

## Principais conclusões

É importante que os analistas de segurança estejam familiarizados com as instruções condicionais. As instruções condicionais requerem a palavra-chave if. Você também pode usar else e elif ao trabalhar com condicionais para especificar ações adicionais a serem tomadas. Os Operadores lógicos and, or e not também são úteis ao escrever condicionais.





# Mais sobre loops em Python Situação: 



Anteriormente, você explorou as instruções iterativas. Uma **instrução iterativa** é um código que executa repetidamente um conjunto de instruções. Dependências dos critérios, as instruções iterativas são executadas zero ou mais vezes. Fizemos a iteração do código usando os loops for e while. Nesta leitura, você recapitulará a sintaxe dos loops. Em seguida, aprenderá a usar as palavras-chave break e continue para controlar a execução dos loops.

## loops for 

Se precisar fazer a iteração em uma sequência especificada, use um loop for.

O seguinte loop for faz a iteração de uma sequência de nomes de usuário. Você pode executá-lo para observar o resultado:

````py
for i in ["elarson", "bmoreno", "tshah", "sgilmore"]:
    print(i)
````

```
elarson
bmoreno
tshah
sgilmore
```



A primeira linha desse código é o cabeçalho do loop. No cabeçalho do loop, a palavra-chave for sinaliza o início de um loop for. Logo após for, aparece a variável de loop . A **variável de loop** é uma variável usada para controlar as iterações de um loop. Nos loops for, a variável de loop faz parte do Cabeçalho. Neste exemplo, a variável de loop é i.

O restante do cabeçalho do loop indica a sequência a ser iterada. O operador in aparece antes da sequência para dizer ao Python para executar o loop para cada item da sequência. Neste exemplo, a sequência é a lista de nomes de usuário. O Cabeçalho do loop deve terminar com dois pontos (:).

A segunda linha do exemplo do loop for é o corpo do loop. O corpo do loop for pode consistir em várias linhas de código. No corpo, você indica o que o loop deve fazer em cada iteração. Nesse caso, é para print(i), ou, em outras palavras, para exibir o valor atual da variável do loop durante essa iteração do loop. Para que o Python execute o código corretamente, o corpo do loop deve ser recuado mais do que o Cabeçalho do loop. 

**Observação:** Quando usado em um loop for, o Operador in precede a sequência pela qual o loop for fará a iteração. Quando usado em uma Instrução condicional, o operador in é usado para avaliar se um Objeto faz parte de uma sequência. O exemplo if "elarson" in ["tshah", "bmoreno", "elarson"] é avaliado como True porque "elarson" faz parte da sequência que segue in.

## **Loop em uma lista**

O uso de loops for no Python permite a iteração fácil em listas, como uma lista de recursos de computador. No loop for a seguir, asset é a variável de loop e outra variável, computer_assets, é a sequência. A variável computer_assets armazena uma lista. Isso significa que, na primeira iteração, o valor de asset será o primeiro elemento dessa lista e, na segunda iteração, o valor de asset será o segundo elemento dessa lista. Você pode executar o código para observar o que ele produz:

````py
computer_assets = ["laptop1", "desktop20", "smartphone03"]
for asset in computer_assets:
    print(asset)
````

```
laptop1
desktop20
smartphone03
```



**Observação:** Também é possível fazer um loop em uma string. Isso retornará cada caractere, um por um. Você pode observar isso executando o seguinte bloco de código que faz uma iteração na string "security":

````py
string = "security"
for character in string:
    print(character)
````

```
s
e
c
u
r
i
t
y
```



### **Usando Intervalo()**

Outra maneira de iterar em um loop for é com base em uma sequência de números, o que pode ser feito com range(). A função range() gera uma sequência de números. Ela aceita entradas para o ponto de início, o ponto de parada e o incremento entre parênteses. Por exemplo, o código a seguir indica o início da sequência de números em 0, a parada em 5 e o incremento a cada vez em 1:

range(0, 5, 1)

**Observação:** O ponto de início é inclusivo, o que significa que 0 será incluído na sequência de números, mas o ponto de parada é exclusivo, o que significa que 5 será excluído da sequência. Ela será concluída um número inteiro antes do ponto de parada.

Ao executar esse código, você pode observar como 5 é excluído da sequência:

````py
for i in range(0, 5, 1):
    print(i)
````

```
0
1
2
3
4
```



Você deve estar ciente de que é sempre necessário incluir o ponto de parada, mas se o ponto de início for o valor padrão de 0 e o incremental for o valor padrão de 1, eles não precisarão ser especificados no Código. Se você executar esse código, obterá os mesmos resultados:

````python
for i in range(5):
    print(i)
````

```
0
1
2
3
4
```



**Observação:** Se o ponto de início for qualquer coisa diferente de 0 ou o incremento for qualquer coisa diferente de 1, eles deverão ser especificados.

## loops while

Se quiser que um loop faça a iteração com base em uma condição, use um loop while. Enquanto a condição for True, o loop continua, mas quando a avaliação for False, o loop while é encerrado. O loop while a seguir continua enquanto a condição i < 5 for True:

````py
i = 1
while i < 5:
    print(i)
    i = i + 1
````

```
1
2
3
4
```



Nesse loop while, o Cabeçalho do loop é a linha while i < 5:. Diferentemente dos loops for, o valor de uma variável de loop usada para controlar as iterações não é atribuído dentro do cabeçalho do loop em um loop while. Em vez disso, ele é atribuído fora do loop. Neste exemplo, i é atribuído a um valor inicial de 1 em uma linha que precede o loop.

A palavra-chave while sinaliza o início de um loop while. Depois disso, o Cabeçalho do loop indica a condição que determina quando o loop termina. Essa condição usa os mesmos operadores de comparação das instruções condicionais. Como em um loop for, o Cabeçalho de um loop while deve terminar com dois pontos (:).

O corpo de um loop while indica as ações a serem executadas em cada iteração. Neste exemplo, é para exibir o valor de i e Incrementalizar o valor de i por 1. Para que o valor de i mude a cada iteração, é necessário indicar isso no corpo do loop while. Neste exemplo, o loop itera quatro vezes até atingir o valor de 5.

### Inteiros na condição do loop

Muitas vezes, como acabamos de demonstrar, a condição do loop é baseada em valores inteiros. Por exemplo, talvez você queira permitir que um usuário faça o registro desde que ele tenha se registrado menos de cinco vezes. Então, sua variável de loop, login_attempts, pode ser inicializada como 0, incrementada por 1 no loop, e a condição de loop pode especificar a iteração somente quando a variável for menor que 5. Você pode executar o código abaixo e analisar a contagem de cada tentativa de login:

````py
login_attempts = 0
while login_attempts < 5:
    print("Login attempts:", login_attempts)
    login_attempts = login_attempts + 1
````

```
Login attempts: 0
Login attempts: 1
Login attempts: 2
Login attempts: 3
Login attempts: 4
```



O valor de login_attempts foi de 0 para 4 antes de a condição de loop ser avaliada em False. Portanto, os valores de 0 a 4 são impressos e o valor 5 não é impresso.

### Valores booleanos na condição de loop

As condições dos loops while também podem depender de outros tipos de dados, incluindo comparações de dados booleanos. Nas comparações de dados booleanos, a condição do loop pode verificar se uma variável do loop é igual a um valor como True ou False. O loop faz uma iteração de um número indeterminado de vezes até que a condição booleana não seja mais True.

No exemplo abaixo, um valor booleano é usado para sair de um loop quando um usuário tiver feito cinco tentativas de login. Uma variável chamada count controla cada tentativa de login e muda a variável login_status para False quando count for igual a 4. (O Incremental count de 0 a 4 representa cinco tentativas de login.) Como a condição while só é iterativa quando login_status é True, ela sairá do loop. Você pode executar isso para explorar essa saída:

````py
count = 0
login_status = True
while login_status == True:
    print("Try again.")
    count = count + 1
    if count == 4:
        login_status = False
````

```
Try again.
Try again.
Try again.
Try again.
```



O código imprime uma mensagem para tentar novamente quatro vezes, mas sai do loop quando login_status é definido como False.

## Gerenciamento de loops

É possível usar as palavras-chave break e continue para controlar ainda mais as iterações do loop. Ambas são incorporadas em uma Instrução condicional dentro do corpo do loop. Elas podem ser inseridas para execução quando a condição em uma instrução if for True. A palavra-chave break é usada para sair de um loop. A palavra-chave continue é usada para ignorar uma iteração e continuar com a próxima.

## **break**

Quando quiser sair de um loop for ou while com base em uma condição específica em uma instrução if que seja True, você pode escrever uma instrução condicional no corpo do loop e escrever a palavra-chave break no corpo da condicional.

O exemplo a seguir demonstra isso. A instrução condicional com break instrui o Python a sair do loop for se o valor da variável do loop asset for igual a "desktop20". Na segunda iteração, essa condição é avaliada como True. Você pode executar esse código para observar isso na saída:

````py
computer_assets = ["laptop1", "desktop20", "smartphone03"]
for asset in computer_assets:
    if asset == "desktop20":
        break
    print(asset)
````

```
laptop1
```



AS Como esperado, os valores de "desktop20" e "smartphone03" não são impressos porque o loop é interrompido na segunda iteração.

## **continuar**

Quando quiser pular uma iteração com base em uma determinada condição em uma instrução if sendo True, você pode adicionar a palavra-chave continue no corpo de uma instrução condicional dentro do loop. Neste exemplo, continue será executado quando a variável de loop asset for igual a "desktop20". Você pode executar esse código para observar como essa saída difere do exemplo anterior com break:



````py
computer_assets = ["laptop1", "desktop20", "smartphone03"]
for asset in computer_assets:
    if asset == "desktop20":
        continue
    print(asset)
````

laptop1 

smartphone03

O valor `"desktop20"` na segunda iteração não é impresso. No entanto, nesse caso, o loop continua na próxima iteração, e `"smartphone03"` é impresso.

## Loops infinitos

Se você criar um loop que não sai, isso é chamado de loop infinito. Nesses casos, você deve pressionar `CTRL-C ou CTRL-Z`  no teclado para interromper o loop infinito. Talvez seja necessário fazer isso ao executar um serviço que processa dados constantemente, como um servidor da Web.

## Principais lições

Os analistas de segurança precisam estar familiarizados com declarações iterativas. Eles podem usar os loops for para executar tarefas que envolvam a iteração de listas em um número predeterminado de vezes. Também podem usar os loops while para executar tarefas com base em determinadas condições avaliadas em True. As palavras-chave break e continue são usadas em instruções iterativas para controlar o fluxo dos loops com base em condições adicionais.



# Guia de referência: Conceitos Python do Módulo 1Situação: Traduzido automaticamente do InglêsTraduzido automaticamente do Inglês



Informações:

Este item inclui conteúdo que ainda não foi traduzido para o idioma de sua preferência.



Este guia de referência contém a linguagem Python introduzida durante o Módulo 1. O guia está organizado nas seguintes seções:

- Comentários
- Funções
- Instruções condicionais
- Declarações iterativas

Em cada seção, os itens geralmente aparecem na ordem em que foram introduzidos.

## Acessível e salve o guia

Você pode salvar uma cópia deste guia para referência futura. Pode usá-lo como um recurso para prática adicional ou em seus futuros projetos profissionais.

Para acessar uma versão para download deste item do curso, clique no link a seguir e selecione *Usar modelo*.

[Guia de referência: Conceitos de Python do Módulo 1](https://docs.google.com/document/d/1g01BIeiQtyFillHBNQMegGjbSzePkCj8nT-O4v1k8Gs/template/preview?usp=sharing&resourcekey=0-VdiTfxrHUssEh0I7P2z4LQ)

# Termos do glossário do Módulo 1 Situação: 



### **Termos e definições do Curso 7, Módulo 1**

**Automação:** O uso da tecnologia para reduzir o esforço humano e manual na execução de tarefas comuns e repetitivas

**Dados booleanos:** Dados que só podem ter um de dois valores: True ou False

**Interface de Linha de Comando (CLI):** Uma interface do usuário (IU) baseada em texto que usa comandos para interagir com o computador

**Comentário:** Uma nota que os programadores fazem sobre a intenção por trás de seu código

**Instrução condicional:** Uma instrução que avalia o código para determinar se ele atende a um conjunto especificado de condições

**Tipo de dados:** Uma categoria para um tipo específico de item de dados

**Dicionário de dados:** Dados que consistem em um ou mais pares chave-valor

**Dados Flutuantes:** Dados que consistem em um número com um ponto decimal

**Dados inteiros:** Dados que consistem em um número que não inclui um ponto decimal

**Ambiente de desenvolvimento integrado (IDE):** Um software de aplicativo para escrever códigos que fornece assistência à edição e ferramentas de correção de erros

**Interpretador:** Um programa de computador que traduz o código Python em instruções executáveis, linha por linha.

**Declaração iterativa:** Código que executa repetidamente um conjunto de instruções

**Dados de lista:** Estrutura de dados que consiste em uma coleção de dados em forma sequencial

**Loop variable (variável de loop):** Uma variável que é usada para controlar as iterações de um loop

**Notebook:** Uma interface on-line para escrever, armazenar e executar códigos

**Programação:** Um processamento que pode ser usado para criar um conjunto específico de instruções para um computador executar tarefas

**Conjunto de dados:** Dados que consistem em uma coleção não ordenada de Valores únicos

**Dados de String:** Dados que consistem em uma sequência ordenada de caracteres

**Sintaxe:** As regras que determinam o que é estruturado corretamente em uma linguagem de computador

**Dados de tupla:** Estrutura de dados que consiste em uma coleção de dados que não pode ser alterada.

**Erro de tipo:** Um erro resultante do uso do tipo de dados errado

**Variáveis:** Uma contenção que armazena dados



# Funções do Python na segurança cibernéticaSituação: Traduzido automaticamente do InglêsTraduzido automaticamente do Inglês

Anteriormente, você explorou como definir e chamar suas próprias funções. Nesta leitura, você revisitará o que aprendeu sobre funções e examinará como elas podem aumentar a eficiência em um ambiente de segurança cibernética.

## Funções na segurança cibernética

Uma **função** é uma seção de código que pode ser reutilizada em um programa. As funções são importantes no Python porque permitem automatizar partes repetitivas do seu código. Na segurança cibernética, você provavelmente adotará alguns processos que serão repetidos com frequência.

Ao trabalhar com logs de segurança, você frequentemente encontrará tarefas que precisam ser repetidas. Por exemplo, se você for responsável por encontrar atividades de login mal-intencionadas com base em tentativas de login fracassadas, talvez seja necessário repetir o processo para vários logs.

Para contornar isso, você poderia definir uma função que recebe um log como entrada e retorna todos os logins potencialmente mal-intencionados. Seria fácil aplicar essa função a diferentes logs.

## Definição de uma função

No Python, você trabalhará com funções incorporadas e funções definidas pelo usuário. **As funções incorporadas** são funções que existem no Python e podem ser chamadas diretamente. A função print() é um exemplo de função incorporada.

**As funções definidas pelo usuário** são funções que os programadores projetam para suas necessidades específicas. Para definir uma função, é necessário incluir um cabeçalho de função e o corpo da função.

### **Cabeçalho da função**

O cabeçalho da função é o que informa ao Python que você está começando a definir uma função. Por exemplo, se você quiser definir uma função que exiba uma mensagem "investigate activity", poderá incluir esse cabeçalho de função:

def display_investigation_message():

A palavra-chave def é colocada antes de um nome de função para definir uma função. Nesse caso, o nome da função é display_investigation_message.

Os parênteses que seguem o nome da função e os dois pontos (:) no final do cabeçalho da função também são partes essenciais da sintaxe.

**Dica profissional**: Ao nomear uma função, dê a ela um nome que indique o que ela faz. Assim, será mais fácil lembrar-se dela ao chamá-la mais tarde.

### **Corpo da função**

O corpo da função é um bloco de código recuado após o cabeçalho da função que define o que a função faz. A indentação é muito importante ao escrever uma função porque separa a definição de uma função do restante do código.

Para adicionar um corpo à sua definição da função display_investigation_message(), adicione uma linha recuada com a função print(). Sua definição de função passa a ser a seguinte:

def display_investigation_message():

  print("investigate activity")

## Chamada de uma função

Após definir uma função, você pode usá-la quantas vezes forem necessárias em seu código. O uso de uma função depois de defini-la é chamado de chamada de uma função. Para chamar uma função, escreva seu nome seguido de parênteses. Portanto, para a função que você definiu anteriormente, você pode usar o código a seguir para chamá-la:

display_investigation_message()

Embora as funções sejam usadas de maneiras mais complexas à medida que você expandir seu conhecimento, o código a seguir fornece uma introdução de como a função display_investigation_message() pode fazer parte de uma seção maior de código. Você pode executá-la e analisar sua saída:

1

2

3

4

5

6

7

8

9

10

11

12

Redefinir

```
application_log:
investigate activity
```



A função display_investigation_message() é usada duas vezes no código. Ela imprimirá mensagens "investigate activity" sobre dois logs diferentes quando as condições especificadas forem avaliadas como True. Neste exemplo, somente a primeira Instrução condicional é avaliada como True, portanto, a mensagem é impressa uma vez.

Esse código chama a função de dentro das condicionais, mas você pode chamar uma função de vários locais dentro do código.

**Observação:** A chamada de uma função dentro do corpo de sua definição de função pode criar um loop infinito. Isso acontece quando não é combinada com uma lógica que interrompe a chamada da função quando determinadas condições são atendidas. Por exemplo, na definição de função a seguir, depois que você chamar func1() pela primeira vez, ela continuará a chamar a si mesma e criará um loop infinito:



# Funções do Python na segurança cibernética Situação:

Anteriormente, você explorou como definir e chamar suas próprias funções. Nesta leitura, você revisitará o que aprendeu sobre funções e examinará como elas podem aumentar a eficiência em um ambiente de segurança cibernética.

## Funções na segurança cibernética

Uma **função** é uma seção de código que pode ser reutilizada em um programa. As funções são importantes no Python porque permitem automatizar partes repetitivas do seu código. Na segurança cibernética, você provavelmente adotará alguns processos que serão repetidos com frequência.

Ao trabalhar com logs de segurança, você frequentemente encontrará tarefas que precisam ser repetidas. Por exemplo, se você for responsável por encontrar atividades de login mal-intencionadas com base em tentativas de login fracassadas, talvez seja necessário repetir o processo para vários logs.

Para contornar isso, você poderia definir uma função que recebe um log como entrada e retorna todos os logins potencialmente mal-intencionados. Seria fácil aplicar essa função a diferentes logs.

## Definição de uma função

No Python, você trabalhará com funções incorporadas e funções definidas pelo usuário. **As funções incorporadas** são funções que existem no Python e podem ser chamadas diretamente. A função `print()` é um exemplo de função incorporada.

**As funções definidas pelo usuário** são funções que os programadores projetam para suas necessidades específicas. Para definir uma função, é necessário incluir um cabeçalho de função e o corpo da função.

### **Cabeçalho da função**

O cabeçalho da função é o que informa ao Python que você está começando a definir uma função. Por exemplo, se você quiser definir uma função que exiba uma mensagem `"investigate activity"`, poderá incluir esse cabeçalho de função:

`def display_investigation_message():`

A palavra-chave `def` é colocada antes de um nome de função para definir uma função. Nesse caso, o nome da função é `display_investigation_message`.

Os parênteses que seguem o nome da função e os dois pontos `(:)` no final do cabeçalho da função também são partes essenciais da sintaxe.

**Dica profissional**: Ao nomear uma função, dê a ela um nome que indique o que ela faz. Assim, será mais fácil lembrar-se dela ao chamá-la mais tarde.

### **Corpo da função**

O corpo da função é um bloco de código recuado após o cabeçalho da função que define o que a função faz. A indentação é muito importante ao escrever uma função porque separa a definição de uma função do restante do código.

Para adicionar um corpo à sua definição da função `display_investigation_message()`, adicione uma linha recuada com a função `print()`. Sua definição de função passa a ser a seguinte:

`def display_investigation_message():`

  `print("investigate activity")`

## Chamada de uma função

Após definir uma função, você pode usá-la quantas vezes forem necessárias em seu código. O uso de uma função depois de defini-la é chamado de chamada de uma função. Para chamar uma função, escreva seu nome seguido de parênteses. Portanto, para a função que você definiu anteriormente, você pode usar o código a seguir para chamá-la:

`display_investigation_message()`

Embora as funções sejam usadas de maneiras mais complexas à medida que você expandir seu conhecimento, o código a seguir fornece uma introdução de como a função `display_investigation_message()` pode fazer parte de uma seção maior de código. Você pode executá-la e analisar sua saída:

````py
def display_investigation_message():
    print("investigate activity")

application_status = "potential concern"
email_status = "okay"

if application_status == "potential concern":
    print("application_log:")
    display_investigation_message()

if email_status == "potential concern":
    print("email log:")
````

```
application_log:
investigate activity
```



A função `display_investigation_message()` é usada duas vezes no código. Ela imprimirá mensagens `"investigate activity"` sobre dois logs diferentes quando as condições especificadas forem avaliadas como `True`. Neste exemplo, somente a primeira Instrução condicional é avaliada como `True`, portanto, a mensagem é impressa uma vez.

Esse código chama a função de dentro das condicionais, mas você pode chamar uma função de vários locais dentro do código.

**Observação:** A chamada de uma função dentro do corpo de sua definição de função pode criar um loop infinito. Isso acontece quando não é combinada com uma lógica que interrompe a chamada da função quando determinadas condições são atendidas. Por exemplo, na definição de função a seguir, depois que você chamar `func1()` pela primeira vez, ela continuará a chamar a si mesma e criará um loop infinito:

`def func1():`

  `func1()`

## Principais conclusões

As funções do Python são importantes ao escrever código. Para definir suas próprias funções, você precisa dos dois componentes essenciais do cabeçalho da função e do corpo da função. Depois de definir uma função, você pode chamá-la quando necessário.



# Funções e variáveis

Anteriormente, você se concentrou em trabalhar com vários parâmetros e argumentos em funções e em retornar informações de funções. Nesta leitura, você revisará esses conceitos. Você também será apresentado a um novo conceito: variáveis globais e locais.

## Trabalho com variáveis em funções

Trabalhar com variáveis em funções requer um entendimento de parâmetros e argumentos. Os termos parâmetros e argumentos têm usos distintos quando se referem a variáveis em uma função. Além disso, se quiser que a função retorne o resultado, você deve estar familiarizado com as declarações de retorno.

### Parâmetros

Um **parâmetro** é um objeto incluído em uma definição de função para uso nessa função. Ao definir uma função, você cria variáveis no Cabeçalho da função. Elas podem então ser usadas no corpo da função. Nesse contexto, essas variáveis são chamadas de parâmetros. Por exemplo, considere a seguinte função:

`def remaining_login_attempts(maximum_attempts, total_attempts):`

  `print(maximum_attempts - total_attempts)`

Essa função recebe duas variáveis, `maximum_attempts` e `total_attempts`, e as utiliza para realizar um cálculo. Neste exemplo, `maximum_attempts` e `total_attempts` são parâmetros.

### Argumentos

Em Python, um **argumento** são os dados trazidos para uma função quando ela é chamada. Ao chamar `remaining_login_attempts` no exemplo a seguir, os inteiros 3 e 2 são considerados argumentos:

`remaining_login_attempts(3, 2)`

Esses inteiros passam para a função por meio dos parâmetros que foram identificados ao definir a função. Nesse caso, esses parâmetros seriam `maximum_attempts` e `total_attempts`. 3 está na primeira posição, portanto, passa para `maximum_attempts`. Da mesma forma, 2 está na segunda posição e passa para `total_attempts`.

### Declarações de retorno

Ao definir funções em Python, você usa instruções de retorno se quiser que a função retorne a saída. A palavra-chave return é usada para retornar informações de uma função.

A palavra-chave return aparece na frente das informações que você deseja retornar. No exemplo a seguir, ela aparece antes do cálculo do número de tentativas de login restantes:

`def remaining_login_attempts(maximum_attempts, total_attempts):`

  `return maximum_attempts - total_attempts`

**Observação:** a palavra-chave `return` não é uma função, portanto, você não deve colocar parênteses depois dela.

As instruções de retorno são úteis quando você deseja armazenar o que uma função retorna dentro de uma variável para usar em outra parte do código. Por exemplo, você pode usar essa variável para cálculos ou em instruções condicionais. No exemplo a seguir, as informações retornadas da chamada para `remaining_login_attempts` são armazenadas em uma variável chamada `remaining_attempts`. Em seguida, essa variável é usada em uma condicional que imprime uma mensagem `"Your account is locked"` quando `remaining_attempts` é menor ou igual a 0. Você pode executar esse código para explorar sua saída:

````python
def remaining_login_attempts(maximum_attempts, total_attempts):
    return maximum_attempts - total_attempts
remaining_attempts = remaining_login_attempts(3, 3)
if remaining_attempts <= 0:
    print("Your account is locked")
````

```
Your account is locked
```



Neste exemplo, a mensagem é impressa porque o cálculo na função resulta em 0.

**Observação:** quando o Python encontra uma instrução return, ele executa essa instrução e, em seguida, sai da função. Se houver linhas de código que seguem a instrução return dentro da função, elas não serão executadas. O exemplo anterior não continha nenhuma linha de código após a instrução return, mas isso pode se aplicar a outras funções, como uma que contenha uma instrução condicional.

## Variáveis globais e locais

Para entender melhor como as funções interagem com as variáveis, você deve saber a diferença entre variáveis globais e locais.

Ao definir e chamar funções, você está trabalhando com variáveis locais, que são diferentes das variáveis que você define fora do escopo de uma função.

### Variáveis globais

Uma **variável global** é uma variável que está disponível em todo o programa. As variáveis globais são atribuídas fora da definição de uma função. Sempre que essa variável for chamada, seja dentro ou fora de uma função, ela retornará o valor que lhe foi atribuído.

Por exemplo, você pode atribuir a seguinte variável no início de seu código:

`device_id = "7ad2130bd"`

Durante o restante do código, será possível acessar e modificar a variável `device_id` em condicionais, loops, funções e outras sintaxes.

### Variáveis locais

Uma **variável local** é uma variável atribuída em uma função. Essas variáveis não podem ser chamadas ou acessadas fora do corpo de uma função. As variáveis locais incluem parâmetros, bem como outras variáveis atribuídas em uma definição de função.

Na definição de função a seguir, total_string e name são variáveis locais:

`def greet_employee(name):`

  `total_string = "Welcome" + name`

  `return total_string`

A variável total_string é uma variável local porque é atribuída dentro da função. O parâmetro name é uma variável local porque também é criado quando a função é definida. 

Sempre que você chama uma função, o Python cria essas variáveis temporariamente enquanto a função está sendo executada e as exclui da memória depois que a função para de ser executada.

Isso significa que, se você chamar a função `greet_employee()` com um argumento e depois usar a variável total_string fora dessa função, receberá um erro.

### Práticas recomendadas para variáveis globais e locais

Ao trabalhar com variáveis e funções, é muito importante certificar-se de que o nome de uma determinada variável seja usado apenas uma vez, mesmo que uma seja definida globalmente e a outra localmente.

Ao usar variáveis globais dentro de funções, as funções podem acessar os valores de uma variável global. Você pode executar o exemplo a seguir para explorar isso:

````py
username = "elarson"
def identify_user():
    print(username)
identify_user()
````

```
elarson
```



O bloco de código retorna "elarson" mesmo que esse nome não esteja definido localmente. A função acessa a variável global. Se quisesse que a função identify_user() acomodasse outros nomes de usuário, teria de reatribuir a variável global de nome de usuário fora da função. Essa não é uma boa prática. Uma maneira melhor de passar valores diferentes para uma função é usar um parâmetro em vez de uma variável global.

Há outra coisa a considerar também. Se você reutilizar o nome de uma variável global em uma função, ela criará uma nova variável local com esse nome. Em outras palavras, haverá tanto uma variável global com esse nome quanto uma variável local com esse nome, e elas terão valores diferentes. Você pode considerar o seguinte bloco de código:

````py
username = "elarson"
print("1:" + username)
def greet():
    username = "bmoreno"
    print("2:" + username)
greet()
print("3:" + username)
````

```
1:elarson
2:bmoreno
3:elarson
```



A primeira instrução print ocorre antes da função, e o Python retorna o valor da variável global `username`, `"elarson"`. A segunda instrução print está dentro da função e retorna o valor da variável local username, que é `"bmoreno`". Mas isso não muda o valor da variável global, e quando `username` é impresso uma terceira vez após a chamada da função, ele ainda é `"elarson"`.

Devido a essa complexidade, é melhor evitar a combinação de variáveis globais e locais nas funções. 

## Principais lições

Trabalhar com variáveis em funções requer a compreensão de vários conceitos. Um parâmetro é um objeto incluído em uma definição de função para uso nessa função, um argumento são os Dados internos de uma função quando ela é chamada e a Palavra-chave return é usada para retornar informações de uma função. Além disso, as variáveis globais são variáveis acessíveis em todo o programa, e as variáveis locais são parâmetros e variáveis atribuídos em uma função que não podem ser usados fora dela. É importante garantir que todas as variáveis tenham nomes distintos, mesmo que uma seja uma variável local e a outra seja uma variável global.



# Trabalhar com funções integradas



Anteriormente, você explorou as funções internas do Python, incluindo print(), type(), max() e sorted(). **As funções incorpor** adas são funções que existem no Python e podem ser chamadas diretamente. Nesta leitura, você as explorará mais a fundo e também aprenderá sobre a função min(). Além disso, você verá como passar a saída de uma função para outra função.

## print()

A função print() gera a saída de um objeto especificado para a tela. A função print() é uma das funções mais comumente usadas no Python, pois permite a saída de qualquer detalhe de seu código.

Para usar a função print(), você passa o objeto que deseja imprimir como um argumento para a função. A função print() recebe qualquer número de argumentos, separados por vírgula, e imprime todos eles. Por exemplo, você pode executar o código a seguir que imprime uma string, uma variável, outra string e um inteiro juntos:

````python
month = "September"
print("Investigate failed login attempts during", month, "if more than", 100)
````

```
Investigate failed login attempts during September if more than 100
```



## type()

A função type() retorna o Tipo de dados de seu argumento. A função type() ajuda a manter o controle dos tipos de dados das variáveis para evitar erros em todo o código.

Para usá-la, você passa o objeto como argumento e ela retorna seu Tipo de dado. Ela aceita apenas um argumento. Por exemplo, você poderia especificar type("security") ou type(7).

### Passagem de uma função para outra

Ao trabalhar com funções, muitas vezes é necessário passá-las pelo site print() se quiser enviar o Tipo de dado para a tela. Esse é o caso quando se usa uma função como type(). Considere o código a seguir:

````py
print(type("This is a string"))
````

```
<class 'str'>
```



Ele exibe str, o que significa que o argumento passado para a função type() é uma string. Isso acontece porque a função type() é processada primeiro e sua saída é passada como argumento para a função print(). 

## max() e min()

A função max() retorna a maior entrada numérica passada para ela. A função min() retorna a menor entrada numérica passada para ela.

As funções max() e min() aceitam argumentos de vários valores numéricos ou de um iterativo, como uma Lista, e retornam o maior ou o menor valor, respectivamente.

Em um contexto de segurança cibernética, é possível usar essas funções para identificar a sessão mais longa ou mais curta em que um usuário fez a geração de registros. Se um usuário específico se conectou sete vezes durante uma semana e você armazenou os tempos de acesso em minutos em uma lista, poderá usar as funções max() e min() para localizar e imprimir as sessões mais longas e mais curtas:

````py
time_list = [12, 2, 32, 19, 57, 22, 14]
print(min(time_list))
print(max(time_list))
````

```
2
57
```



## sorted()

A função `sorted()` classifica os componentes de uma lista. A função `sorted()` também funciona em qualquer Iterativo, como uma string, e retorna os elementos classificados em uma lista. Por padrão, ela os classifica em ordem crescente. Quando recebe um iterável que contém números, ele os classifica do menor para o maior; isso inclui iteráveis que contêm dados numéricos, bem como iteráveis que contêm dados de strings que começam com números. Um iterável que contenha strings que comecem com caracteres alfabéticos será classificado em ordem alfabética.

A função sorted() usa um iterável, como uma lista ou uma cadeia de caracteres, como entrada. Assim, por exemplo, você pode usar o código a seguir para classificar a lista de sessões de login da mais curta para a mais longa:

````py
time_list = [12, 2, 32, 19, 57, 22, 14]
print(sorted(time_list))
````

```
[2, 12, 14, 19, 22, 32, 57]
```



Isso exibe a lista classificada.

A função `sorted()` não altera o iterável que ela classifica. O código a seguir ilustra isso:

````py
time_list = [12, 2, 32, 19, 57, 22, 14]
print(sorted(time_list))
print(time_list)
````

```
[2, 12, 14, 19, 22, 32, 57]
[12, 2, 32, 19, 57, 22, 14]
```



A primeira função `print()` exibe a lista classificada. Entretanto, a segunda função print(), que não inclui a função `sorted()`, exibe a lista conforme atribuída a time_list na primeira linha de código.

Outro detalhe importante sobre a função `sorted()` é que ela não pode receber listas ou strings que tenham elementos de mais de um Tipo de dados. Por exemplo, não é possível usar a lista `[1, 2, "hello"]`.

## Principais conclusões

As funções incorporadas são ferramentas poderosas no Python que permitem executar tarefas com um simples comando. A função `print()` imprime seus argumentos na tela, a função `type()` retorna o Tipo de dado de seu argumento, as funções `min()` e `max()` retornam o menor e o maior valores de um iterável, respectivamente, e `sorted()` organiza seu argumento.

## Recursos para obter mais informações

Essas foram apenas algumas das funções integradas do Python. Você pode continuar aprendendo sobre outras por conta própria:

- [A documentação da biblioteca padrão do Python](https://docs.python.org/3/library/functions.html): Lista das funções integradas do Python e informações sobre como usá-las



# Importar módulos e bibliotecas em Python



Anteriormente, você explorou as bibliotecas e os módulos. Você aprendeu que um **módulo** é um arquivo Python que contém funções adicionais, variáveis, classes e qualquer tipo de código executável. Você também aprendeu que uma **biblioteca** é uma coleção de módulos que fornecem código que os usuários podem acessar em seus programas. Você foi apresentado a alguns módulos da biblioteca padrão do Python e a algumas bibliotecas externas. Nesta leitura, você aprenderá a importar um módulo existente na biblioteca padrão do Python e a usar suas funções. Você também ampliará sua compreensão das bibliotecas externas.

## A biblioteca padrão do Python

A **Biblioteca Padrão do Python** é uma extensa coleção de códigos Python que geralmente vem junto com o Python. Ela inclui uma variedade de módulos, cada um com programação pré-construída centrada em um tipo específico de tarefa.

Por exemplo, você foi apresentado anteriormente aos seguintes módulos da Biblioteca Padrão do Python:

- O módulo re, que fornece funções usadas para pesquisar padrões em arquivos de log
- O módulo csv, que fornece funções usadas ao trabalhar com arquivos .csv 
- Os módulos glob e os, que fornecem funções usadas na interação com a linha de comando
- Os módulos time e datetime, que fornecem funções usadas ao trabalhar com registros de data e hora

Outro módulo da Biblioteca Padrão Python é o statistics. O módulo statistics inclui funções usadas no cálculo de estatísticas relacionadas a dados numéricos. Por exemplo, mean() é uma função no módulo statistics que recebe dados numéricos como entrada e calcula sua média (ou average). Além disso, median() é uma função no módulo statistics que recebe dados numéricos como entrada e calcula sua mediana (ou valor médio).

## Como importar módulos da biblioteca padrão do Python

Para acessar os módulos da biblioteca padrão do Python, é necessário importá-los. Você pode optar por importar um módulo completo ou importar apenas funções específicas de um módulo.

### **Importando um Módulo inteiro**

Para importar um módulo inteiro da Biblioteca Padrão Python, use a palavra-chave import. A palavra-chave import procura um Módulo ou uma biblioteca em um sistema e o adiciona ao ambiente Python local. Após import, especifique o nome do Módulo a ser importado. Por exemplo, você pode especificar import statistics para importar o módulo statistics. Isso importará todas as funções dentro do módulo statistics para uso posterior em seu código.

Por exemplo, talvez você queira usar a função mean() do módulo statistics para calcular o número médio de tentativas de login com falha por mês para um determinado usuário. No bloco de código a seguir, o número total de tentativas de login com falha para cada um dos doze meses é armazenado em uma lista chamada `monthly_failed_attempts.` Execute esse código e analise como mean() pode ser usado para calcular a média desses totais mensais de login com falha e armazená-la em mean_failed_attempts:

````py
import statistics
monthly_failed_attempts = [20, 17, 178, 33, 15, 21, 19, 29, 32, 15, 25, 19]
mean_failed_attempts = statistics.mean(monthly_failed_attempts)
print("mean:", mean_failed_attempts)
````

```
mean: 35.25
```



A saída retorna uma média de 35.25. Você pode notar o valor discrepante de 178 e deseja encontrar o valor médio também. Para fazer isso por meio da função median(), você pode usar o código a seguir:

````py
import statistics
monthly_failed_attempts = [20, 17, 178, 33, 15, 21, 19, 29, 32, 15, 25, 19]
median_failed_attempts = statistics.median(monthly_failed_attempts)
print("median:", median_failed_attempts)
````

```
median: 20.5
```



Isso lhe dá o valor de 20.5, que também pode ser útil para analisar as estatísticas de tentativas de login fracassadas do usuário.

**Observação:** ao importar um módulo inteiro da Python Standard Library, você precisa identificar o nome do módulo com a função ao chamá-la. Você pode fazer isso colocando o nome do Módulo seguido de um ponto (.) antes do nome da função. Por exemplo, os blocos de código anteriores usam statistics.mean() e statistics.median() para chamar essas funções.

### **Importação de funções específicas de um Módulo**

Para importar uma função específica da biblioteca padrão Python, você pode usar a palavra-chave from. Por exemplo, se quiser importar apenas a função `median()` do módulo `statistics`, você pode escrever `from statistics import median`.

Para importar várias funções de um Módulo, você pode separar as funções que deseja importar com uma vírgula. Por exemplo, `from statistics import mean`, `median` importa as funções `mean()` e `median()` do módulo `statistics`.

Um detalhe importante a ser observado é que, se você importar funções específicas de um módulo, não precisará mais especificar o nome do módulo antes dessas funções. Você pode examinar isso no código a seguir, que importa especificamente apenas as funções median() e mean() do módulo statistics e executa os mesmos cálculos que os exemplos anteriores:

````py
from statistics import mean, median
monthly_failed_attempts = [20, 17, 178, 33, 15, 21, 19, 29, 32, 15, 25, 19]
mean_failed_attempts = mean(monthly_failed_attempts)
print("mean:", mean_failed_attempts)
median_failed_attempts = median(monthly_failed_attempts)
print("median:", median_failed_attempts)
````

```
mean: 35.25
median: 20.5
```



Não é mais necessário especificar `statistics.mean()` ou `statistics.median()` e, em vez disso, o código incorpora essas funções como `mean()` e `median()`.

## Bibliotecas externas

Além da biblioteca padrão do Python, também é possível fazer download de bibliotecas externas e incorporá-las ao seu código Python. Por exemplo, anteriormente você foi apresentado à Beautiful Soup (bs4) para analisar arquivos HTML e à `NumPy (numpy)` para matrizes unidimensionais e cálculos matemáticos. Antes de usá-las em um Notebook `Jupyter` ou em um ambiente do Google Colab, é necessário instalá-las primeiro.

Para instalar uma biblioteca, como a `numpy`, em qualquer ambiente, você pode executar a seguinte linha antes de importar a biblioteca:

`%pip install numpy`

Isso instala as bibliotecas para que você possa usá-las em seu Notebook.

Depois que uma biblioteca for instalada, você poderá importá-la diretamente para o Python usando a Palavra-chave `import` de forma semelhante à usada para importar módulos da Biblioteca Padrão do Python. Por exemplo, após a instalação do `numpy`, você pode usar este código para importá-lo:

`import numpy`

## Principais conclusões

A Python Standard Library contém muitos módulos que você pode importar, incluindo `re`, `csv`, `os`, `glob`, `time`, `datetime` e `statistics`. Para importar esses módulos, você deve usar a Palavra-chave import. A Sintaxe varia de acordo com o fato de você querer importar o Módulo inteiro ou apenas funções específicas dele. As bibliotecas externas também podem ser importadas para o Python, mas elas precisam ser instaladas primeiro.



# Garantir a sintaxe e a legibilidade adequadas em Python

Anteriormente, você foi apresentado ao guia de estilo PEP 8 e suas diretrizes estilísticas para programadores que trabalham em Python. Você também aprendeu como adicionar comentários e usar a indentação correta torna seu código mais legível. Além disso, a indentação correta garante que seu código seja executado corretamente. Esta leitura explora ainda mais essas ideias e também se concentra em itens comuns a serem verificados na Sintaxe do seu código para garantir que ele seja executado.

## Comentários

Um **comentário** é uma nota que os programadores fazem sobre as intenções por trás de seu código. Os comentários facilitam a leitura e o entendimento de seu código por você e por outros programadores.

É importante iniciar seu código com um comentário que explique o que o programa faz. Em seguida, ao longo do código, adicione comentários adicionais sobre suas intenções por trás de seções específicas.

Ao adicionar comentários, você pode adicionar comentários de linha única e comentários de várias linhas.

### **Comentários de linha única**

Os comentários de linha única em Python começam com o símbolo (#). De acordo com o guia de estilo PEP 8, é uma prática recomendada manter todas as linhas em Python com menos de 79 caracteres para manter a legibilidade, e isso inclui os comentários.

Os comentários de linha única são frequentemente usados em todo o programa para explicar a intenção por trás de seções específicas do código. Por exemplo, isso pode ocorrer quando estiver explicando componentes mais simples do seu programa, como o seguinte loop for:

````py


# Print elements of 'computer_assets' list

computer_assets = ["laptop1", "desktop20", "smartphone03"]

for asset in computer_assets:

  print(asset)
````



**Observação:** Os comentários são importantes ao escrever códigos mais complexos, como funções, vários loops ou instruções condicionais. Entretanto, eles são opcionais ao escrever códigos menos complexos, como reatribuir uma variável.

### **Comentários de várias linhas**

Os comentários com várias linhas são usados quando são necessários mais de 79 caracteres em um único comentário. Por exemplo, isso pode ocorrer ao definir uma função se o comentário descrever suas entradas e seus tipos de dados, bem como sua saída.

Há duas maneiras comumente usadas para escrever comentários de várias linhas em Python. A primeira é usar o símbolo hashtag (#) em várias linhas:

````py
# remaining_login_attempts() function takes two integer parameters,

# the maximum login attempts allowed and the total attempts made,

# and it returns an integer representing remaining login attempts

def remaining_login_attempts(maximum_attempts, total_attempts):

  return maximum_attempts - total_attempts
````



Outra forma de escrever comentários com várias linhas é usar strings de documentação e não atribuí-las a uma variável. As strings de documentação, também chamadas de docstrings, são strings escritas em várias linhas e usadas para documentar o código. Para criar uma cadeia de documentação, use aspas triplas (""" """).

Você também pode adicionar o comentário à função no exemplo anterior dessa forma:

````py
"""

remaining_login_attempts() function takes two integer parameters,

the maximum login attempts allowed and the total attempts made,

and it returns an integer representing remaining login attempts

"""
````



## Indentação correta

**A indentação** é o espaço adicionado no início de uma linha de código. Em Python, você deve recuar o corpo de instruções condicionais, instruções iterativas e definições de funções. A indentação não é apenas necessária para que o Python interprete essa sintaxe corretamente, mas também pode facilitar a leitura do seu código por você e por outros programadores.

O guia de estilo PEP 8 recomenda que os recuos sejam de quatro espaços. Por exemplo, se você tivesse uma instrução condicional dentro de um loop while, o corpo do loop seria recuado quatro espaços e o corpo da condicional seria recuado quatro espaços além disso. Isso significa que a condicional seria recuada oito espaços no total.

````py
count = 0

login_status = True

while login_status == True:

  print("Try again.")

  count = count + 1

  if count == 4:

​    login_status = False
````



## Manutenção da sintaxe correta

Os erros de sintaxe envolvem o uso inválido da linguagem Python. Eles são incrivelmente comuns no Python, portanto, concentrar-se na sintaxe correta é essencial para garantir que seu código seja executado. O conhecimento dos erros comuns o ajudará a corrigi-los com mais facilidade.

Os erros de sintaxe geralmente ocorrem devido a erros com tipos de dados ou nos Cabeçalhos de instruções condicionais ou iterativas ou de definições de funções.

### Tipos de dados

A Sintaxe correta varia de acordo com o Tipo de dado:

- Coloque os dados de string entre aspas.
  - Exemplo: username = "bmoreno"
- Não coloque aspas nos tipos de dados inteiros, Flutuantes ou Booleanos.
  - Exemplos: login_attempts = 5, percentage_successful = .8, login_status = True
- Coloque as listas entre colchetes e separe os elementos de uma lista com vírgulas.
  - Exemplo: username_list = ["bmoreno", "tshah"]

### Dois-pontos em Cabeçalhos

O Cabeçalho de uma instrução condicional ou iterativa ou de uma definição de função deve terminar com dois pontos. Por exemplo, dois pontos aparecem no final do cabeçalho da seguinte definição de função:

````py
def remaining_login_attempts(maximum_attempts, total_attempts):

  return maximum_attempts - total_attempts
````



## Principais conclusões

O guia de estilo PEP 8 fornece recomendações para escrever códigos que possam ser facilmente compreendidos e lidos por outros programadores Python. Para deixar suas intenções claras, você deve incorporar comentários em seu código. Dependências do comprimento do comentário, você pode seguir as convenções para comentários de linha única ou de várias linhas. Também é importante usar a indentação correta; isso garante que seu código será executado como pretendido e também facilita a leitura. Por fim, você também deve estar ciente dos problemas comuns de sintaxe para que possa corrigi-los com mais facilidade.

## Recursos para obter mais informações

Aprender a escrever códigos legíveis pode ser um desafio, portanto, certifique-se de revisar o guia de estilo PEP 8 e aprender sobre outros aspectos da legibilidade do código.

- [PEP 8 - Guia de estilo para código Python](https://peps.python.org/pep-0008/): O guia de estilo do PEP 8 contém todos os padrões do código Python. Ao ler esse guia, é útil usar o índice para navegar pelos conceitos que você ainda não aprendeu.



# Guia de referência: Conceitos Python do Módulo 2



Este guia de referência contém a linguagem Python introduzida durante o módulo 2. O guia está organizado nas seções a seguir:

- Funções definidas pelo usuário
- Funções incorporadas
- Importação de módulos e bibliotecas
- Comentários

Em cada seção, os itens geralmente aparecem na ordem em que foram introduzidos.

## Acessar e salvar o guia

Você pode salvar uma cópia deste guia para referência futura. Você pode usá-lo como um recurso para prática adicional ou em seus futuros projetos profissionais.

Para acessar uma versão para download deste item do curso, clique no link a seguir e selecione *Usar modelo*.

[Guia de referência: Conceitos de Python do módulo 2](https://docs.google.com/document/d/19kQXJP2L5P4_jBOhW8D9IyA4ewaQj1QWv1-Lp2HL0YU/template/preview?resourcekey=0-fcyLEIA6lINwqu6dTvTM0g#heading=h.6eikvmfmqupl)



# Termos do glossário do Módulo 2



## **Termos e definições do Curso 7, Módulo 2**

**Argumento (Python):** Os dados trazidos para uma Função quando ela é chamada

**Função embutida:** Uma função que existe no Python e pode ser chamada diretamente

**Comentário:** Uma nota que os programadores fazem sobre a intenção por trás de seu código

**Função:** Uma seção de código que pode ser reutilizada em um programa

**Variável global:** Uma variável que está disponível em todo o programa

**Indentação:** Espaço adicionado no início de uma linha de código

**Bibliotecas:** Uma coleção de módulos que fornecem código que os usuários podem acessar em seus programas

**Variável local:** Uma variável atribuída dentro de uma função

**Módulo**: Um arquivo Python que contém funções adicionais, variáveis, classes e qualquer tipo de código executável

**Parâmetro (Python):** Um objeto que é incluído em uma definição de função para uso nessa função

**Guia de estilo PEP 8:** Um recurso que fornece diretrizes estilísticas para programadores que trabalham com Python.

**Python Standard Library (Biblioteca padrão Python):** Uma extensa coleção de códigos Python que geralmente vem empacotada com o Python

**Declaração de retorno:** Uma instrução Python que é executada dentro de uma função e envia informações de volta para a chamada da função 

**Guia de estilo:** Um manual que informa a redação, a formatação e o design de documentos

**Função definida pelo usuário:** Uma função que os programadores projetam para suas necessidades específicas







