# MoSCoW

## Introdução

O método MoSCoW é uma técnica de priorização de tarefas.
Esse método pode auxiliar a manter o fluxo de entregas eficiente e com o máximo de funcionalidade em cada entrega.

As iniciais de _MoSCoW_ representam, em inglês, o esquema de priorização que essa técnica define:

* Must-have
* Should-have
* Could-have
* Won't-have

## Must-have

Requisitos que são extritamente necessários para o projeto, ou seja,
sem esses requisitos o projeto não será bem-sucedido.

Algumas métricas para determinar se um requisito é _must-have_ são:

1. O usuário só ficará satisfeito caso esse requisito seja concluído.
1. O requisito não possui alternativas satisfatórias.
1. O sucesso do projeto depende da conclusão desse requisito.

## Should-have

Requisitos que tem um impacto significativos no fluxo do projeto.
São importantes e devem ser implementados, mas tem importância menor que os requisitos _must-have_.

Para determinar se um requisito é _should-have_, deve-se considerar o valor que ele agrega ao projeto.

## Could-have

São menos importantes que requisitos _should-have_.
Agregam valor ao projeto, mas sua ausência não impacta significantemente.

Para distinguir requisitos _should-have_ de requisitos _could-have_, deve-se analizar o fluxo do projeto.
Aqueles com maior impacto devem ser categorizados como _should-have_, e os outros como _could-have_.

Esses requisitos só devem ser incluídos no projeto quando todos os requisitos com maior importância foram satisfeitos.

## Won't-have

São aqueles que não tem importância significativa para o projeto.
A presença ou ausência desses requisitos não tem impacto na conclusão satisfatória do projeto.

Categorizar requisitos nessa categoria ajuda a diminuir o escopo das funcionalidades.

# First Things First

## Introdução

First Things First é uma técnica de priorização onde há um levantamento dos benefícios, custos e riscos associados a cada requisito.
Utilizando essa metodologia, é possível estabelecer uma ordem de prioridade de cada requisito, baseando-se nos fatores que impactam os usuários finais.

## Metodologia

Nessa metodologia, é construída uma tabela que equilibra os posicionamentos do cliente e do desenvolvedor.
Os seguintes passos devem ser seguidos:

1. Listagem de todos os requisitos, retirando somente os interdependentes.
2. Estimativa do benefício relativo de cada funcionalidade.
3. Estimativa da penalidade decorrente da não aplicação ou atraso do requisito.
4. Estimativa do custo relativo de implementação.
5. Estimativa do grau relativo ao risco de aplicação.
6. Cálculos
   1. Valor total: (Benefício relativo * Peso Relativo + Penalidade Relativa * Peso Relativo)
   2. Prioridade: Valor / (Custo * Peso de Custo + Risco * Peso de Risco)
7. Ordenação da lista em ordem decrescente de prioridade.

_Todas as estimativas são feitas em uma escala de 1 à 9, crescente._
