Segundo Trabalho de AED III
====
GCC109 – Algoritmos e Estrutura de Dados III
(Turmas 10A/14A/22A)

Componentes do Grupo:
Juventino Neto, Rafael Lima e Thiago Almeida

Proibida Cópia sem autorização.


Cadastro de referências bibliográficas com índice organizado em Árvore B
Requisitos
Um pesquisador deseja manter um cadastro de suas referências bibliográficas (artigos e livros)
em disco, e acabou de contratá-lo para resolver o problema. Para cada referência, o pesquisador
deseja manter os seguintes atributos:

*Código da referência (composição das três primeiras letras do nome do primeiro autor e
dois últimos dígitos do ano da publicação, por ex. SHI90 – esse campo é chave – para
simplificar, assumiremos que um autor não terá mais que uma publicação por ano).

* Título (string com o título).

* Autor (sobrenome e iniciais do primeiro autor, por ex.: Schimman,D.E.).

* Ano de publicação (por ex.: 1990).

* Veículo (string longa com o nome do congresso ou periódico, e outros dados adicionais,
como páginas, volume e número, local, etc.).

Você deverá desenvolver um sistema que permita ao pesquisador:

* Inserir uma nova referência, atualizando um índice.

* Remover uma referência a partir da chave. O registro deverá ser localizado acessando o
índice. A remoção deve colocar o caractere # (sustenido) na primeira posição do registro
removido no arquivo de dados. O espaço do registro removido não deverá ser
reutilizado para novas inserções, as quais deverão ser colocadas sempre no fim do
arquivo (supõe-se, assim, que um processo de compactação eliminaria os espaços
disponíveis em outro processo, mas não é necessário implementar neste trabalho).

* Buscar uma referência a partir da chave. A busca deve ser realizada acessando o
índice.

Ao final da execução, dois arquivos deverão ter sido criados: um arquivo de índice e um
arquivo de dados.
