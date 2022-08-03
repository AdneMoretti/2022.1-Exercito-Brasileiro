# NFR Framework

## Introdução

O NFR Framework é uma abordagem para representar e analisar Requisitos
Não-Funcionais.
Tem como principal objetivo auxiliar os desenvolvedores no processo
de implantação de soluções personalizadas com a perspectiva das características
do domínio e do sistema em questão.

Essas características incluem os Requisitos Não-Funcionais, Requsitos Funcionais,
prioridades e carga de trabalho. Os Requisitos Não-Funcionais são considerados
cidadãos de primeira ordem.

O Framework trabalha com o conceito de softgoals, e possui um método de análise
quantitativa para definiar os status dos softgoals.

## Softgoals

Um softgoal é um objetivo que não tem definição clara nem critérios de aceitação precisos.
São utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados,
indicando a influência de um softgoal em outro.

Para representar essa interdependência, usa-se um Softgoal Interdependency Graph (SIG).
Esses gráficos armazenam um registro completo de todas as decisões de desenvolvimento
e da lógica do projeto de forma gráfica e concisa, incluindo os Requisitos Não-Funcionais e suas
alternativas, decisões e justificativas.

Existem três tipos de softgoals, e cada um deles possui uma notação gráfica associada.

### Softgoals NFR

Representam os Requisitos Não-Funcionais.
Podem estar interrelacionados, organizados em catálogos e apresentados
de forma hierárquica durante o desenvolvimento do projeto.

Sua notação gráfica é uma nuvem com contorno simples, como mostra a _figura 1_.

### Softgoals de Operacionalização

Representam as soluções de implementação que satisfazem os softgoals NFR
em outros softgoals de operacionalização.
Incluem processos, representações de dados, operações, estruturações
e restrições no sistema alvo para atender às necessidades indicadas pelos softgoals em questão.

Sua notação gráfica é uma nuvem com contorno em negrito, como mostra a _figura 2_.

### Softgoals de Afirmação

Representam as características de domínio de forma que elas possam ser
consideradas e refletidas durante o processo de tomada de decisão.
Servem como justificativa para a forma de priorização dos softgoals,
decidindo quais deles são selecionados, refinados e priorizados.
Devem ser escritos em linguagem natural, e anotam algo que pode ser
acrescentado ao modelo em um ponto específico.

Sua notação gráfica é uma nuvem com contorno tracejado, como mostra a _figura 3_.

## Decomposição

Existem quatro tipos de decompoições no Framework NFR.
Três delas estão associadas a um tipo de softgoal, e a quarta
pode ser aplicada em qualquer tipo.

### Decomposição de um softgoal NFR

Refina ou subdivide um softgoal NFR em outros específicos.
Divide grandes problemas em problemas menores, e ajuda a lidar com ambiguidades
e problemas na priorização.

### Decomposição de Operacionalização

Subdivide um softgoal de operacionalização em outros softgoals de
operacionalização mais específicos.
É útil para definir uma solução geral e refiná-la em soluções mais específicas.

### Decomposição de Afirmação (Claims)

Refina um softgoal de afirmação em outros softgoals de afirmação.
Importante para apoiar ou negar justificativas específicas do projeto.

### Priorização

É um tipo especial de decomposição, que pode ser aplicada em qualquer tipo de softgoal.
Refina um softgoal em outro com o mesmo tipo e tópicos, mas com uma prioridade associada.

## Contribuições

Conforme os softgoals são refinados sucessivamente, um sofgoal descendente
pode contribuir de forma total ou parcial, de forma negativa ou posisitca,
para a satisfação do ascendente.

Contribuições descrevem como a satisfação ou não de um softgoal descendente
contribui para a satisfação de um softgoal ascendente, poden ser positivas ou negativas,
ou até satisfazendo completamente o ascendente.

## Referências
<div align="justify">&emsp;&emsp; Os seguintes documentos de Cenarios serviram como referência durante a elaboração desse documento:
</div><br>

> BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.<br><br>

| Versão | Data | Descrição | Autor | Revisor |
|--------|------|-------|-----------| ------- |
| 0.1 | 03/08/22 | Documento Inicial | Guilherme Puida e Vitor Eduardo | --




