# Funções e programação defensiva

Parte do curso
[Matemática Especial I](http://www.leouieda.com/matematica-especial/)
da [UERJ](http://www.uerj.br/).

Ministrado por [Leonardo Uieda](http://www.leouieda.com/).

## Objetivos

* Aprender a utilizar funções para manejar seu código
* Desenvolver técnicas para produzir código mais correto

## Leitura recomendada

* Lição de funções do [Software Carpentry](http://software-carpentry.org/)
  (versão 4)
* Lição de programação defensiva do Software Carpentry
  :http://swcarpentry.github.io/python-novice-inflammation/08-defensive.html
* http://www.scipy-lectures.org/intro/language/functions.html

## Preparação

Utilize o link enviado por e-mail para criar um repositório para seu grupo.
Cada membro do grupo deve clicar no link e selecionar o nome do grupo criado na
prática passada.
Não se esqueça de sair de sua conta **no github.com e no
classroom.github.com**.

**Crie um arquivo** chamado `alunos.txt` com os **nomes completos** de todos os
integrantes do grupo. Inclua também a **qual turma** pertencem.

As tarefas para serem feitas estão em um [Jupyter
notebook](http://jupyter.org/).
Para utilizar o Jupyter, você precisa iniciar um servidor de notebook
no seu computador.
Abra o bash e digite:

    $ jupyter notebook

Espere um pouco até aparecer algo como:

    [I 10:50:47.370 NotebookApp] Serving notebooks from local directory: /home/leo
    [I 10:50:47.370 NotebookApp] 0 active kernels
    [I 10:50:47.370 NotebookApp] The IPython Notebook is running at: http://localhost:8888/
    [I 10:50:47.370 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).

Isso deve abrir o seu navegador padrão também em uma página no endereço
[http://127.0.0.1:8888](http://127.0.0.1:8888).
Essa página irá te mostrar as pastas que estão em seu computador
(a partir da pasta onde você rodou `$ jupyter notebook`).

## Tarefas

Siga as instruções em no notebook disponibilizado no repositório.
As tarefas e **suas soluções devem estar contidas nesse notebook**.
Por isso, faça commits de suas mudanças ao notebook.

**AVISO**: Não esqueça de verificar se abriu o notebook no clone correto!

**AVISO 2**: Após cada mudança, `git add` + `git commit` + `git push`.

**AVISO 3**: ANTES de começar: `git pull origin master`

## Dicas

* Façam muitos **commits**. Quanto mais melhor.
* Não se esqueça do **push**.
* Utilize **mensagens de commit** descritivas. "Completei a tarefa 1" é melhor que
  "mudança".
* Escolha nomes descritivos para **variáveis**. "temperatura" é melhor que "a".
* **Descreva o que (e por que) você fez** em comentários e células de texto.
  Isso será muito útil quando você voltar a essa tarefa depois.
* Preste atenção aos **detalhes**. Leia as instruções com atenção.

## Checklist da avaliação

Utilizaremos a lista abaixo para avaliar a sua solução. Cada item poderá
receber a nota "total" se atender perfeitamente ao critério, "parcial" (metade
da nota) se atender parcialmente ao critério, ou "zero" se falhar ao critério.
Note que a nota máxima (incluindo a bônus) é 10.

    - [] Mensagens de commit que explicam claramente a mudança que foi feita
      [total|parcial|zero] 0.5 pt
    - [] Formatação do código apropriada.
      Ex: `espacamento = (maximo - minimo)/(N - 1)`,
      `indices = range(0, N, 1)`, `dado = dados[i + 1]` == BOM.
      `espacamento=(maximo-minimo)/ (N-1)`, `indices=range (0,N,1)`,
      `dado= dados [i+ 1]` == RUIM [total|parcial|zero] 0.5 pt
    - [] Utilizar variáveis ao invés de colocar número "na mão".
      Ex: `for i in range(0, N):`, `A[k][N - 1]` == BOM.
      `for i in range(0, 39):`, `A[k][47]` == RUIM. [total|parcial|zero] 1 pt
    - [] Código com comentários que explicam "por que" algo foi feito, não só
      "o que" foi feito [total|parcial|zero] 1 pt
    - [] Nomes de variáveis descritivos. Ex: `temperatura`, `media_por_hora`,
      `linha`, `somatorio` == bom. `a`, `var`, `meh`, `lista` == ruim.
      [total|parcial|zero] 2 pt
    - [] Código produz a solução correta (**exatamente** como deveria ser
      impresso) [total|parcial|zero] 5 pt
    - [] Tarefa bônus [total|parcial|zero] 1 pt extra (não será considerado
      caso a nota já seja 10)

## License

All content can be freely used and adapted under the terms of the
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)
