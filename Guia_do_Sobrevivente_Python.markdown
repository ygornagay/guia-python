# Técnico de Inteligência Artificial - SENAC

![Capa do Guia do Sobrevivente: Python](capa_inicial.png)

# Guia do Sobrevivente: Python 🐍

Bem-vindos, sobreviventes! Esta é um guia e um resumo dos nossos primeiros passos no mundo de Python, com o professor Peterson Chiquetto (https://github.com/petersonchiquetto). Nessa apostila, teremos os códigos do professor explicados, exercícios resolvidos e até um guia pra domar o VS Code. Se Python parece um alienígena, relaxa: vamos traduzi-lo pro humanês com analogias, piadinhas e paciência infinita. Preparado pra virar um herói ou heroína da nossa turma de Tec. de IA? 🚀

---

## Configurando a Mochila: Instalando o Python e o VS Code no Windows 🛠️

Antes de desbravar o cosmos, precisamos equipar nossa mochila. O Visual Studio Code (VS Code, "Primeiro de Seu Nome, Rei dos Editores, Protetor dos Códigos, Senhor das Extensões, Quebrador de Bugs") é nossa nave mochileira pra escrever códigos, e o Python é o combustível. Aqui vai o guia mais simples da galáxia pra instalar tudo no Windows.

*Recomendo escutar Toto - Africa nesse início de jornada!*

### Passo 1: Instalar o Python
- **O que é?** Python é a linguagem que usamos. Sem ele, o VS Code é só uma mochila vazia.
- **Como fazer**:
  1. **Opção 1: Windows Store (recomendado)**: Abra a Microsoft Store, pesquise "Python" e instale a versão mais recente (ex.: Python 3.13). A loja configura tudo automaticamente, incluindo atualizações.
  2. **Opção 2: Site oficial**: Acesse [python.org](https://www.python.org/), clique em "Downloads" e baixe a versão 3.13 ou superior. Abra o instalador e **marque "Add Python to PATH"** (isso diz pro Windows: "Python existe!"). Clique em "Install Now" e espere.
- **Teste rápido**: Abra o Prompt de Comando ou PowerShell (tecla Windows + R, digite `cmd` ou `powershell`, aperte Enter) e digite `python --version`. Se aparecer "Python 3.13.0", tá funcionando!
- **Erro comum**: Se der "command not found", o PATH não foi configurado. Reinstale pelo instalador e marque "Add Python to PATH" ou use a Windows Store.

### Passo 2: Instalar o VS Code
- **O que é?** O VS Code é onde você escreve e roda seus códigos. É uma mochila digital com superpoderes.
- **Como fazer**:
  1. **Opção 1: Windows Store (recomendado)**: Abra a Microsoft Store, pesquise "Visual Studio Code" e instale. É rápido e já vem configurado.
  2. **Opção 2: Site oficial**: Acesse [code.visualstudio.com](https://code.visualstudio.com/), clique em "Download for Windows", abra o instalador e siga clicando em "Next" e "Install" (deixe as opções padrão).
- **Teste rápido**: Abra o VS Code. Se aparecer uma tela colorida com "Welcome", tá de boa!
- **Putz, tá em inglês e eu não falo inglês! 😱**: Calma, viajante cósmico! No VS Code, clique no ícone de extensões (bloquinhos à esquerda), pesquise "Portuguese (Brazil) Language Pack", instale e reinicie o VS Code. A magia acontece, e tudo fica em português!

### Passo 3: Configurar o VS Code pro Python
- **O que fazer**:
  1. No VS Code, clique no ícone de extensões (mesmo lugar da tradução pro português).
  2. Pesquise "Python" e instale a extensão oficial da Microsoft (primeira da lista).
  3. Crie um arquivo novo (Ctrl + N), salve com `.py` (ex.: `meu_codigo.py`).
  4. Escreva um código simples, tipo `print("Teste!")`, e clique no triângulo verde no canto superior direito pra rodar.
- **Erro comum**: Se o VS Code não achar o Python, vá em "Arquivo > Preferências > Configurações", pesquise "Python Path" e aponte pro caminho do Python (ex.: `C:\Users\SeuNome\AppData\Local\Programs\Python\Python313\python.exe`).
- *SeuNome é o nome da sua pasta!*

### Dica Pro
- Ative o Auto Save e diga adeus aos crashes! No VS Code, vá em "Arquivo > Auto Save" e marque a opção. É como ter um robô que salva sua mochila cósmica antes de cada aventura. Se preferir atalhos, use `Ctrl + K, S` pra ativar/desativar rapidinho.

**Autoavaliação**: Conseguiu instalar o Python e o VS Code? [ ] Sim [ ] Não

---

## Dicionário do Desesperado 📖
O manual de tradução pra entender Python sem crise. Aqui tá tudo o que o professor Peterson jogou na aula, explicado como se fosse um guia de viagem intergaláctico.

- **print()**: O papagaio do Python. Mostra na tela o que você mandar. Exemplo: `print("Oi!")` → "Oi!" na tela.
- **Variáveis**: Caixinhas pra guardar dados. Exemplo: `nome = "Peterson"` → guardei o texto "Peterson" na caixinha "nome".
- **String (str)**: Texto entre aspas. Exemplo: `"Banana"` ou `'Oi'`.
- **int**: Número inteiro, tipo `28`.
- **float**: Número com vírgula, tipo `1.78`.
- **bool**: Verdadeiro (`True`) ou falso (`False`).
- **input()**: O microfone do Python. Pega o que o usuário digita. Exemplo: `nome = input("Seu nome: ")`.
- **if/elif/else**: Decisões tipo "se isso, faça aquilo; senão, faça outra coisa". Exemplo: `if idade >= 18: print("Adulto")`.
- **while**: Repete um código enquanto algo for verdade. Tipo: "Enquanto eu tiver fome, como mais um pedaço de pizza espacial."
- **for**: Repete um código um número fixo de vezes. Tipo: "Toca minha playlist 5 vezes."
- **range()**: Cria uma sequência de números. Exemplo: `range(5)` → 0, 1, 2, 3, 4.

---

## Códigos do Professor Explicados!
O professor Peterson lançou vários códigos na aula. Vamos destrinchar cada um como se fosse a primeira vez que você vê Python, com a vibe de um mochileiro explorando o cosmos!

### Código 1: Variáveis e Tipos de Dados
```python
nome = "Peterson"       # str (string): textos, como "Peterson"
idade = 28             # int: número inteiro
altura = 1.78          # float: número com vírgula
aprendendo = True      # bool: verdadeiro ou falso
print(nome, idade, altura, aprendendo)
```

**Explicação linha por linha**:
- `nome = "Peterson"`: Cria uma caixinha chamada "nome" e guarda o texto "Peterson". As aspas dizem: "Isso é uma string!"
- `idade = 28`: Caixinha "idade" guarda o número inteiro 28. Sem aspas, porque não é texto.
- `altura = 1.78`: Caixinha "altura" guarda o número com vírgula 1.78 (um float).
- `aprendendo = True`: Caixinha "aprendendo" guarda um valor booleano (True ou False). É como um interruptor: ligado (True) ou desligado (False).
- `print(nome, idade, altura, aprendendo)`: O papagaio Python mostra tudo na tela, separando com espaços. Saída: `Peterson 28 1.78 True`.

**Analogia**: Variáveis são como bolsos numa mochila cósmica. Você coloca um rótulo ("nome", "idade") e guarda algo dentro (texto, número, etc.). O `print()` é como abrir os bolsos e mostrar o que tem dentro.

**Erro comum**: Esquecer aspas em strings. `nome = Peterson` dá erro, porque o Python acha que "Peterson" é uma variável, não texto. Sempre use `"Peterson"`.

**Exemplo prático**:
```python
nome = "João"  # Troque pelo seu nome
idade = 20
altura = 1.75
estudando = True
print("Eu sou", nome, "e tenho", idade, "anos!")
```

---

### Código 2: Entrada de Dados
```python
nome = input("Qual é o seu nome? ")
print("Olá,", nome)
idade = int(input("Qual é a sua idade? "))
print("Sua idade é,", idade)
```

**Explicação linha por linha**:
- `nome = input("Qual é o seu nome? ")`: O `input()` é um comunicador intergaláctico que pergunta algo (o texto entre aspas aparece na tela) e guarda a resposta na caixinha "nome". Tudo que o usuário digita vira string.
- `print("Olá,", nome)`: Mostra uma saudação com o nome digitado.
- `idade = int(input("Qual é a sua idade? "))`: Pede a idade, mas usa `int()` pra transformar a string digitada (ex.: "25") num número inteiro (25). Isso é importante pra cálculos.
- `print("Sua idade é,", idade)`: Mostra a idade.

**Analogia**: O `input()` é como um alienígena anotando seu pedido. Ele sempre entrega texto, então usamos `int()` pra transformar em número, tipo pedir "25" e confirmar que é um número, não uma palavra.

**Erro comum**: Esquecer o `int()` e tentar usar a idade como número. Exemplo: `idade = input(...)` followed by `idade + 1` vai dar erro ou concatenar como texto ("25" + "1" = "251"). Sempre converta com `int()` pra cálculos.

**Exemplo prático**:
```python
nome = input("Qual seu apelido? ")
print("E aí,", nome, "! Beleza?")
```

---

### Código 3: Operadores Matemáticos
```python
a = 10
b = 3
print(a + b)  # Soma
print(a - b)  # Subtração
print(a * b)  # Multiplicação
print(a / b)  # Divisão
print(a // b) # Divisão inteira
print(a % b)  # Resto da divisão
print(a ** b) # Potência
```

**Explicação linha por linha**:
- `a = 10` e `b = 3`: Duas caixinhas com números inteiros.
- `print(a + b)`: Soma (10 + 3 = 13).
- `print(a - b)`: Subtrai (10 - 3 = 7).
- `print(a * b)`: Multiplica (10 * 3 = 30).
- `print(a / b)`: Divide normalmente (10 / 3 = 3.333...).
- `print(a // b)`: Divide e pega só a parte inteira (10 / 3 = 3).
- `print(a % b)`: Pega o resto da divisão (10 ÷ 3 sobra 1).
- `print(a ** b)`: Eleva à potência (10³ = 1000).

**Analogia**: Operadores são como ferramentas numa calculadora espacial. Cada um faz um trabalho diferente, e o `//` e `%` são tipo "divisão de suprimentos": `//` dá quantos pacotes inteiros cabem, e `%` dá o que sobra.

**Erro comum**: Confundir `/` (divisão normal, dá float) com `//` (divisão inteira, dá int). Se quiser só a parte inteira, use `//`.

**Exemplo prático**:
```python
x = 5
y = 2
print("Soma:", x + y)  # 7
print("Resto:", x % y) # 1
```

---

### Código 4: Condicionais (if, elif, else)
```python
idade = int(input("Digite sua idade: "))
if idade >= 18:
    print("Você é maior de idade")
elif idade > 12:
    print("Você é adolescente")
else:
    print("Você é uma criança")
```

**Explicação linha por linha**:
- `idade = int(input("Digite sua idade: "))`: Pede a idade e converte pra número.
- `if idade >= 18:`: Verifica se a idade é maior ou igual a 18. Se sim, executa o código abaixo (note os dois pontos `:` e a indentação).
- `print("Você é maior de idade")`: Mostra se a condição do `if` for verdadeira.
- `elif idade > 12:`: Se o `if` for falso, testa se a idade é maior que 12.
- `else:`: Se nenhuma condição anterior for verdadeira, executa o código do `else`.
- **Indentação**: As linhas abaixo de `if`, `elif` e `else` precisam estar "afundadas" (com 4 espaços ou um Tab). É como dizer pro Python: "Isso faz parte da decisão."

**Analogia**: É como escolher um planeta pra pousar: "Se tiver oxigênio, pouso na Terra; senão, se tiver comida, pouso em Marte; senão, fico na nave."

**Erro comum**: Esquecer os dois pontos `:` ou a indentação. Sem eles, o Python surta. Exemplo: `if idade >= 18 print("Erro")` não funciona.

**Exemplo prático**:
```python
nota = int(input("Digite sua nota: "))
if nota >= 7:
    print("Aprovado!")
else:
    print("Tenta de novo!")
```

---

### Código 5: Laços de Repetição (while e for)
```python
# While
contador = 0
while contador <= 10:
    print("Contando", contador)
    contador += 1
```

```python
# While (outro exemplo)
contador = 0
while contador < 5:
    print("Contando:", contador)
    contador += 1
```

```python
# For
for i in range(5):
    print("Repetição", i)
```

**Explicação (while)**:
- `contador = 0`: Cria uma caixinha com o valor 0.
- `while contador <= 8000:`: Enquanto o contador for menor ou igual a 8000, repete o código abaixo.
- `print("Contando", contador)`: Mostra o valor atual.
- `contador += 1`: Aumenta o contador em 1 (é o mesmo que `contador = contador + 1`).
- No segundo exemplo, faz a mesma coisa, mas até 4 (menor que 5).

**Explicação (for)**:
- `for i in range(5)`: Cria uma sequência de 0 a 4 (0, 1, 2, 3, 4) e executa o código pra cada número, guardando o número atual na caixinha "i".
- `print("Repetição", i)`: Mostra o número atual.

**Analogia**:
- `while`: É como explorar um planeta enquanto tiver oxigênio. Você checa o tanque a cada passo.
- `for`: É como visitar 5 planetas numa rota fixa. Você sabe quantas paradas vai fazer.

**Erro comum**: Esquecer de aumentar o contador no `while` (ex.: tirar o `contador += 1`). Isso cria um loop infinito, e seu programa trava. Sempre atualize a condição do `while`!

**Exemplo prático**:
```python
for x in range(3):
    print("Oi, repeti", x, "vezes!")
```

---

### Código 6: Métodos de Listas
O professor terminou com métodos de listas. Listas são como eco-bags cósmicas onde você guarda várias coisas (números, textos, etc.). Aqui vai um resumo dos métodos que ele explicou:

```python
# append()
frutas = ['maçã', 'banana']
frutas.append('laranja')
print(frutas)  # ['maçã', 'banana', 'laranja']

# insert()
numeros = [1, 2, 3]
numeros.insert(1, 100)
print(numeros)  # [1, 100, 2, 3]

# extend()
lista1 = [1, 2]
lista1.extend([3, 4])
print(lista1)  # [1, 2, 3, 4]

# remove()
valores = [10, 20, 30, 20]
valores.remove(20)
print(valores)  # [10, 30, 20]

# pop()
itens = ['a', 'b', 'c']
ultimo = itens.pop()
print(ultimo)  # 'c'
print(itens)   # ['a', 'b']

# clear()
nomes = ['Ana', 'Bruno', 'Carlos']
nomes.clear()
print(nomes)  # []

# index()
letras = ['x', 'y', 'z']
print(letras.index('y'))  # 1

# count()
nums = [1, 2, 2, 3, 2]
print(nums.count(2))  # 3

# sort()
valores = [5, 1, 4]
valores.sort()
print(valores)  # [1, 4, 5]

# reverse()
dados = [1, 2, 3]
dados.reverse()
print(dados)  # [3, 2, 1]
```

**Explicação resumida**:
- Listas são criadas com colchetes: `[]`. Exemplo: `frutas = ['maçã', 'banana']`.
- Cada método é como uma ferramenta pra mexer na mochila:
  - `append()`: Coloca algo no final da mochila.
  - `insert(pos, item)`: Coloca algo numa posição específica.
  - `extend()`: Junta outra mochila na sua.
  - `remove()`: Tira a primeira coisa que achar.
  - `pop()`: Tira algo (padrão: o último) e te mostra o que tirou.
  - `clear()`: Esvazia a mochila.
  - `index()`: Diz onde algo tá na mochila.
  - `count()`: Conta quantas vezes algo aparece.
  - `sort()`: Organiza a mochila (crescente ou decrescente).
  - `reverse()`: Vira a mochila de cabeça pra baixo.

**Analogia**: Uma lista é como uma pochete de viagem. Você pode adicionar suprimentos (`append`), tirar coisas (`remove`, `pop`), reorganizar (`sort`), ou até virar tudo do avesso (`reverse`).

**Erro comum**: Tentar `remove()` algo que não tá na lista dá erro. Sempre cheque se o item existe antes!

**Exemplo prático**:
```python
minha_lista = ["gato", "cachorro"]
minha_lista.append("papagaio")
print(minha_lista)  # ['gato', 'cachorro', 'papagaio']
```

**Exercícios práticos** (pra fixar os métodos, como o professor sugeriu):

**Exercício 6.1: Montando a Lista de Compras**
- **Enunciado**: Crie uma lista de compras com 3 itens iniciais (ex.: "leite", "pão", "ovos"). Use `append()` pra adicionar um item, `insert()` pra colocar algo na segunda posição, e `remove()` pra tirar um item. Mostre a lista final.
- **Código**:
  ```python
  compras = ["leite", "pão", "ovos"]
  print("Lista inicial:", compras)
  compras.append("biscoito")
  print("Depois de append:", compras)
  compras.insert(1, "café")
  print("Depois de insert:", compras)
  compras.remove("pão")
  print("Depois de remove:", compras)
  ```
- **Saída**:
  ```
  Lista inicial: ['leite', 'pão', 'ovos']
  Depois de append: ['leite', 'pão', 'ovos', 'biscoito']
  Depois de insert: ['leite', 'café', 'pão', 'ovos', 'biscoito']
  Depois de remove: ['leite', 'café', 'ovos', 'biscoito']
  ```

**Exercício 6.2: Organizando a Playlist**
- **Enunciado**: Crie uma lista com 4 músicas. Use `sort()` pra organizar em ordem alfabética, `reverse()` pra inverter a ordem, e `pop()` pra remover a última música. Mostre a lista em cada etapa.
- **Código**:
  ```python
  playlist = ["Bohemian Rhapsody", "Billie Jean", "Smells Like Teen Spirit", "Sweet Child O' Mine"]
  print("Playlist inicial:", playlist)
  playlist.sort()
  print("Depois de sort:", playlist)
  playlist.reverse()
  print("Depois de reverse:", playlist)
  ultima = playlist.pop()
  print("Música removida:", ultima)
  print("Playlist final:", playlist)
  ```
- **Saída**:
  ```
  Playlist inicial: ['Bohemian Rhapsody', 'Billie Jean', 'Smells Like Teen Spirit', 'Sweet Child O' Mine']
  Depois de sort: ['Billie Jean', 'Bohemian Rhapsody', 'Smells Like Teen Spirit', 'Sweet Child O' Mine']
  Depois of reverse: ['Sweet Child O' Mine', 'Smells Like Teen Spirit', 'Bohemian Rhapsody', 'Billie Jean']
  Música removida: Billie Jean
  Playlist final: ['Sweet Child O' Mine', 'Smells Like Teen Spirit', 'Bohemian Rhapsody']
  ```

**Exercício 6.3: Contando Itens Repetidos**
- **Enunciado**: Crie uma lista com números (ex.: [1, 2, 2, 3, 2, 4]). Use `count()` pra contar quantas vezes o número 2 aparece e `index()` pra achar a posição do primeiro 3. Mostre os resultados.
- **Código**:
  ```python
  numeros = [1, 2, 2, 3, 2, 4]
  print("Lista:", numeros)
  quantidade = numeros.count(2)
  print("O número 2 aparece", quantidade, "vezes")
  posicao = numeros.index(3)
  print("O número 3 está na posição", posicao)
  ```
- **Saída**:
  ```
  Lista: [1, 2, 2, 3, 2, 4]
  O número 2 aparece 3 vezes
  O número 3 está na posição 3
  ```

---

## Exercícios Resolvidos!
*Recomendo ouvir Scorpions - Rock You Like a Hurricane*

Aqui vão os exercícios do professor Peterson, resolvidos com aquele toque de "parece impossível, mas é tranquilo".

### Exercício 1.1: Olá, Mundo!
**Enunciado**: Crie um programa que exiba "Bem-vindo ao mundo da programação!".

**Passo 1: Entender o Problema**
- Só precisamos usar o `print()` pra mostrar uma mensagem fixa.
- Não tem entrada de usuário nem cálculos, é o mais simples possível.

**Passo 2: Esqueleto do Código**
```python
# Mostrar a mensagem
print("Bem-vindo ao mundo da programação!")
```

**Passo 3: Possíveis Bugs**
- **Erro**: Esquecer as aspas. `print(Bem-vindo ao mundo da programação!)` dá erro, porque o Python acha que é uma variável.
- **Solução**: Sempre coloque texto entre aspas (`""` ou `''`).

**Código Final**:
```python
print("Bem-vindo ao mundo da programação!")
```

---

### Exercício 2.1: Variáveis e Tipos de Dados
**Enunciado**: Declare variáveis para seu nome, idade, altura e se está estudando Python (booleano). Exiba com `print()`.

**Passo 1: Entender o Problema**
- Criar 4 caixinhas (variáveis): nome (string), idade (int), altura (float), estudando (bool).
- Mostrar tudo numa frase com `print()`.

**Passo 2: Esqueleto do Código**
```python
# Criar as variáveis
nome = "SeuNome"  # String: seu nome
idade = 20        # Int: sua idade
altura = 1.75     # Float: sua altura
estudando = True  # Bool: você tá estudando Python

# Mostrar as informações
print("Nome:", nome, "| Idade:", idade, "| Altura:", altura, "| Estudando Python?", estudando)
```

**Passo 3: Possíveis Bugs**
- **Erro**: Usar números sem cuidado. Exemplo: `altura = "1.75"` (string) em vez de `altura = 1.75` (float). Se for fazer cálculos depois, use float.
- **Solução**: Cheque o tipo com `print(type(variavel))`. Exemplo: `type(altura)` deve mostrar `<class 'float'>`.

**Código Final**:
```python
nome = "João"  # Troque pelo seu nome
idade = 20
altura = 1.75
estudando = True
print("Nome:", nome, "| Idade:", idade, "| Altura:", altura, "| Estudando Python?", estudando)
```

---

### Exercício 3.1: Entrada de Dados
**Enunciado**: Peça o nome e a idade do usuário e mostre "Olá, [nome]! Você tem [idade] anos.".

**Passo 1: Entender o Problema**
- Usar `input()` pra pegar nome e idade.
- Converter idade pra `int` (porque `input()` dá string).
- Mostrar uma mensagem personalizada.

**Passo 2: Esqueleto do Código**
```python
# Pegar o nome
nome = input("Digite seu nome: ")

# Pegar a idade
idade = int(input("Digite sua idade: "))

# Mostrar a mensagem
print("Olá,", nome, "! Você tem", idade, "anos.")
```

**Passo 3: Possíveis Bugs**
- **Erro**: Se o usuário digitar algo que não é número (ex.: "vinte") no `int(input())`, o programa trava.
- **Solução**: Por enquanto, peça pra digitar números. Mais tarde, podemos usar `try/except` pra lidar com erros.
- **Erro**: Esquecer a conversão com `int()`. Se fizer `idade = input(...)`, a idade vira texto.

**Código Final**:
```python
nome = input("Digite seu nome: ")
idade = int(input("Digite sua idade: "))
print("Olá,", nome, "! Você tem", idade, "anos.")
```

---

### Exercício 5.1: Condicionais
**Enunciado**: Peça a idade do usuário e classifique: Criança (até 12 anos), Adolescente (13 a 17), Adulto (18 a 59), Idoso (60 ou mais).

**Passo 1: Entender o Problema**
- Pegar a idade com `input()` e converter pra `int`.
- Usar `if/elif/else` pra verificar a faixa etária.
- Mostrar a classificação.

**Passo 2: Esqueleto do Código**
```python
# Pegar a idade
idade = int(input("Digite sua idade: "))

# Verificar a faixa etária
if idade <= 12:
    print("Criança")
elif idade <= 17:
    print("Adolescente")
elif idade <= 59:
    print("Adulto")
else:
    print("Idoso")
```

**Passo 3: Possíveis Bugs**
- **Erro**: Esquecer a indentação ou os dois pontos (`:`). Exemplo: `if idade <= 12 print("Criança")` dá erro.
- **Solução**: Sempre cheque se o código abaixo de `if/elif/else` tá "afundado" e tem `:`.
- **Erro**: Usar `=` em vez de `<=`. O `=` atribui valor, não compara.

**Código Final**:
```python
idade = int(input("Digite sua idade: "))
if idade <= 12:
    print("Criança")
elif idade <= 17:
    print("Adolescente")
elif idade <= 59:
    print("Adulto")
else:
    print("Idoso")
```

---

### Exercício 6.2: For (Tabuada)
**Enunciado**: Peça um número ao usuário e mostre a tabuada de 1 a 10 usando `for`.

**Passo 1: Entender o Problema**
- Pegar um número com `input()` e converter pra `int`.
- Usar um laço `for` pra multiplicar o número de 1 a 10.
- Mostrar cada linha da tabuada.

**Passo 2: Esqueleto do Código**
```python
# Pegar o número
numero = int(input("Digite um número: "))

# Mostrar a tabuada
print("----- Tabuada do", numero, "-----")
for i in range(1, 11):  # De 1 a 10
    print(numero, "x", i, "=", numero * i)
print("------------------------")
```

**Passo 3: Possíveis Bugs**
- **Erro**: Usar `range(10)` em vez de `range(1, 11)`. O `range(10)` vai de 0 a 9, mas queremos de 1 a 10.
- **Solução**: Sempre cheque o intervalo do `range()`. Pra ir de 1 a 10, use `range(1, 11)`.
- **Erro**: Esquecer de converter o `input()` com `int()`. Isso faz o Python tentar multiplicar texto.

**Código Final**:
```python
numero = int(input("Digite um número: "))
print("----- Tabuada do", numero, "-----")
for i in range(1, 11):
    print(numero, "x", i, "=", numero * i)
print("------------------------")
```

---

### Exercício II: Tabuada com Validação
**Enunciado**: Peça um número de 1 a 10, verifique se é válido, e mostre a tabuada com `for`. Se inválido, mostre erro.

**Passo 1: Entender o Problema**
- Pegar um número e verificar se está entre 1 e 10.
- Se válido, mostrar a tabuada (como no exercício 6.2).
- Se inválido, mostrar mensagem de erro.

**Passo 2: Esqueleto do Código**
```python
# Pegar o número
numero = int(input("Digite um número entre 1 e 10: "))

# Verificar se é válido
if 1 <= numero <= 10:
    print("----- Tabuada do", numero, "-----")
    for i in range(1, 11):
        print(numero, "x", i, "=", numero * i)
    print("------------------------")
else:
    print("Erro: o número deve estar entre 1 e 10!")
```

**Passo 3: Possíveis Bugs**
- **Erro**: Usuário digitar algo que não é número. O `int()` vai travar.
- **Solução temporária**: Peça pra digitar números. Futuramente, usamos `try/except`.
- **Erro**: Condição errada, tipo `numero >= 1 and numero <= 10`. A forma `1 <= numero <= 10` é mais clara.

**Código Final**:
```python
numero = int(input("Digite um número entre 1 e 10: "))
if 1 <= numero <= 10:
    print("----- Tabuada do", numero, "-----")
    for i in range(1, 11):
        print(numero, "x", i, "=", numero * i)
    print("------------------------")
else:
    print("Erro: o número deve estar entre 1 e 10!")
```

---

### Exercício III: Verificador de Senha (Chefão Final)
**Enunciado**: Crie um programa com uma senha pré-definida ("python123"). O usuário tem 3 tentativas pra acertar. Use `while`.

**Passo 1: Entender o Problema**
- Definir a senha no código.
- Usar um `while` pra contar até 3 tentativas.
- Comparar a senha digitada com a correta.
- Mostrar "Acesso concedido" ou "Acesso bloqueado".

**Passo 2: Esqueleto do Código**
```python
# Definir a senha
senha_correta = "python123"
tentativas = 3
contador = 0

# Loop de tentativas
while contador < tentativas:
    senha = input("Digite a senha: ")
    if senha == senha_correta:
        print("Acesso concedido!")
        break  # Sai do loop se acertar
    else:
        contador += 1
        print("Senha incorreta. Tentativas restantes:", tentativas - contador)
if contador == tentativas:
    print("Acesso bloqueado! Tentativas esgotadas.")
```

**Passo 3: Possíveis Bugs**
- **Erro**: Esquecer o `break` no `if`. Sem ele, mesmo acertando a senha, o loop continua.
- **Erro**: Não atualizar o contador. Sem `contador += 1`, o loop pode virar infinito.
- **Solução**: Sempre cheque se o loop tem uma saída (aumentar contador ou `break`).

**Código Final**:
```python
senha_correta = "python123"
tentativas = 3
contador = 0
while contador < tentativas:
    senha = input("Digite a senha: ")
    if senha == senha_correta:
        print("Acesso concedido!")
        break
    else:
        contador += 1
        print("Senha incorreta. Tentativas restantes:", tentativas - contador)
if contador == tentativas:
    print("Acesso bloqueado! Tentativas esgotadas.")
```

---

## Dicas Pro 🕵️
- **Ative o Auto Save**: Vá em "Arquivo > Auto Save" e marque a opção. É como ter um robô que salva sua mochila cósmica antes de cada aventura. Atalho: `Ctrl + K, S`.
- **Evite Nomes de Arquivo com Espaço**: Nomeie seus arquivos como `meu_codigo.py`, não `meu código.py`. Espaços causam erros chatos no Python.
- **Teste em Pequenos Pedaços**: Se seu código tá grande e não funciona, teste só uma parte (ex.: só o `input()`). É como provar o molho antes de jogar na massa.
- **Debugging**: Se o código não roda, leia a mensagem de erro. Ela geralmente diz a linha do problema (ex.: "SyntaxError: unexpected EOF").
- **Pratique**: Copie os códigos da apostila, mude valores (ex.: troque "Peterson" por seu nome) e rode. Isso fixa na cabeça!

---

## Autoavaliação Final 🎯
- Entendeu como usar `print()`, `input()`, e variáveis? [ ] Sim [ ] Não
- Conseguiu fazer pelo menos um exercício rodar no VS Code? [ ] Sim [ ] Não
- Tá mais confiante com `if`, `while`, e `for`? [ ] Sim [ ] Não
- Sabe criar e mexer em listas (ex.: adicionar ou remover itens)? [ ] Sim [ ] Não
- Consegue rodar um código sem erros de indentação ou dois pontos? [ ] Sim [ ] Não
- Se sente pronto pra tentar um exercício sozinho antes de olhar a solução? [ ] Sim [ ] Não

---

## Frase Motivacional Final
Se nada deu certo, respira fundo, releia com calma, ore, chore se precisar, mas nunca desista! É só o começo, e a comunidade da sala está aqui pra te ajudar. Juntos, vamos sobreviver ao Python!

## PRÓXIMO CAPÍTULO: Git e GitHub e o commit sagrado. Até Mais, Vlw.

![Teaser do Próximo Capítulo: Git e GitHub](teaser_github.png)
