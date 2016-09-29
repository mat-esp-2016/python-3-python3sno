# Python 3: Funções e programação defensiva

Parte do curso
[Matemática Especial I](https://github.com/mat-esp/about)
da [UERJ](http://www.uerj.br/).

Ministrado por [Leonardo Uieda](http://www.leouieda.com/).


## Objetivos

* Aprender como fazer suas próprias funções.
* Observar como criar funções ajuda a manejar um código complexo e evitar
  repetição.
* Aprender como usar funções torna possível testar seu código por partes.
* Entender as técnicas de programação defensiva para evitar erros.


## Leitura recomendada

Vamos seguir de perto o material
[Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/)
(ver as aulas "Creating Functions" e "Defensive Programming")
e
[Plotting and programming in Python](http://swcarpentry.github.io/python-novice-gapminder/)
do Software Carpentry.
Farei algumas modificações para ser mais voltado para o tipo de dados que
costumamos encontrar nas geociências.

Uma ótima referência para aprender a usar o numpy e matplotlib é o
[Scipy Lectures](http://www.scipy-lectures.org/).


## Tarefa

Utilize o link enviado para a [lista de
emails](https://github.com/mat-esp/about#informa%C3%A7%C3%B5es) para criar um
repositório para seu grupo ou se juntar a um grupo já criado.
Anote o link para o repositório criado para seu grupo. Vocês precisarão desse
link.

Clone o repositório do seu grupo para seu computador. Não se esqueça de
configurar o git para um dos membros do grupo (`git config --global user.name
"Fulado de Tal"` e `git config --global user.email fulado@gmail.com`).

Essa prática continua com os mesmo dados de temperatura que utilizamos na
prática [Python 2](https://github.com/mat-esp/python-2).

**IMPORTANTE**: tenha em mente o [checklist de
correção](https://github.com/mat-esp/about/blob/master/ISSUE_TEMPLATE.md#checklist-de-avalia%C3%A7%C3%A3o-do-professor)
quando fizer a tarefa. Não perca pontos de bobeira.
O site [pep8.org](http://pep8.org/) é uma boa referência para como escrever
código Python bem formatado.

Siga as instruções abaixo. Não se esqueça de fazer os commits e roda `git push`
para salvar seu trabalho.

1. Adicione no repositório um arquivo `alunos.txt` com os nomes completos de
   cada membro do grupo e seus nomes de usuário no github.com
2. Crie um Jupyter notebook chamado `python3.ipynb`. Todos os passos abaixo
   devem ser feitos nesse notebook. Use as células de texto do notebook para
   descrever o que você quis fazer com cada bloco de código.
3. Fazer e testar uma função que recebe como entrada um array de anos e um de
   meses e retorna um array de anos decimais.
4. Fazer e testar uma função que recebe como entrada uma matriz (array 2d) de
   dados de temperaturas e retorna os anos decimais, a anomalia anual, anomalia
   de 10 anos e sua respectiva incerteza.
5. Use as funções criadas acima para repetir a tarefa da prática
   [Python 2](https://github.com/mat-esp/python-2).


**BÔNUS**: Fazer e testar uma função que recebe como entrada o nome de um
arquivo de dados, o nome de uma pasta e o formato da figura (ex: `png`, `pdf`,
`svg`) e retorna o nome da respectiva figura
trocando o `.txt` pela extensão e adicionando o nome da pasta.
Exemplo: dado como entrada `'dados/0.80S-49.02W-TAVG-Trend.txt'`, formato `png`
e pasta `figuras`, a função deve retornar
`'figuras/0.80S-49.02W-TAVG-Trend.png'`.


## Entrega das soluções

A solução de cada prática será um repositório no [Github](http://github.com/)
com o código feito pelos alunos.

A entrega das soluções será feita criando uma
[Issue](https://guides.github.com/features/issues/)
no repositório da disciplina
[mat-esp/about](https://github.com/mat-esp/about).
Utilize o link abaixo para ir direto para as Issues:

https://github.com/mat-esp/about/issues

Cada grupo deve criar uma Issue para entregar cada prática.
A issue deverá seguir o padrão abaixo:

* Título: Deve conter o nome da prática seguido dos nomes dos integrantes do
  grupo e a qual turma pertencem (caso haja mais de uma). Ex: "Prática
  Integração: Bilbo, John, Arthur - Turma 1"
* Corpo: Deve conter o link para o repositório do grupo (ex:
  `https://github.com/mat-esp-2016/integracao-sociedade-42`) e qualquer
  comentário que achar necessário (ex: problemas com os commits, erros que foram
  arrumados depois, dificuldades, etc).


## License

All content can be freely used and adapted under the terms of the
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)
