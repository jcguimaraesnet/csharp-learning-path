# :page_with_curl: C# Learning Path

ℹ️ Este repositório contém uma proposta de trilha de aprendizado para a linguagem C# em dezoito aulas, contendo links para a documentação da Microsoft e exercícios  práticos.

🧑🏽‍🎓 Essa proposta de aprendizado se destina inicialmente para alunos do Instituto Infnet, uma faculdade focada na área de TI com sede no Rio de Janeiro/Brasil, cujas disciplinas transcorrem em uma janela de espaço de nove semanas (ou dezoito aulas). Eu ficaria feliz se o conteúdo estruturado aqui neste repo for útil para professores e alunos de outras instituições e demais interessados no aprendizado dessa linguagem. 

</br>

# ⭐ Dê uma estrela

Se você estiver usando este repositório para seu aprendizado, por favor, dê uma estrela. Eu ficarei muito feliz com isso. Obrigado :+1:

</br>

## 📌 Learning Path 1.1
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: hello world, visual studio, depuração, variáveis e tipos*

1. [Download e instalação do Visual Studio (VS) Community](https://learn.microsoft.com/pt-br/visualstudio/install/install-visual-studio)
2. [Desabilitar](https://learn.microsoft.com/pt-br/visualstudio/install/install-visual-studio) e [ocultar](https://learn.microsoft.com/pt-br/visualstudio/ide/visual-studio-github-copilot-install-and-states?view=vs-2022#hide-copilot-badge) o Github Copilot
3. [Criar um novo projeto no VS](https://learn.microsoft.com/pt-br/visualstudio/get-started/csharp/tutorial-console)
4. [Solution Explorer e estrutura do projeto (arquivos e pastas)](https://learn.microsoft.com/pt-br/visualstudio/ide/use-solution-explorer?view=vs-2022#solution-explorer-ui)
5. [Classe Program](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/program-structure/)
6. [Método Main estático (ponto de entrada) de aplicações C#](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/program-structure/main-command-line)
7. [Saída de dados no console](https://learn.microsoft.com/pt-br/visualstudio/get-started/csharp/tutorial-console?view=vs-2022)
8. [Uso e definição de namespaces para organização](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/types/namespaces)
9. [Compilar e executar aplicativos no VS](https://learn.microsoft.com/pt-br/visualstudio/get-started/csharp/run-program?view=vs-2022#run-the-program)
10. [Depuração com breakpoints no VS](https://learn.microsoft.com/pt-br/visualstudio/get-started/csharp/tutorial-debugger?view=vs-2022)
11. [Declaração de variáveis implicitamente e explicitamente tipadas (string, inteiro e double)](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/implicitly-typed-local-variables)
12. [Tipo string, concatenação e interpolação](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/strings/)
13. [Tipos numéricos integrais (int)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)
14. [Tipos numéricos de ponto flutuante (float)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types)
15. [Instruções de nível superior](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/program-structure/top-level-statements)

### Para aprofundar
- [Coding Convention](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- [Todos os tipos (internos) do C#](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/built-in-types)

### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/main)
  
<details>
<summary>Exercício em aula</summary>

1. Imprima no console a frase “Hello World”.
2. Compile e execute.
3. Após, crie variáveis atribuindo um nome, uma idade e um salário. Imprima as variáveis no console.
4. Compile e execute.
5. Refaça o mesmo programa com instrução de nível superior
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um aplicativo console Hello World
2. Execute o aplicativo sem depuração
- **`Exercício prático 2`**
1. Execute linha a linha o aplicativo anterior
2. Antes de executar o comando de imprimir no console, altere o texto “Hello World” para conter o seu nome.
3. Continue a execução do programa e verifique a saída no console
- **`Exercício prático 3`**
1. Implemente um aplicativo console que imprima no console seu nome, idade e hobby
2. Crie variáveis para conter os seus dados
3. Crie um breakpoint na linha de código idade
4. Execute linha a linha o seu aplicativo
5. Altere o valor atribuído da variável idade (qualquer outro valor) em tempo de execução
6. Finalize a execução do aplicativo e verifique a saída no console
- **`Exercício prático 4`**
1. No aplicativo anterior, altere o método usado da classe console de WriteLine para Write.
2. Execute o aplicativo console e verifique a saída no console
</details>

</br>

## 📌 Learning Path 1.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: conversões, if-else, switch, erros, operações aritméticas, datetime*

1. [Definindo a cultura padrão de um aplicativo console](https://learn.microsoft.com/pt-pt/dotnet/fundamentals/runtime-libraries/system-globalization-cultureinfo#culture-and-application-domains)
2. [Entrada de dados](https://learn.microsoft.com/pt-br/dotnet/api/system.console.readline)
3. [Conversões com classes auxiliares (classe Convert, Parse, TryParse)](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/types/how-to-convert-a-string-to-a-number)
4. [Formatação de tipos numéricos](https://learn.microsoft.com/pt-br/dotnet/standard/base-types/standard-numeric-format-strings)
5. [Definindo uma constante](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/const)
6. [Instruções de seleção - if, if-else e switch](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/statements/selection-statements)
7. [Operadores aritméticos](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/arithmetic-operators)
8. [Operadores de comparação](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/comparison-operators)
9. [Operadores lógicos](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/boolean-logical-operators)
10. [Manipulando datas](https://learn.microsoft.com/pt-br/dotnet/standard/datetime/how-to-use-dateonly-timeonly)
11. [TryParseExact para conversão de datas](https://learn.microsoft.com/pt-br/dotnet/api/system.datetime.tryparseexact)


### Para aprofundar
- [Todos operadores em C# (aritméticos, lógicos e comparação)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/)
- [Correspondência de padrões (técnica funcional)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/patterns)

### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-1_2)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de funcionários de uma hamburgueria (apenas 1 funcionário)
2. Formulário de leitura de dados pessoais: nome, sobrenome e salário
3. Exiba o nome completo em caixa alta
4. Compile e execute
5. Defina uma constante com o total de horas padrão mensal
6. Calcule e imprima o valor hora do funcionário dividindo o salário pelo total de horas padrão mensal 
7. Compile e execute
8. Adicione a leitura da data de nascimento ao formulário
9. Imprima no console se a pessoa é menor aprendiz (menor que 18)
10. Compile e execute
11. Exiba a categoria de classe de renda (A, B, C, D e E) por faixa de renda (<=1.5k, <=5k, <=10k, <=20k, +20k)
12. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. O programa deve calcular o total de um pedido apenas uma vez por execução do programa
3. Imprima duas opções de de produto da loja (ex: 1 - beef burguer e 2 - fish burguer)
4. Considere que o produto 1 e 2 tenham valor fixo de R$ 50,00 e R$ 60,00 respectivamente
4. Leia a opção de produto desejado pelo usuário
5. Leia a quantidade desejada, calcule e imprima o total do pedido
6. Compile e execute
- **`Exercício prático 2`**
1. Calcule o IMC de uma pessoa (peso / (altura * altura))
2. Imprima no console as classificações de acordo com a OMS (abaixo do peso, normal, sobrepeso, obesidade)
3. Compile e execute
- **`Exercício prático 3`**
1. Calcule e imprima a média escolar de aluno com base em três notas (nome, nota1, nota2, nota3)
2. Informe a situação atual do aluno (reprovado < 5; aprovado ≥ 7; recuperação 5 ≥ e < 7)
3. Compile e execute
- **`Exercício prático 4`**
1. Conversor de temperatura de celsius para fahrenheit 
2. Leia temperatura em celsius e imprima a temperatura em fahrenheit
3. Compile e execute
</details>


</br>

## 📌 Learning Path 2.1
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: arrays, repetição, menu, enum*

1. [Uso de matrizes (arrays)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/arrays#single-dimensional-arrays)
2. [Matrizes de tipo implícito](https://www.notion.so/csharp-course-outline-1836275169d480208413cfd2c6ea2b1c?pvs=21)
3. [Instrução for](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/statements/iteration-statements#the-for-statement)
4. [Instrução foreach](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/statements/iteration-statements#the-foreach-statement)
5. [Instrução while](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/statements/iteration-statements#the-while-statement)
6. [Instrução do..while](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/statements/iteration-statements#the-do-statement)
7. [Enumeração](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/enum)

### Para aprofundar
- [Operador de intervalo para matrizes](https://learn.microsoft.com/pt-br/dotnet/csharp/tutorials/ranges-indexes)
- [Usando Enum como sinalizador de bits (múltiplos valores)](https://learn.microsoft.com/pt-br/dotnet/api/system.enum.hasflag?view=net-9.0#exemplos)

### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-2_1)

<details>
<summary>Exercício em aula</summary>

1. Defina um array de horas extras com 12 posições, itere o array e preencha com um valor aleatório (for)
2. Imprima a soma de horas extras
3. Compile e execute
4. Defina um array com o nome dos dias da semana e imprima cada dia no console (foreach)
5. Compile e execute
6. Leia um numero inteiro e implemente uma contagem regressiva até zero (while)
7. Imprima o número, decremente o número e aguarde 1 segundo
8. Compile e execute
9. Defina um enum com os dias da semana e imprima cada dia no console (enum)
10. Compile e execute
11. Implemente um programa de caixa registradora para pedidos de uma hamburgueria (do … while)
12. Imprima um menu com as opções: beef burger e fish burger (com seus respectivos valores)
13. Leia a quantidade de hamburgueres desejados, calcule e imprima o total do pedido
14. Ofereça uma opção para reiniciar ou sair
15. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. Imprima uma lista de menu com opções de produto da loja
3. Leia a opção de produto desejado pelo usuário
4. Leia a quantidade desejada, calcule e imprima o total do pedido
5. Realize um desconto de 50% no total calculado apenas para o quinto pedido do dia
6. Ofereça uma opção para reiniciar a caixa registradora e outra opção para sair
7. Compile e execute
- **`Exercício prático 2`**
1. Implemente um pequeno jogo para acertar cara ou coroa
2. Saia do programa somente quando o usuário acertar
3. Use enumeration no seu programa
4. Compile e execute
- **`Exercício prático 3`**
1. Defina um array de inteiro com 5 números aleatórios e fixos
2. Exiba o array na ordem inversa ao que foi definido
3. Compile e execute
- **`Exercício prático 4`**
1. Defina um array de float com 4 posições, leia 4 notas escolares, calcule a média, a maior e a menor nota 
2. Imprima a média das notas, a maior e a menor nota
3. Compile e execute
</details>


</br>

## 📌 Learning Path 2.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Programação orientada a objetos (introdução)*
> </br> **Leitura do TP1**

1. [Adicionando um pacote do nuget: Colorful.Console](https://github.com/tomakita/Colorful.Console?tab=readme-ov-file#convert-text-to-ascii-art-using-a-default-font)
2. [Classe - definição de um tipo](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/types/classes)
3. [Objeto - instância de tipos](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/object-oriented/objects)
4. [Níveis de acessibilidade](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/accessibility-levels)
5. [Método](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/methods)
6. [Campo](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/fields)
7. [Propriedades auto implementadas](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/properties)
8. [Construtor](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/constructors)
9. [Lançando exceções para valores inválidos (string.IsNullOrWhiteSpace e throw new)](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/exceptions/creating-and-throwing-exceptions)
10. [Tratamento de erros com try-catch](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/exceptions/)


### Para aprofundar
- [Exceções mais comuns (tanto para capturar, quanto para utilizar)](https://learn.microsoft.com/pt-br/dotnet/standard/exceptions/#common-exceptions)
- [Classes parciais](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/partial-classes-and-methods)
- [Inicializando objetos (4 formas diferentes)](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/types/classes#constructors-and-initialization)
- [Struct para pequenos tipos de dados com pouco comportamento (imutáveis)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/struct)
- [Record para tipos focados em armazenamento de dados sem comportamento](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/types/records)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-2_2)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de funcionários de uma hamburgueria (apenas um funcionário)
2. Crie apenas 1 (um) objeto do tipo funcionário com valores fixos (não leia do console)
3. Formulário de leitura de dados pessoais: nome, sobrenome e salário
4. Aceite apenas salário maior que zero
5. Capture as exceções que podem ocorrer, exiba mensagem de erro, encerre ou reinicie o programa
6. Exiba o nome completo em caixa alta
7. Exiba o valor da hora extra. Regra: Salario / 160 * 40%
8. Compile e execute
9. Adicione a leitura da data de nascimento ao formulário
10. Imprima no console se a pessoa é menor aprendiz (menor que 18)
11. Compile e execute
12. Exiba a categoria de classe de renda (A, B, C, D e E) por faixa de renda (<=1.5k, <=5k, <=10k, <=20k, +20k)
13. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. O programa deve calcular o total de um pedido apenas uma vez por execução do programa
3. Imprima uma lista de menu com duas opções de produto da loja (exemplo: beef burger e fish burguer)
4. Leia a opção de produto desejado pelo usuário
5. Leia a quantidade desejada, calcule e imprima o total do pedido
6. Aceite apenas quantidade maior que zero
7. Capture as exceções que podem ocorrer, exiba mensagem de erro, encerre ou reinicie o programa
8. Calcule um desconto de 10% para total de pedido acima de 200 reais
9. Compile e execute
- **`Exercício prático 2`**
1. Calcule o IMC de uma pessoa (peso / altura)
2. Imprima no console as classificações de acordo com a OMS (abaixo do peso, normal, sobrepeso, obesidade)
3. Compile e execute
- **`Exercício prático 3`**
1. Calcule e imprima a média escolar de aluno com base em três notas (nome, nota1, nota2, nota3)
2. Informe a situação atual do aluno (reprovado < 5; aprovado ≥ 7; recuperação 5 ≥ e < 7)
3. Compile e execute
- **`Exercício prático 4`**
1. Conversor de temperatura de celsius para fahrenheit 
2. Leia temperatura em celsius e imprima a temperatura em fahrenheit
3. Compile e execute
</details>


</br>


## 📌 Learning Path 3.1
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: C# avançado (tipos anuláveis, sobrecarga (overloading), métodos de extensão, parâmetros opcionais e nomeados, arrow function, required, init, readonly, operador ternário)


1. [Tipos de referência anuláveis](https://learn.microsoft.com/pt-br/dotnet/csharp/nullable-references)
2. [Parâmetros nomeados](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/named-and-optional-arguments#named-arguments)
3. [Parâmetros opcionais](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/named-and-optional-arguments#optional-arguments)
4. [Sobrecarga de métodos (overloading)](https://learn.microsoft.com/en-us/dotnet/standard/design-guidelines/member-overloading)
5. [Métodos de extensão](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/how-to-create-a-new-method-for-an-enumeration)
6. [Arrow function ou expression body definition](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/statements-expressions-operators/expression-bodied-members#methods)
7. [Membros (prop e métodos) estáticos](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/static-classes-and-static-class-members)
8. [Acessador init para propriedade verificável e imutável (propriedade continua opcional)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/readonly#readonly-field-example)
9. [Propriedade required como obrigatória no construtor ou inicialização do objeto](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/required)
10. [Campos readonly como obrigatório no construtor ou declaração](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/readonly#readonly-field-example)
11. [Operador Ternário (?:)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/conditional-operator)


### Para aprofundar
- [Clean Code para C# (thangchung)](https://github.com/thangchung/clean-code-dotnet)
- [Q&A sobre temas avançados de .NET e C# (Stack Overflow - Por Maniero)](https://github.com/maniero/SOpt/blob/master/CSharp/Conceptual.md)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-3_1)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de funcionários de uma hamburgueria (apenas um funcionário)
2. Crie apenas 1 (um) objeto do tipo funcionário com valores fixos (não leia do console)
3. Formulário de leitura de dados pessoais: nome, sobrenome e salário
4. Aceite apenas nome e sobrenome preenchido (readonly, required, init, ternário)
5. Aceite apenas salário maior que zero (readonly, required, init, ternário)
6. Capture as exceções que podem ocorrer, exiba mensagem de erro, encerre ou reinicie o programa
7. Exiba o nome completo em caixa alta (arrow function)
8. Exiba o valor da hora extra. Regra: Salario / 160 * 40%
9. Compile e execute
10. Exiba o valor da hora extra com opção de adicional noturno de 60% (parametro nomeado, método sobrecarga ou parâmetro opcional)
11. Compile e execute
12. Adicione a leitura da data de nascimento ao formulário
13. Aceite data nascimento como opcional (tipo anulável)
14. Aceite data nascimento menor que a data atual (set verificável, ternário)
15. Imprima no console se a pessoa é menor aprendiz (menor que 18)
16. Compile e execute
17. Exiba a categoria de classe de renda (A, B, C, D e E) por faixa de renda (<=1.5k, <=5k, <=10k, <=20k, +20k)
18. Compile e execute
19. Crie um método de extensão que enquadre as classificações D e E como elegível ao bolsa família
20. Exiba se o funcionário está elegível ou não ao bolsa família
21. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. O programa deve calcular o total de um pedido apenas uma vez por execução do programa
3. Imprima uma lista de menu com duas opções de produto da loja (exemplo: beef burger e fish burguer)
4. Leia a opção de produto desejado pelo usuário
5. Leia a quantidade desejada, calcule e imprima o total do pedido
6. Aceite apenas quantidade maior que zero
7. Capture as exceções que podem ocorrer, exiba mensagem de erro, encerre ou reinicie o programa
8. Calcule um desconto de 10% para total de pedido acima de 200 reais
9. Compile e execute
10. `Use algum ou alguns dos recursos demonstrados nesta aula`
- **`Exercício prático 2`**
1. Calcule o IMC de uma pessoa (peso / altura)
2. Imprima no console as classificações de acordo com a OMS (abaixo do peso, normal, sobrepeso, obesidade)
3. Compile e execute
4. `Use algum ou alguns dos recursos demonstrados nesta aula`
- **`Exercício prático 3`**
1. Calcule e imprima a média escolar de aluno com base em três notas (nome, nota1, nota2, nota3)
2. Informe a situação atual do aluno (reprovado < 5; aprovado ≥ 7; recuperação 5 ≥ e < 7)
3. Compile e execute
4. `Use algum ou alguns dos recursos demonstrados nesta aula`
- **`Exercício prático 4`**
1. Conversor de temperatura de celsius para fahrenheit 
2. Leia temperatura em celsius e imprima a temperatura em fahrenheit
3. Compile e execute
4. `Use algum ou alguns dos recursos demonstrados nesta aula`
</details>


</br>

## 📌 Learning Path 3.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: coleções, LINQ*

1. [Coleções indexáveis: List<T>](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/collections#indexable-collections)
2. [Coleções de pares chave/valor: Dictionary<TKey, TValue>](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/collections#keyvalue-pair-collections)
3. [Quando usar coleções genéricas](https://learn.microsoft.com/pt-br/dotnet/standard/collections/when-to-use-generic-collections)
4. [LINQ (Consulta Integrada à Linguagem) e consultas mais comuns](https://learn.microsoft.com/pt-br/dotnet/csharp/linq/get-started/introduction-to-linq-queries#classification-table)
5. [LINQ: Sintaxe de query  (declarativa)](https://learn.microsoft.com/pt-br/dotnet/csharp/linq/get-started/query-expression-basics#starting-a-query-expression)
6. [LINQ: Sintaxe de método (imperativa)](https://learn.microsoft.com/pt-br/dotnet/csharp/linq/standard-query-operators/filtering-data)

### Para aprofundar
- [Visão geral sobre coleções do .NET](https://learn.microsoft.com/pt-br/dotnet/standard/collections/)
- [Introdução a consultas LINQ](https://learn.microsoft.com/pt-br/dotnet/csharp/linq/get-started/introduction-to-linq-queries)
- [Todas as coleções Genéricas - System.Collections.Generic](https://learn.microsoft.com/pt-br/dotnet/api/system.collections.generic)
- [Todas as coleções não genéricas (Object) - System.Collections](https://learn.microsoft.com/pt-br/dotnet/api/system.collections)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-3_2)

<details>
<summary>Exercício em aula</summary>

0. Implemente um exemplo simples de soma (LINQ), a partir de uma coleção fixa de inteiros
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (vários funcionários)
2. Apresente um menu com três opções: adicionar funcionário, calcular folha e sair
3. Opção 1: ler os dados do funcionário: nome e salário
4. Opção 2: Calcular o total, mínimo, máximo e média dos salários
5. Opção 3: Sair do programa
6. Compile e execute
7. Adicione o campo identidade (ou cpf) do funcionário e use um dicionário para evitar duplicidade
8. Compile e execute
9. Crie um menu adicional para pesquisar funcionários com salários maiores que R$5.000,00
10. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Crie uma coleção com cinco nome de frutas (nomes fixos no programa)
2. Filtre e imprima os nomes de frutas que começam com a letra “b” ou “B”
3. Compile e execute
- **`Exercício prático 2`**
1. Crie uma coleção que contenha frutas do tipo crítica e não cítricas (fixos no programa)
2. Filtre e imprima apenas as frutas do tipo cítricas
3. Compile e execute
- **`Exercício prático 3`**
1. Crie uma coleção que contenha 10 números inteiros (fixos no programa)
2. Imprima somente os números ímpares
3. Compile e execute
- **`Exercício prático 4`**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. Apresente um menu com duas opções de produto e seus valores (exemplo: beef burger e fish burguer)
3. Leia a opção de produto desejado pelo usuário
4. Leia a quantidade desejada e apresente o menu novamente
5. Ofereça também um item de menu para calcular o valor total de todos os pedidos
6. E ofereça um outro item de menu para sair do programa
7. Compile e execute

</details>

</br>

## 📌 Learning Path 4.1
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Programação orientada a objetos (encapsulamento)*

1. [POO - Encapsulamento 1](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/tutorials/oop)
2. [POO - Encapsulamento 2 (deviq)](https://deviq.com/principles/encapsulation)
3. [Padrão Modelo de domínio](https://martinfowler.com/eaaCatalog/domainModel.html)
4. [Padrão (ou antipadrão) Modelo de domínio anêmico](https://martinfowler.com/bliki/AnemicDomainModel.html)


### Para aprofundar
- [Princípios populares de desenvolvimento - Regra do escoteiro](https://deviq.com/principles/boy-scout-rule)
- [Princípios populares de desenvolvimento - KISS (Keep It Simple, Stupid)](https://deviq.com/principles/keep-it-simple)
- [Princípios populares de desenvolvimento - YAGNI (You Ain't Gonna Need It - Você não vai precisar)](https://deviq.com/principles/yagni)
- [Princípios populares de desenvolvimento - DRY (Don't Repeat Yourself)](https://deviq.com/principles/dont-repeat-yourself)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-4_1)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de conta bancária com operações de depósito e saque
2. Simule algumas operações de depósito e saque
3. Ao final exiba o valor do saldo da conta bancária
4. Certifique-se de manter o saldo inacessível para alterações
5. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de um funcionário de uma loja (tema do aluno)
2. Apresente um menu com três opções: adicionar funcionário, aumentar e exibir salario, e sair
3. Opção 1: ler os dados do funcionário: nome, cargo e salário (regra: salário maior que zero)
4. Opção 2: Aumentar  e exibir o salário dos funcionários (regra → 20% para gerente e 10% para os demais)
6. Opção 3: Sair do programa
7. Use os princípios de encapsulamento, definindo a visibilidade adequada para os membros da classe
8. Compile e execute
- **`Exercício prático 2`**
1. Simule operações de transações com um cartão de crédito (duas ou mais transações de compra)
2. Antes de simular as operações, defina um limite inicial de R$ 5000,00
3. Imprima a fatura com o limite atual
4. Use os princípios de encapsulamento, definindo a visibilidade adequada para os membros da classe
5. Compile e execute
- **`Exercício prático 3`**
1. Simule um sistema de fidelidade de pontos (duas ou mais transações)
2. Antes de simular as operações, defina uma pontuação inicial de 50 pontos
3. Cada transação deve ser convertida em dólar. Cada dólar gera 1 ponto.
4. Simule uma operação de resgate de 10 pontos.
5. Imprima na tela o extrato com a pontuação atual
6. Use os princípios de encapsulamento, definindo a visibilidade adequada para os membros da classe
7. Compile e execute
- **`Exercício prático 4`**
1. Simule um carrinho de compras de um ecommerce
2. Simule duas ou mais operações de “adicionar itens ao carrinho” informando produto, preço e qtde
3. Crie uma propriedade que contenha o total do pedido
4. Imprima na tela o valor total do pedido
5. Use os princípios de encapsulamento, definindo a visibilidade adequada para os membros da classe
6. Compile e execute
</details>

</br>

## 📌 Learning Path 4.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Programação orientada a objetos (herança)*
> </br> **Leitura do TP2**

1. [O que é uma herança - relacionamento do tipo “é um” (ex: garçon "é um" funcionário)](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/tutorials/inheritance#background-what-is-inheritance)
2. [Conceito de classe base e classe derivada](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/tutorials/inheritance#background-what-is-inheritance)
3. [Palavra-chave 'base' para herança explícita de construtor (não existe herança implícita de construtor)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/base)
4. [Visibilidade 'protected'](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/protected)
5. [Palavra-chave 'sealed' para impedir herança](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/sealed)
6. [Sobrecarregando métodos](https://learn.microsoft.com/pt-br/dotnet/standard/design-guidelines/member-overloading)


### Para aprofundar
- [Ferramenta para modelar diagrama de classes (Draw.io)](https://app.diagrams.net)
- [Ferramenta para modelar diagrama de classes (Lucidchart)](https://lucid.app/lucidchart/706e4961-b5e1-4f87-b000-3037506405bb/edit?invitationId=inv_559bf1e0-50db-4c2c-9e5f-0482cc331425&page=azYL66cQbwSa#)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-4_2)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie três publicações atribuindo valores fixos e aleatórios
8. Compile e execute
9. Crie um método `protegido` na classe base para exibir as informações básicas (ex: ExibirDadosBasicos)
10. Crie um método sem parâmetros para exibir todas as informações (básicas e adicionais) nas classes derivadas (cor padrão)
11. Crie um método `com sobrecarga` do método anterior para exibir as informações em cores (parâmetro ConsoleColor)
12. Exiba no console os dados de cada publicação em cores diferentes
13. Compile e execute

</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (colecao de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do valor faturamento mes anterior
7. Crie um método `protegido` na classe base para exibir as informações básicas (Ex. ExibirDadosBasicos)
8. Crie métodos nas classes derivadas para exibir as informações básicas e adicionais (use o método protegido)
9. Crie três tipos de funcionário, atribuindo valores fixos e aleatórios (use herança de construtor)
10. Exiba os dados de todos os funcionários
11. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Crie um método `protegido` na classe base para calcular o salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base com os dados básicos do funcionário
4. Compile e execute
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. O garçom possui calculo de comissão (regra: salario base mensal * mesas / 100)
3. O supervisor possui calculo de adicional noturno (regra: madrugada 20% do salario base mensal e restante 10%)
4. O caixa possui calculo de bonus (regra: valor faturamento mes anterior * 0.01%)
5. Crie um método privado nas classes derivadas para calcular o salário total (salario base + adicional)
6. Exiba o salario total dos funcionários junto com os dados `adicionais`
7. Compile e execute
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>

</br>

## 📌 Learning Path 5.1
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Programação orientada a objetos (polimorfismo)*

1. [O que é polimorfismo](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/object-oriented/polymorphism)
2. [Permitindo a sobrescrita de membros na classe base (virtual)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/virtual)
3. [Sobrescrevendo membros (da classe base) na classe derivada (override)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/override)
4. [Object e herança implícita para classes](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/tutorials/inheritance#implicit-inheritance)
5. [Usando método ToString em classes herdadas implicitamente](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/how-to-override-the-tostring-method)


### Para aprofundar
- [Clean architecture dotnet](https://github.com/thangchung/clean-architecture-dotnet)
- [Exemplo de solução .NET com arquitetura evolucionária (em 4 estágios)](https://github.com/evolutionary-architecture/evolutionary-architecture-by-example)
- [Exemplo de modelagens de objetos/classes para problemas reais](https://github.com/ashishps1/awesome-low-level-design?tab=readme-ov-file#-low-level-design-interview-problems)
- [Exemplos de projetos reais completos](https://github.com/thangchung/awesome-dotnet-core?tab=readme-ov-file#sample-projects)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-5_1)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie três publicações atribuindo valores fixos e aleatórios
8. Compile e execute
9. Sobrescreva o método da classe base para exibir também as informações adicionais de cada tipo de publicação
10. Compile e execute
11. Simule cadastros de mais tipos de publicação com valores fixos e aleatórios em uma coleção
12. Exiba as informações de todas as publicações no console (use polimorfismo)
13. Compile e execute
14. Experimente usar o método ToString no lugar do método que exibe as informações
15. Compile e execute

</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (colecao de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do valor faturamento mes anterior
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Crie um método `virtual` na classe base para exibir as informações básicas
9. Crie métodos `override` nas classes derivadas para exibir informações básicas e adicionais
10. Exiba os dados de todos os funcionários (use polimorfismo)
11. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Crie um método `virtual` na classe base para calcular o salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base com os dados básicos do funcionário
4. Compile e execute
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. O garçom possui calculo de comissão (regra: salario base mensal * mesas / 100)
3. O supervisor possui calculo de adicional noturno (regra: noite → 10% e madruga 20% salario base mensal)
4. O caixa possui calculo de bonus (regra: valor faturamento mes anterior * 0.01%)
5. Crie um método `override` para calcular o salário total (invoque o método virtual da classe base)
6. Exiba o salario total dos funcionários (salario base + adicional) entre os dados `básicos`
7. Exibia também o tipo do funcionário entre os dados `básicos`
8. Compile e execute
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>


</br>

## 📌 Learning Path 5.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Programação orientada a objetos (abstração)*

1. [O que é abstração](https://pt.wikipedia.org/wiki/Abstra%C3%A7%C3%A3o_(ci%C3%AAncia_da_computa%C3%A7%C3%A3o))
2. [Abstract para classe](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/abstract-and-sealed-classes-and-class-members#abstract-classes-and-class-members)
3. [Abstract para métodos e membros de uma classe](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/abstract)


### Para aprofundar
- [.NET Awesome (Libs & Tools)](https://github.com/quozd/awesome-dotnet)
- [.NET Core Awesome (Libs & Tools)](https://github.com/thangchung/awesome-dotnet-core)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-5_2)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Compile e execute
9. Defina a classe base como abstrata
10. Crie um método abstrato para imprimir informações adicionais
11. Crie um método que imprima todos as informações básicas de qualquer tipo de publicação e invoke o método abstrato de informações adicionais
12. Implemente o método de imprimir informações adicionais para exibir as informações adicionais de cada tipo de publicação.
13. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (colecao de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do valor faturamento mes anterior
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Crie um método `abstrato` na classe base relativo as informações adicionais
9. Crie um método na classe base para exibir informações básicas e adicionais `(invoke o método abstrato)`
10. Implemente o método abstrato nas classes derivadas para exibir adicionais
11. Use o conceito de abstração em classe e método neste exercício
12. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Crie um método na classe base para calcular o salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base de cada um dos três funcionários entre as informações básicas
4. Compile e execute
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. Defina na classe base um método abstrato para calcular salario adicional
3. Crie um método na classe base para calcular o salário total (salário base + adicional)
4. Implemente o método abstrato de salário adicional para cada funcionário
5. O garçom possui calculo de comissão (regra: salario base mensal * mesas / 100)
6. O supervisor possui calculo de adicional noturno (regra: noite → 10% e madruga 20% salario base mensal)
7. O caixa possui calculo de bonus (regra: valor faturamento mes anterior * 0.01%)
8. Exiba o salário adicional e salário total entre as informações básicas
9. Compile e execute
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>


</br>

## 📌 Learning Path 6.1
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Programação orientada a objetos (interface)*

1. [O que é uma interface](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/interface)
2. [Interface Segregation Principle (ISP)](https://deviq.com/principles/interface-segregation)
3. [Exemplo de uso de interface com ISP - relacionamento do tipo "faz algo" (ex: garçom pode fechar pedido)](https://github.com/richielybmp/solid-design-principles-in-c-sharp/tree/master/ISP.InterfaceSegregationPrinciple)
4. [Usando o tipo Type para filtrar (LINQ OfType, LINQ Where, GetType, typeof)](https://learn.microsoft.com/pt-br/dotnet/api/system.linq.enumerable.oftype)


### Para aprofundar
- [Princípios SOLID com exemplos C#](https://github.com/richielybmp/solid-design-principles-in-c-sharp)
- [Implementação padrão em interfaces](https://learn.microsoft.com/pt-br/dotnet/csharp/advanced-topics/interface-implementation/default-interface-methods-versions)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-6_1)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Compile e execute
9. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
10. Exiba as informações (básicas e adicionais) de todos os funcionários
11. Compile e execute
12. `Crie uma interface IEmprestavel e adicione capacidades para emprestar, devolver e verificar disponibilidade (somente para Livro e Revista)`
13. `Itere sobre os publicações emprestáveis (somente emprestáveis) e e exiba os sesu dados`
14. `Compile e execute`
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (colecao de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do valor faturamento mes anterior
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. `Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)`
9. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Crie um método na classe base para calcular o salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base de cada um dos três funcionários entre as informações básicas
4. `Crie uma interface IDissidioElegivel e adicione a capacidade de acrescentar mais 10% ao Valor Hora de todos os funcionários elegíveis (somente supervisor e caixa)`
5. `Dica: Se necessário, altere a acessibilidade de membros da classe base para protected`
6. `Compile e execute`
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. `Itere sobre cada funcionário, e faça os três passos abaixo:`
3. `1 - Exiba o nome, tipo funcionário e salário base`
4. `2 - Acrescente o dissídio (somente aos elegíveis)`
5. `3 - Exiba o salário base novamente com dissídio (somente aos elegíveis)`
6. `Compile e execute`
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>


</br>

## 📌 Learning Path 6.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Testes de unidade com C#*
> </br> **Leitura do TP3**

1. [Os vários tipos de testes](https://learn.microsoft.com/pt-br/dotnet/core/testing/)
2. [Os pacotes mais populares para teste de unidade](https://learn.microsoft.com/pt-br/dotnet/core/testing/unit-testing-with-dotnet-test)
3. [Padrão AAA de teste(Arrange-Act-Assert)](https://deviq.com/testing/arrange-act-assert)
4. [Gerenciador de testes no VS](https://learn.microsoft.com/pt-br/visualstudio/test/run-unit-tests-with-test-explorer?view=vs-2022#run-tests-in-test-explorer)
5. [Tipos de projeto de teste de unidade no VS](https://learn.microsoft.com/pt-br/visualstudio/test/create-a-unit-test-project?view=vs-2022#to-create-a-unit-test-project)

### Para aprofundar
- [Melhores práticas de teste de unidade](https://learn.microsoft.com/pt-br/dotnet/core/testing/unit-testing-best-practices)
- [Pirâmide de testes](https://deviq.com/testing/testing-pyramid)

### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-6_2)

<details>
<summary>Exercício em aula</summary>

1. Crie um novo projeto de teste usando xUnit e referencie o projeto Classroom
1. Crie testes de unidade para a classe Livro
2. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Crie um novo projeto de teste usando xUnit e referencie o projeto Pratical_1
2. Crie testes de unidade para a classe Funcionario
3. Compile e execute os testes no Gerenciador de Testes
- **`Exercício prático 2`**
1. Crie um novo projeto de teste usando xUnit e referencie o projeto Pratical_2
2. Crie testes de unidade para a classe Garçon
3. Compile e execute os testes no Gerenciador de Testes
- **`Exercício prático 3`**
1. Crie um novo projeto de teste usando xUnit e referencie o projeto Pratical_3
2. Crie testes de unidade para a classe Supervisor
3. Compile e execute os testes no Gerenciador de Testes
- **`Exercício prático 4`**
1. Crie um novo projeto de teste usando xUnit e referencie o projeto personalizado de acordo com o tema da sua loja
2. Crie testes de unidade para as classes do tema da sua loja
3. Compile e execute
</details>

</br>


## 📌 Learning Path 7.1
### Tópicos principais

> [!IMPORTANT]
> *Assuntos cobertos: Programação orientada a objetos (relacionamento entre objetos)*

1. [Agregação - Agrega, existem separadamente, relacionamento "tem um"](https://learning.oreilly.com/library/view/hands-on-object-oriented-programming/9781788296229/a68cdc1a-4eb8-4ce7-b689-70e915ea5abd.xhtml)
2. [Composição - Compõe, dependem um do outro (gerencia ciclo de vida), relacionamento "parte de"](https://learning.oreilly.com/library/view/hands-on-object-oriented-programming/9781788296229/3b1f6c0e-8884-448d-acf2-3a5546acd286.xhtml)
3. [Prefira composição em vez de herança](https://pt.stackoverflow.com/questions/11378/%C3%89-correto-dar-maior-prefer%C3%AAncia-a-composi%C3%A7%C3%A3o-do-que-heran%C3%A7a)


### Para aprofundar
- [POO e os tipos de associação entre objetos](https://www.macoratti.net/20/09/c_tipassoc1.htm)
- [DDD - Catálogo de padrões para domínio complexo](https://github.com/Sairyss/domain-driven-hexagon)
- [DDD - Microserviços orientado à DDD](https://learn.microsoft.com/pt-br/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/ddd-oriented-microservice)

### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-7_1)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Compile e execute
9. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
10. Exiba as informações (básicas e adicionais) de todos os funcionários
11. Compile e execute
12. `Crie uma nova classe Biblioteca (nome e localizacao) e uma agregação com publicação`
13. `Liste todas as publicações (por tipo) a partir da classe Biblioteca`
14. `Compile e execute`
15. `Crie uma nova classe Secao (Titulo, Resumo) como composição de Publicação`
16. `Simule seções para cada publicação`
17. `Ao listar as publicações, exiba também as seções da publicação`
18. `Compile e execute`
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (colecao de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do valor faturamento mes anterior
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. `Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)`
9. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Crie um método na classe base para calcular o salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base de cada um dos três funcionários entre as informações básicas
4. `Crie uma opção para adicionar dependente (composição) a cada funcionário (nome e data nascimento)`
5. `Ofereça um auxílio dependente aos funcionários, no valor de 500 reais para cada dependente`
6. `Exiba o valor do salário base, do auxílio dependente e do valor total do salário (base + auxilio)`
. `Compile e execute`
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. `Crie uma classe (nome: Hamburgueria) para gerenciar os funcionários (agregação)`
3. `Liste todas os funcionários (por tipo) a partir da classe Hamburgueria`
4. `Compile e execute`
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>




## 📌 Learning Path 7.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Leitura e escrita em arquivos (streams/fluxos)*

1. [Arquivos e diretórios](https://learn.microsoft.com/pt-br/dotnet/standard/io/#files-and-directories)
2. [Exemplos de como se referir a um arquivo](https://learn.microsoft.com/pt-br/dotnet/standard/io/file-path-formats#example-ways-to-refer-to-the-same-file)
3. [Classe Environment - CurrentDirectory, Environment.SpecialFolder.MyDocuments](https://learn.microsoft.com/pt-br/dotnet/api/system.environment#examples)
4. [Classe File e StreamReader/StreamWriter](https://learn.microsoft.com/pt-br/dotnet/api/system.io.file#examples)
5. [StreamReader/StreamWriter](https://learn.microsoft.com/pt-br/dotnet/api/system.io.streamreader.readline#exemplos)
6. [StreamReader - Leitura do início ao fim](https://learn.microsoft.com/pt-br/dotnet/standard/io/how-to-read-text-from-a-file#read-a-file)


### Para aprofundar
- [E/S de arquivo e de fluxo - Visão Geral](https://learn.microsoft.com/pt-br/dotnet/standard/io/)
- [Exceções comuns em operações de E/S](https://learn.microsoft.com/pt-br/dotnet/standard/io/handling-io-errors#exception-handling-in-io-operations)
- [Append - Acrescentar dados em arquivo](https://learn.microsoft.com/pt-br/dotnet/standard/io/how-to-open-and-append-to-a-log-file)

### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-7_2)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Compile e execute
9. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
10. Exiba as informações (básicas e adicionais) de todos os funcionários
11. Compile e execute
12. `Crie uma nova classe Biblioteca (nome e localizacao) e uma agregação com publicação`
13. `Crie um método na classe Biblioteca para gerar um relatório (txt) com os dados básicos de todas as publicações`
14. `Crie um método na classe Biblioteca para exibir o relatório (txt) caso exista`
15. `Use stream (fluxo) para gravar e ler os dados`
16. `Compile e execute`
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (colecao de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do valor faturamento mes anterior
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
9. `Crie uma classe (nome: Hamburgueria) para gerenciar os funcionários (agregação)`
10. Compile e execute
- **`Exercício prático 2`**
1. `Evolua o exercício anterior com os próximos passos`
2. `Crie um método para gerar um relatório (txt) com os dados básico dos funcionários`
3. `Use stream (fluxo) para gravar os dados`
4. Compile e execute
- **`Exercício prático 3`**
1. `Evolua o exercício anterior com os próximos passos`
2. `Crie um método para exibir o relatório (txt) caso exista`
3. `Use stream (fluxo) para ler os dados`
4. `Compile e execute`
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>

</br>


## 📌 Learning Path 8.1
### Tópicos principais

> [!IMPORTANT]
> *Assuntos cobertos: Leitura e escrita em arquivos (ReadAllLines, WriteAllLines, string.Split)*
> </br> **Leitura do AT**

1. [Escrita de array de strings em arquivo - File.WriteAllLines](https://learn.microsoft.com/pt-br/dotnet/api/system.io.file.writealllines)
2. [Leitura de arquivo para array de strings - File.ReadAllLines](https://learn.microsoft.com/pt-br/dotnet/api/system.io.file.readalllines)
3. [Como separar strings em array usando Split](https://learn.microsoft.com/pt-br/dotnet/csharp/how-to/parse-strings-using-split#stringsplit-examples)


### Para aprofundar
- [C# Language Roadmap](https://github.com/gridlocdev/csharp-learning-roadmap)
- [.NET Developer Roadmap (por phongnguyend)](https://github.com/phongnguyend/.net-developer-roadmap)
- [.NET Developer Roadmap (por Milan Milanović)](https://github.com/milanm/DotNet-Developer-Roadmap)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-8_1)

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Compile e execute
9. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
10. Exiba as informações (básicas e adicionais) de todos os funcionários
11. Compile e execute
12. `Crie uma nova classe Biblioteca (nome e localizacao) e uma agregação com publicação`
13. `Crie um método na classe Biblioteca para exportar os dados de todas as publicações em arquivo (txt)`
14. `Crie um método na classe Biblioteca para importar os dados de todas as publicações do arquivo (txt)`
15. `Exporte e importe os dados básicos e/ou adicionais e realize as modificações necessárias no construtor das classes`
16. `Exiba os dados de todas as publicações`
17. `Use ReadAllLines e WriteAllLines para gravar e ler os dados`
18. `Compile e execute`
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (colecao de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do valor faturamento mes anterior
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
9. `Crie uma classe (nome: Hamburgueria) para gerenciar os funcionários (agregação)`
10. Compile e execute
- **`Exercício prático 2`**
1. `Evolua o exercício anterior com os próximos passos`
2. `Crie um método para exportar os dados dos funcionários em arquivo (txt)`
3. `Use ReadAllLines e WriteAllLines para gravar e ler os dados`
4. Compile e execute
- **`Exercício prático 3`**
1. `Evolua o exercício anterior com os próximos passos`
2. `Crie um método para importar os dados dos funcionários a partir de um arquivo (txt)`
3. `Use ReadAllLines e WriteAllLines para gravar e ler os dados`
4. `Compile e execute`
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>


</br>


## 📌 Learning Path 8.2 (Extra)
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Delegate, Action e Func*

1. [Delegates - Referência (variável, parâmetro, etc) a um método](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/delegates/using-delegates)
2. [Action - Delegate padrão de 0 a 16 parâmetros](https://learn.microsoft.com/pt-br/dotnet/api/system.action-1)
3. [Func - Delegate padrão de 0 a 16 parâmetros com retorno](https://learn.microsoft.com/pt-br/dotnet/api/system.action-1)

### Para aprofundar
- [Algoritmos implementados em C#](https://github.com/TheAlgorithms/C-Sharp)
- [C# Algoritmos](https://github.com/aalhour/C-Sharp-Algorithms)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*
> </br> [Código fonte de exemplo](https://github.com/jcguimaraesnet/csharp-learning-path-exercises/tree/path-8_2)

<details>
<summary>Exercício em aula</summary>

- `Exemplo 1: Delegate como variável para receber métodos ("Toy problem" simples)`
1. Crie um delegate personalizado: `public delegate int Operacao(int x, int y);`
2. Crie um método (estático) para Somar e multiplicar que seja compatível com a assinatura do Delegate
3. No método Main, crie uma variável (soma) do tipo Operacao que receba o método de Somar
4. No método Main, crie uma variável (multiplicacao) do tipo Operacao que receba o método de Multiplicacao
5. `Execute` a variável soma passando por parâmetro dois inteiros e exiba o resultado
6. `Execute` a variável multiplicacao passando por parâmetro dois inteiros e exiba o resultado
- `Exemplo 2: Delegate como parâmetro de método ("Toy problem" intermediário)`
1. Crie um método void (ExecutarOperacao) que receba como parâmetros dois inteiros e o tipo Operacao (delegate)
2. No método ExecutarOperacao, `execute` o parâmetro operacao informando os dois inteiros recebidos
3. Imprima no console os dois inteiros e o resultado da execução do delegate (linha anterior)
4. No método Main, execute o método ExecutarOperacao informando dois inteiros e a variável `soma`
5. No método Main, execute o método ExecutarOperacao informando dois inteiros e a variável `multiplicacao`
- `Exemplo 3: Delegate como encadeamento de métodos ("Toy problem" intermediário)`
1. Crie um delegate personalizado: public delegate `void` Operacao3(int x, int y);
1. Crie um novo método void para Somar `(Somar3)`, que receba dois inteiros e `imprima o resultado no console`
2. Crie um novo método void para Multiplicar `(Multiplicar3)`, que receba dois inteiros e `imprima resultado no console`
3. No método Main, crie uma variável `multiplasOperacoes` do tipo `Operacao3`
4. Atribua o método `Somar3` a variável multiplasOperacoes
5. Atribua o método `Multiplicar3` a variável multiplasOperacoes (use o operador +=)
6. No método Main, execute a variável multiplasOperacoes informando dois inteiros
- `Exemplo 4: Delegate como callback ("Toy problem" avançado)`
1. Crie um novo delegate personalizado: `public delegate void Callback(int result);`
2. Crie um método (Imprimir) que receba um inteiro e o imprima no Console (compatível com o delagate Callback)
3. Crie o método para Somar4, que receba dois inteiros e mais um parâmetro do tipo callback
4. No método Somar4, execute a soma, e logo após, execute o callback informando como parâmeto o resultado da soma
5. No método Main, execute o método Somar4, informando dois inteiros e o método Imprimir
6. Agora execute os mesmos passos implementando o método Multiplicar4
- `Exemplo 5: Use o delegate predefinido Func`
1. Refaça o exemplo 1 usando o delegate predefinido Func com dois parâmetros e um retorno: Func<int, int, int>
- `Exemplo 6: Use o delegate predefinido Action`
1. Refaça o exemplo 3 usando o delegate predefinido Action com dois parâmetros: Action<int, int>
- `Exemplo final: Publicações e Biblioteca`
1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Compile e execute
9. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
10. Exiba as informações (básicas e adicionais) de todos os funcionários
11. Compile e execute
12. Crie uma nova classe Biblioteca (nome e localizacao) e uma agregação com publicação
13. `Crie um método void para exibir publicações na classe Biblioteca que receba uma Action<string> como parâmetro (imprimir)`
14. `Na classe Program, crie um método void ImprimirPersonalizado para imprimir com background em verde`
16. `Execute o método ExibirPublicacoes da classe Biblioteca passando o método Console.WriteLine`
17. `Execute o método ExibirPublicacoes da classe Biblioteca passando o método ImprimirPersonalizado`
35. `Compile e execute`
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (colecao de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do valor faturamento mes anterior
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
9. Crie uma classe (nome: Hamburgueria) para gerenciar os funcionários (agregação)
10. Compile e execute
- **`Exercício prático 2`**
1. `Evolua o exercício anterior com os próximos passos`
2. `Crie um método para exportar os dados dos funcionários`
3. `Receba no método anterior um delegate de callback para gravar os dados`
4. `Crie um método compatível com o delegate de callback, que grave os dados em txt (sem cabeçalho)`
5. `No método Main, execute a exportação informando callback anterior`
6. `Compile e execute`
- **`Exercício prático 3`**
1. `Evolua o exercício anterior com os próximos passos`
2. `Crie um método compatível com o delegate de callback, que grave os dados em txt (com cabeçalho)`
3. `No método Main, execute a exportação informando callback anterior`
4. `Compile e execute`
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>


</br>


## 📌 Learning Path 9.1 (Extra)
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Eventos*

1. [Eventos - Visão Geral](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/events/)
2. [Evento - Um pequeno exemplo](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/event)
3. [Assinar eventos](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/events/how-to-subscribe-to-and-unsubscribe-from-events#to-subscribe-to-events-programmatically)

### Para aprofundar
- [Design Patterns com exemplos em C# 1 (DotNetTutorials)](https://dotnettutorials.net/course/dot-net-design-patterns/)
- [Design Patterns com exemplos em C# 2 (nemanharogico)](https://github.com/nemanjarogic/DesignPatternsLibrary)
- [Melhores práticas para Backend](https://github.com/Sairyss/backend-best-practices)
- [Padrões para System Design](https://github.com/Sairyss/system-design-patterns)
- [System Design Resources Awesome](https://github.com/ashishps1/awesome-system-design-resources)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. O livro possui informações adicionais de autor e ISBN
5. A revista possui informações adicionais de numero edição e ISSN
6. O jornal possui informações adicionais de data edição e cidade
7. Crie uma colecao com 10 tipos de funcionarios, atribuindo valores fixos e aleatórios
8. Compile e execute
9. Crie métodos para exibir informações básicas e adicionais (use, ou polimorfismo, ou abstração ou herança)
10. Exiba as informações (básicas e adicionais) de todos os funcionários
11. Compile e execute
12. Crie uma nova classe Biblioteca (nome e localizacao) e uma agregação com publicação
13. Compile e execute
14. `1.Crie um delegate personalizado na classe Biblioteca: public delegate void PublicacaoAdicionadaHandler(object sender, Publicacao publicacao);`
15. `2.Crie um evento com base no tipo delegate anterior: public event PublicacaoAdicionadaHandler PublicacaoAdicionada;`
16. `3.Execute o evento no método AdicionarPublicacao: PublicacaoAdicionada?.Invoke(this, publicacao);`
17. `4.Na classe Program, crie o método ImprimirPublicacaoAdicionada(object sender, Publicacao publicacao) para imprimir`
18. `5.Na classe Program, método Main, assine o evento: biblioteca.PublicacaoAdicionada += ImprimirPublicacaoAdicionada;`
19. `Compile e execute`
20. `1.Crie um evento com base no tipo delegate EventHandler: public event EventHandler<Publicacao> PublicacaoAdicionada2;`
21. `2.Execute o evento no método AdicionarPublicacao: PublicacaoAdicionada2?.Invoke(this, publicacao);`
22. `3.Na classe Program, método Main, assine o evento: biblioteca.PublicacaoAdicionada2 += ImprimirPublicacaoAdicionada;`
19. `Compile e execute`
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de cadastro de funcionários de uma hamburgueria (garçon, supervisor e caixa)
2. Obs.: Faça inicialmente para uma hamburgueria e depois personalize para outro tema (tema do aluno)
3. Nome, sobrenome e valor hora são informações comuns a todos os funcionários
4. O garçon possui informação adicional de número das mesas sob sua responsabilidade (array de int)
5. O supervisor possui informações adicional do turno que supervisiona (manha, tarde, noite, madrugada)
6. O caixa possui informação adicional do número do caixa que trabalha (valor faturamento mes anterior)
7. Crie um menu com opções para cadastrar os três tipos de funcionário
8. Crie também um menu para sair
9. Compile e execute
- **`Exercício prático 2`**
1. `Evolua o exercício anterior com os próximos passos`
2. `Crie uma classe Hamburgueria para controlar os funcionários. Crie um evento para funcionário adicionado`
3. `Acione o evento de funcionário adicionado, passando por parametro o resultado do método ToString()`
4. `Assine o evento e persista os dados recebidos do evento em um arquivo`
5. `Carregue os dados das publicações existente no arquivo na inicialização do programa`
6. `Use um delegate personalizado`
7. `Compile e execute`
- **`Exercício prático 3`**
1. `Evolua o exercício anterior com os próximos passos`
2. `Crie uma classe Hamburgueria para controlar os funcionários. Crie um evento para funcionário adicionado`
3. `Acione o evento de funcionário adicionado, passando por parametro o resultado do método ToString()`
4. `Assine o evento e persista os dados recebidos do evento em um arquivo`
5. `Carregue os dados das publicações existente no arquivo na inicialização do programa`
6. `Use o delegate EventHandler`
7. `Compile e execute`
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>

</br>
</br>

## :hammer_and_wrench: Packages para usar em console
- [Colorful.Console](https://github.com/tomakita/Colorful.Console)
- [ConsoleTables](https://github.com/khalidabuhakmeh/ConsoleTables)
- [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt)
- [Shellprogressbar](https://github.com/Mpdreamz/shellprogressbar)


## :mage: Perfis para seguir (post/newsletter .NET)
- [https://www.linkedin.com/in/milan-jovanovic](https://www.linkedin.com/in/milan-jovanovic/) (.NET +200k)
- [https://www.linkedin.com/in/djokic-stefan](https://www.linkedin.com/in/djokic-stefan/) (.NET +90k)
- [https://www.linkedin.com/in/davidcallan](https://www.linkedin.com/in/davidcallan/) (.NET +60k)
- [https://www.linkedin.com/in/mwaseemzakir](https://www.linkedin.com/in/mwaseemzakir/) (.NET +50k)
- [https://www.linkedin.com/in/davitshergilashvili](https://www.linkedin.com/in/davitshergilashvili/) (Architecture +50k)


## :link: Perfis para seguir (post/newsletter System Design)
- [https://www.linkedin.com/in/alexxubyte](https://www.linkedin.com/in/alexxubyte/) (System Design +800k)
- [https://www.linkedin.com/in/arslanahmad](https://www.linkedin.com/in/arslanahmad) (System Design +150k)
- [https://www.linkedin.com/in/ashishps1](https://www.linkedin.com/in/ashishps1/) (System Design +55k)


## :1st_place_medal: Para preparação e entrevistas
- [Especificação de projetos desafiadores (por nível de dificuldade)](https://github.com/ashishps1/awesome-coding-projects)
- [Leetcode resources](https://github.com/ashishps1/awesome-leetcode-resources)

- [Interview Q&A](https://github.com/ashishps1/awesome-behavioral-interviews)
