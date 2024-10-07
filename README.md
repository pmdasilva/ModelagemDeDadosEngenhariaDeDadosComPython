# ModelagemDeDadosEngenhariaDeDadosComPython
'Aqui adicionarei o desafio do bootcamp de Engenharia de dados com python, que é voltado a modelagem de dados, fazendo como proposto pelo Bootcamp migrar uma base de dados do modelo de relacionamento para o modelo Star Schema.'


# Descrição Desafio:

Descrição do desafio de modelagem dimensional


## Objetivo:

* Criar o diagrama dimensional – star schema – com base no diagrama relacional disponibilizado.

## Foco:

Professor – objeto de análise

Vocês irão montar o esquema em estrela com o foco na análise dos dados dos professores. Sendo assim, a tabela fato deve refletir diversos dados sobre professor, cursos ministrados, departamento ao qual faz parte.... Por aí vocês já têm uma ideia do que deve compor a tabela fato do modelo em questão.

Obs.: Não é necessário refletir dados sobre os alunos!

### O que deve ser feito?

Deverá ser criada a tabela Fato que contêm o contexto analisado. Da mesma forma, é necessária a criação das tabelas dimensão que serão compostas pelos detalhes relacionados ao contexto.

Por fim, mas não menos importante, adicione uma tabela dimensão de datas. Para compensar a falta de dados de datas do modelo relacional, suponha que você tem acesso aos dados e crie os campos necessários para modelagem.

Ex: data de oferta das disciplinas, data de oferta dos cursos, entre outros. O formato, ou melhor, a granularidade, não está fixada. Podem ser utilizados diferentes formatos que correspondem a diferentes níveis de granularidade.


### Imagem de referência:

![alt text](image.png)


# Resolução do desafio e implementações sugeridas:

Então no dasafio foi proposto remodularizarmos a estrutura de relacionamento, para uma estrutura de modelo star schema, onde o foco de nossa estrutura seria priorizar o nosso professor. Fazendo uma estrutura com bases mais exutas e relevante ao nosso professor. Tambem como obejtivo tivemos adicionar a dimensão date.

### Resultado do Desafio:

![alt text](image-1.png)

Link: para acesso a modelagem:
https://app.sqldbm.com/MySQL/Diagrams/p315445