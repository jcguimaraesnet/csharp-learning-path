# C# Learning Path

ℹ️ Este repositório contém uma proposta de trilha de aprendizado para a linguagem C# em dezoito aulas, contendo links para a documentação da Microsoft e exercícios  práticos.

🧑🏽‍🎓 Essa proposta de aprendizado se destina inicialmente para alunos do Instituto Infnet, uma faculdade focada na área de TI com sede no Rio de Janeiro/Brasil, cujas disciplinas transcorrem em uma janela de espaço de nove semanas (ou dezoito aulas). Eu ficaria feliz se o conteúdo estruturado aqui neste repo for útil para professores e alunos de outras instituições e demais interessados no aprendizado dessa linguagem. 

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
8. [Uso e definição de namespaces](https://learn.microsoft.com/pt-br/dotnet/csharp/fundamentals/types/namespaces)
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

- **Exercício prático 1**
1. Implemente um aplicativo console Hello World
2. Execute o aplicativo sem depuração
- **Exercício prático 2**
1. Execute linha a linha o aplicativo anterior
2. Antes de executar o comando de imprimir no console, altere o texto “Hello World” para conter o seu nome.
3. Continue a execução do programa e verifique a saída no console
- **Exercício prático 3**
1. Implemente um aplicativo console que imprima no console seu nome, idade e hobby
2. Crie variáveis para conter os seus dados
3. Crie um breakpoint na linha de código idade
4. Execute linha a linha o seu aplicativo
5. Altere o valor atribuído da variável idade (qualquer outro valor) em tempo de execução
6. Finalize a execução do aplicativo e verifique a saída no console
- **Exercício prático 4**
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
4. Leia a quantidade de horas extras trabalhadas
5. Exiba o valor total de horas extras. Regra: Salario / 160 * 40% * horas extras
6. Compile e execute
7. Adicione a leitura da data de nascimento ao formulário
8. Imprima no console se a pessoa é menor aprendiz (menor que 18)
9. Compile e execute
10. Exiba a categoria de classe de renda (A, B, C, D e E) por faixa de renda (1.5k, 5k, 10k, 20k, 40k)
11. Compile e execute
</details>

<details>
<summary>Exercícios práticos</summary>

- **Exercício prático 1**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. O programa deve calcular o total de um pedido apenas uma vez por execução do programa
3. Imprima duas opções de de produto da loja (ex: 1 - beef burguer e 2 - fish burguer)
4. Leia a opção de produto desejado pelo usuário
5. Leia a quantidade desejada, calcule e imprima o total do pedido
6. Compile e execute
- **Exercício prático 2**
1. Calcule o IMC de uma pessoa (peso / altura)
2. Imprima no console as classificações de acordo com a OMS (abaixo do peso, normal, sobrepeso, obesidade)
3. Compile e execute
- **Exercício prático 3**
1. Calcule e imprima a média escolar de aluno com base em três notas (nome, nota1, nota2, nota3)
2. Informe a situação atual do aluno (reprovado < 5; aprovado ≥ 7; recuperação 5 ≥ e < 7)
3. Compile e execute
- **Exercício prático 4**
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

- **Exercício prático 1**
1. Implemente um programa de caixa registradora para uma loja (tema do aluno)
2. Imprima uma lista de menu com opções de produto da loja
3. Leia a opção de produto desejado pelo usuário
4. Leia a quantidade desejada, calcule e imprima o total do pedido
5. Realize um desconto de 50% no total calculado apenas para o quinto pedido do dia
6. Ofereça uma opção para reiniciar a caixa registradora e outra opção para sair
7. Compile e execute
- **Exercício 2**
1. Implemente um pequeno jogo para acertar cara ou coroa
2. Saia do programa somente quando o usuário acertar
3. Use enumeration no seu programa
4. Compile e execute
- **Exercício 3**
1. Defina um array de inteiro com 5 números aleatórios e fixos
2. Exiba o array na ordem inversa ao que foi definido
3. Compile e execute
- **Exercício 4**
1. Defina um array de float com 4 posições, leia 4 notas escolares, calcule a média, a maior e a menor nota 
2. Imprima a média a maior, a maior e a menor nota
3. Compile e execute
</details>
