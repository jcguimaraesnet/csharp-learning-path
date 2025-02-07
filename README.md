# C# Learning Path

ℹ️ Este repositório contém uma proposta de trilha de aprendizado para a linguagem C# em dezoito aulas, contendo links para a documentação da Microsoft e exercícios  práticos.

🧑🏽‍🎓 Essa proposta de aprendizado se destina inicialmente para alunos do Instituto Infnet, uma faculdade focada na área de TI com sede no Rio de Janeiro/Brasil, cujas disciplinas transcorrem em uma janela de espaço de nove semanas (ou dezoito aulas). Eu ficaria feliz se o conteúdo estruturado aqui neste repo for útil para professores e alunos de outras instituições e demais interessados no aprendizado dessa linguagem. 

# ⭐ Dê uma estrela

If you're using this repository for your learning, samples, workshop, or your project, please give a star. Thanks :+1:

Se você estiver usando este repositório para seu aprendizado, amostras, workshop ou seu projeto, por favor, dê uma estrela. Obrigado `:+1:`


⭐ Favorite este repositório para me deixar feliz.

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
7. [Operador Ternário (?:)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/conditional-operator)
8. [Operadores aritméticos](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/arithmetic-operators)
9. [Operadores de comparação](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/comparison-operators)
10. [Operadores lógicos](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/boolean-logical-operators)
11. [Manipulando datas](https://learn.microsoft.com/pt-br/dotnet/standard/datetime/how-to-use-dateonly-timeonly)
12. [Tratamento de erros com try-catch](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/exceptions/)

### Para aprofundar
- [Todos operadores em C# (aritméticos, lógicos e comparação)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/)
- [Correspondência de padrões (técnica funcional)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/patterns)

### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de funcionários de uma hamburgueria (apenas 1 funcionário)
2. Formulário de leitura de dados pessoais: nome, sobrenome e salário
3. Exiba o nome completo em caixa alta
4. Compile e execute
5. Leia a quantidade de horas trabalhadas no mês (int)
6. Calcule o valor hora do funcionário dividindo o salário (convertido para int) pelas horas trabalhadas no mês
7. Caso necessário, capture as exceções que podem ocorrer neste cálculo
8. Compile e execute
9. Adicione a leitura da data de nascimento ao formulário
10. Imprima no console se a pessoa é menor aprendiz (menor que 18)
11. Compile e execute
12. Exiba a categoria de classe de renda (A, B, C, D e E) por faixa de renda (1.5k, 5k, 10k, 20k, 40k)
13. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. O programa deve calcular o total de um pedido apenas uma vez por execução do programa
3. Imprima duas opções de de produto da loja (ex: 1 - beef burguer e 2 - fish burguer)
4. Leia a opção de produto desejado pelo usuário
5. Leia a quantidade desejada, calcule e imprima o total do pedido
6. Compile e execute
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
2. Imprima a média a maior, a maior e a menor nota
3. Compile e execute
</details>


</br>

## 📌 Learning Path 2.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: orientação a objetos (introdução)*
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


### Para aprofundar
- [Exceções mais comuns (tanto para capturar, quanto para utilizar)](https://learn.microsoft.com/pt-br/dotnet/standard/exceptions/#common-exceptions)
- [Classes parciais](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/partial-classes-and-methods)
- [Inicializando objetos (4 formas diferentes)](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/types/classes#constructors-and-initialization)
- [Struct para pequenos tipos de dados com pouco comportamento (imutáveis)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/builtin-types/struct)
- [Record para tipos focados em armazenamento de dados sem comportamento](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/types/records)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de funcionários de uma hamburgueria (apenas um funcionário)
2. Formulário de leitura de dados pessoais: nome, sobrenome e salário
3. Exiba o nome completo em caixa alta
4. Exiba o valor da hora extra. Regra: Salario / 160 * 40%
5. Compile e execute
6. Adicione a leitura da data de nascimento ao formulário
7. Imprima no console se a pessoa é menor aprendiz (menor que 18)
8. Compile e execute
9. Exiba a categoria de classe de renda (A, B, C, D e E) por faixa de renda (1.5k, 5k, 10k, 20k, 40k)
10. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **`Exercício prático 1`**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. O programa deve calcular o total de um pedido apenas uma vez por execução do programa
3. Imprima uma lista de menu com duas opções de produto da loja (exemplo: beef burger e fish burguer)
4. Leia a opção de produto desejado pelo usuário
5. Leia a quantidade desejada, calcule e imprima o total do pedido
6. Calcule um desconto de 10% para total de pedido acima de 200 reais
7. Compile e execute
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


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*

<details>
<summary>Exercício em aula</summary>

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
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. Apresente um menu com duas opções de produto e seus valores (exemplo: beef burger e fish burguer)
3. Leia a opção de produto desejado pelo usuário
4. Leia a quantidade desejada e apresente o menu novamente
5. Ofereça também um item de menu para calcular o valor total de todos os pedidos
6. E ofereça um outro item de menu para sair do programa
7. Compile e execute
- **`Exercício prático 2`**
1. Crie uma coleção com cinco nome de frutas (nomes fixos no programa)
2. Filtre e imprima os nomes de frutas que começam com a letra “b” ou “B”
3. Compile e execute
- **`Exercício prático 3`**
1. Crie uma coleção que contenha frutas do tipo crítica e não cítricas (fixos no programa)
2. Filtre e imprima apenas as frutas do tipo cítricas
3. Compile e execute
- **`Exercício prático 4`**
1. Crie uma coleção que contenha 10 números inteiros (fixos no programa)
2. Imprima somente os números ímpares
3. Compile e execute
</details>

</br>

## 📌 Learning Path 3.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Orientação à objetos (encapsulamento)*

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
3. Opção 1: ler os dados do funcionário: nome, cargo e salário
4. Opção 2: Aumentar o salário (regra → aplicar 20% de aumento para gerente e 10% para os demais)
5. Opção 3: Exibir salário
6. Opção 4: Sair do programa
7. Compile e execute
- **`Exercício prático 2`**
1. Simule operações de transações com um cartão de crédito (duas ou mais transações de compra)
2. Antes de simular as operações, defina um limite inicial de R$ 5000,00
3. Imprima na tela o limite atual
4. Compile e execute
- **`Exercício prático 3`**
1. Simule um sistema de fidelidade de pontos (duas ou mais transações)
2. Antes de simular as operações, defina uma pontuação inicial de 50 pontos
3. Cada transação deve ser convertida em dólar. Cada dólar gera 1 ponto.
4. Simule uma operação de resgate de 10 pontos.
5. Imprima na tela a pontuação atual
6. Compile e execute
- **`Exercício prático 4`**
1. Simule um carrinho de compras de um ecommerce
2. Simule duas ou mais operações de “adicionar itens ao carrinho” informando tipo e qtde do produto
3. Crie uma propriedade que contenha o total do pedido
4. Imprima na tela o valor total do pedido
5. Compile e execute
</details>

</br>

## 📌 Learning Path 4.1
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Orientação à objetos (herança)*

1. [O que é uma herança - relacionamento do tipo “é um” (ex: garçon "é um" funcionário)](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/tutorials/inheritance#background-what-is-inheritance)
2. [Conceito de classe base e classe derivada](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/tutorials/inheritance#background-what-is-inheritance)
3. [Palavra-chave base para herança explícita de construtor (não existe herança implícita de construtor)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/base)
4. [Palavra-chave sealed para impedir herança](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/sealed)
5. [Sobrecarregando métodos](https://learn.microsoft.com/pt-br/dotnet/standard/design-guidelines/member-overloading)


### Para aprofundar
- [Ferramenta para modelar diagrama de classes (Draw.io)](https://app.diagrams.net)
- [Ferramenta para modelar diagrama de classes (Lucidchart)](https://lucid.app/lucidchart/706e4961-b5e1-4f87-b000-3037506405bb/edit?invitationId=inv_559bf1e0-50db-4c2c-9e5f-0482cc331425&page=azYL66cQbwSa#)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Simule o cadastro de três tipos de publicação (livro, revista e jornal)
3. Titulo, ano publicação e editora são informações básicas a todas as publicações
4. Crie um método que imprima todos as informações básicas de qualquer tipo de publicação
5. O livro possui informações adicionais de autor e ISBN
6. A revista possui informações adicionais de numero edição e ISSN
7. O jornal possui informações adicionais de data edição e cidade
8. Crie as três publicações atribuindo valores aleatórios (use herança de construtor)
9. Crie um método para cada tipo de publicação para imprimir as informações básicas e adicionais (Ex: ExibirDadosLivro). Execute cada método.
10. Compile e execute
11. Crie um método (sobrecarga) para cada tipo de publicação para imprimir as informações segmentadas em duas partes ("Informações básicas:" e "Informações adicionais:"). Execute cada método.
12. Compile e execute

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
7. Crie os três funcionários atribuindo valores aleatórios (use herança de construtor)
8. Exiba os dados comuns dos três funcionários
9. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Todos os funcionários recebem um salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base de cada um dos três funcionários
4. Compile e execute
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. O garçom possui calculo de comissão (regra: salario base mensal * mesas / 100)
3. O supervisor possui calculo de adicional noturno (regra: noite → 10% e madruga 20% salario base mensal)
4. O caixa possui calculo de bonus (regra: valor faturamento mes anterior * 0.01%)
5. Exiba o salario total mensal de cada um dos três funcionários (salario base + adicional)
6. Compile e execute
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>

</br>

## 📌 Learning Path 4.2
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Orientação à objetos (polimorfismo)*
> </br> **Leitura do TP2**

1. [O que é polimorfismo](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/object-oriented/polymorphism)
2. [Permitindo a sobrescrita de membros na classe base (virtual)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/virtual)
3. [Sobrescrevendo membros (da classe base) na classe derivada (override)](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/override)
4. [Object e herança implícita para classes](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/tutorials/inheritance#implicit-inheritance)
5. [Usando método ToString em classes herdadas implicitamente](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/how-to-override-the-tostring-method)


### Para aprofundar
- [Clean Code para C# (thangchung)](https://github.com/thangchung/clean-code-dotnet)



### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Crie um menu com três opções de cadastro (livro, revista e jornal)
3. Crie também uma opção de menu para exibir todas as publicações
4. Crie também uma opção de menu para sair
5. Titulo, ano publicação e editora são informações básicas a todas as publicações
6. Crie um método que imprima todos as informações básicas de qualquer tipo de publicação
7. O livro possui informações adicionais de autor e ISBN
8. A revista possui informações adicionais de numero edição e ISSN
9. O jornal possui informações adicionais de data edição e cidade
10. Crie as três publicações solicitando leitura dos dados no console 
11. Sobrescreva o método de imprimir da classe base para exibir também as informações adicionais de cada tipo de publicação.
12. Compile e execute
13. Experimente usar o método ToString (ao invés do método Imprimir) para exibir os dados da publicação no console
14. Compile e execute

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
8. Crie também um menu para exibir os dados de todos os funcionários
9. Crie também um menu para sair
10. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Todos os funcionários recebem um salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base de cada um dos três funcionários
4. Compile e execute
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. O garçom possui calculo de comissão (regra: salario base mensal * mesas / 100)
3. O supervisor possui calculo de adicional noturno (regra: noite → 10% e madruga 20% salario base mensal)
4. O caixa possui calculo de bonus (regra: valor faturamento mes anterior * 0.01%)
5. Exiba o salario total mensal (base + adicional) dos funcionários cadastrados
6. Compile e execute
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>


</br>

## 📌 Learning Path 5.1
### Tópicos principais


> [!IMPORTANT]
> *Assuntos cobertos: Orientação à objetos (abstração)*

1. [O que é abstração](https://pt.wikipedia.org/wiki/Abstra%C3%A7%C3%A3o_(ci%C3%AAncia_da_computa%C3%A7%C3%A3o))
2. [Abstract para classe](https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/abstract-and-sealed-classes-and-class-members#abstract-classes-and-class-members)
3. [Abstract para métodos e membros de uma classe](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/abstract)


### Para aprofundar
- [Princípios SOLID com exemplos em C#](https://github.com/richielybmp/solid-design-principles-in-c-sharp)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Crie um menu com três opções de cadastro (livro, revista e jornal)
3. Crie também uma opção de menu para exibir todas as publicações
4. Crie também uma opção de menu para sair
5. Titulo, ano publicação e editora são informações básicas a todas as publicações
6. Defina a classe base como abstrata
7. Crie um método abstrato para imprimir informações adicionais
8. Crie um método que imprima todos as informações básicas de qualquer tipo de publicação e invoke o método abstrato de informações adicionais
9. O livro possui informações adicionais de autor e ISBN
10. A revista possui informações adicionais de numero edição e ISSN
11. O jornal possui informações adicionais de data edição e cidade
12. Crie as três publicações solicitando leitura dos dados no console 
13. Implemente o método de imprimir informações adicionais para exibir as informações adicionais de cada tipo de publicação.
14. Compile e execute
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
8. Crie também um menu para exibir os dados de todos os funcionários
9. Crie também um menu para sair
10. Use o conceito de abstração em classe e método neste exercício
11. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Todos os funcionários recebem um salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base de cada um dos três funcionários
4. Compile e execute
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. Defina na classe base um método abstrato para calcular salario adicional
3. Invoke o método abstrato na classe base para exibir o salário total (base + adicional)
4. Implemente um método de salário adicional para cada funcionário
5. O garçom possui calculo de comissão (regra: salario base mensal * mesas / 100)
6. O supervisor possui calculo de adicional noturno (regra: noite → 10% e madruga 20% salario base mensal)
7. O caixa possui calculo de bonus (regra: valor faturamento mes anterior * 0.01%)
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
> *Assuntos cobertos: Orientação à objetos (interface)*

1. [O que é uma interface](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/interface)
2. 


### Para aprofundar
- [Implementação padrão em interfaces](https://learn.microsoft.com/pt-br/dotnet/csharp/advanced-topics/interface-implementation/default-interface-methods-versions)


### Exercícios
> [!CAUTION]
> *Obs: Coloque o nome das soluções/projetos com o número da aula (Ex: Aula_1.1)*

<details>
<summary>Exercício em aula</summary>

1. Implemente um programa de cadastro de publicações de uma biblioteca
2. Crie um menu com três opções de cadastro (livro, revista e jornal)
3. Crie também uma opção de menu para exibir todas as publicações
4. Crie também uma opção de menu para sair
5. Titulo, ano publicação e editora são informações básicas a todas as publicações
6. Defina a classe base como abstrata
7. Crie um método abstrato para imprimir informações adicionais
8. Crie um método que imprima todos as informações básicas de qualquer tipo de publicação e invoke o método abstrato de informações adicionais
9. O livro possui informações adicionais de autor e ISBN
10. A revista possui informações adicionais de numero edição e ISSN
11. O jornal possui informações adicionais de data edição e cidade
12. Crie as três publicações solicitando leitura dos dados no console 
13. Implemente o método de imprimir informações adicionais para exibir as informações adicionais de cada tipo de publicação.
14. Compile e execute
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
8. Crie também um menu para exibir os dados de todos os funcionários
9. Crie também um menu para sair
10. Use o conceito de abstração em classe e método neste exercício
11. Compile e execute
- **`Exercício prático 2`**
1. Evolua o exercício anterior com os próximos passos
2. Todos os funcionários recebem um salário base mensal. Regra: valor hora * total de horas mes (160)
3. Exiba o salário base de cada um dos três funcionários
4. Compile e execute
- **`Exercício prático 3`**
1. Evolua o exercício anterior com os próximos passos
2. Defina na classe base um método abstrato para calcular salario adicional
3. Invoke o método abstrato na classe base para exibir o salário total (base + adicional)
4. Implemente um método de salário adicional para cada funcionário
5. O garçom possui calculo de comissão (regra: salario base mensal * mesas / 100)
6. O supervisor possui calculo de adicional noturno (regra: noite → 10% e madruga 20% salario base mensal)
7. O caixa possui calculo de bonus (regra: valor faturamento mes anterior * 0.01%)
8. Compile e execute
- **`Exercício prático 4`**
1. Personalize os tipos de funcionários e os cálculos de acordo com o tema da sua loja
2. Use a criatividade para personalizar o seu cadastro
3. Compile e execute
</details>


<!-- 

### Extras
- [Operador “=>”  para “arrow function” ou definição de corpo de métodos](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/operators/lambda-operator#expression-body-definition)

-->