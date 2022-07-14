# Priorização

Definir a prioridade dos requisitos elicitados é de suma importância para o sucesso de um projeto.
Sem essa priorização, os recursos podem ser alocados de forma ineficiente, desperdiçando tempo e dinheiro dos clientes e dos desenvolvedores.
Assim, existem diversas técnicas que auxiliam no processo de priorização dos requisitos.

# MoSCoW

## Introdução

O método MoSCoW é uma técnica de priorização de tarefas.
Esse método pode auxiliar a manter o fluxo de entregas eficiente e com o máximo de funcionalidade em cada entrega.

As iniciais de _MoSCoW_ representam, em inglês, o esquema de priorização que essa técnica define:

* Must-have
* Should-have
* Could-have
* Won't-have

Esses níveis de priorização seguem as definições do RFC2119 (IETF, 1997).

## Must-have

Requisitos que são estritamente necessários para o projeto, ou seja,
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

Para distinguir requisitos _should-have_ de requisitos _could-have_, deve-se analisar o fluxo do projeto.
Aqueles com maior impacto devem ser categorizados como _should-have_, e os outros como _could-have_.

Esses requisitos só devem ser incluídos no projeto quando todos os requisitos com maior importância foram satisfeitos.

## Won't-have

São aqueles que não tem importância significativa para o projeto.
A presença ou ausência desses requisitos não tem impacto na conclusão satisfatória do projeto.

Categorizar requisitos nessa categoria ajuda a diminuir o escopo das funcionalidades.

# First Things First

## Introdução

_First Things First_ é uma técnica de priorização onde há um levantamento dos benefícios, custos e riscos associados a cada requisito.
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


# Metodologia Escolhida - MoSCoW

A metodologia escolhida pelo grupo foi a _MoSCoW_, devido à sua facilidade de implementação e eficiência no processo de priorizar os requisitos.
Segue, na _tabela 1_, a priorização dos requisitos elicitados nos processos anteriores:

| ID    | Requisito                                                                                                                             | Priorização |
|-------|---------------------------------------------------------------------------------------------------------------------------------------|-------------|
| ITP01 | Para primeiro acesso dos usuários, deve ter uma breve explicação sobre o aplicativo e as funcionalidades                               | Should      |
| ITP02 | O usuário deve conseguir fazer o alistamento pelo próprio aplicativo                                                                  | Should      |
| ITP03 | O usuário que trabalhe no exército deve possuir um cadastro para ter acesso a informações individuais e avisos internos               | Must        |
| ITP04 | O usuário poderá acessar os concursos abertos com uma explicação e os links para inscrição                                            | Must        |
| ITP05 | O usuário poderá acessar os uniformes e pedi-los pelo próprio aplicativo                                                              | Should      |
| ITP06 | O usuário poderá visualizar as últimas notícias do exército                                                                           | Must        |
| ITP07 | O usuário poderá visualizar os colégios militares existentes próximos da sua região                                                   | Must        |
| ITP08 | O sistema apenas deve perguntar se o usuário permite o acesso da localização para funcionalidades que desta necessitem                | Should      |
| ITP09 | O aplicativo deve abrir em um tempo de até 5 segundos                                                                                 | Should      |
| ITP10 | O aplicativo deve ter um botão de ajuda para possíveis dúvida                                                                         | Could       |
| ITP11 | O usuário deve conseguir falar com a inteligência artificial do exército pelo próprio aplicativo ou pelo Whatsapp                     | Could       |
| ITP12 | O aplicativo deve abrir em um tempo limite de até 5 segundos                                                                          | Must        |
| ITP13 | O aplicativo deve ter um botão de ajuda para possíveis dúvidas                                                                        | Should      |
| ITP14 | O usuário deve conseguir falar com a inteligência artificial do exército pelo próprio aplicativo ou por um aplicativo de mensagens    | Should      |
| ITP15 | O usuário deve conseguir acessar o aplicativo em qualquer aparelho mobile                                                             | Must        |
| ITP16 | O usuário poderá acessar todas as redes sociais do exército brasileiro                                                                | Must        |
| ITP17 | O usuário que já possua carteira de identidade militar deve conseguir acessá-la pelo aplicativo                                       | Must        |
| BF1   | Ter acesso à informações atualizadas                                                                                                  | Must        |
| BF2   | Processo de alistamento                                                                                                               | Should      |
| BF3   | Visualizar status de serviços solicitados                                                                                             | Must        |
| BF4   | Cadastrar e visualizar carteira de identificação do exército                                                                          | Could       |
| BF5   | Visualizar certificado de reservista                                                                                                  | Should      |
| BF6   | Encontrar informações sobre o processo de alistamento                                                                                 | Should      |
| BNF1  | O sistema deve ser rápido                                                                                                             | Must        |
| BNF2  | O sistema deve ser fácil de usar                                                                                                      | Must        |
| BF7   | Encontrar local de alistamento mais próximo                                                                                           | Should      |
| BF8   | Ouvir podcasts sobre temas do exército                                                                                                | Should      |
| BF9   | Ler histórias militares                                                                                                               | Could       |
| BNF3  | O aplicativo deve funcionar na maioria dos aparelhos em uso                                                                           | Must        |
| BF10  | Ser capaz de entrar em contato com algum representante do Exército                                                                    | Should      |
| BF11  | Ser capaz de oferecer várias funcionalidades sem coletar dados de usuário                                                             | Must        |
| BNF4  | Oferecer funcionalidades offline                                                                                                      | Must        |
| BNF5  | Ser minimalista                                                                                                                       | Must        |
| BNF6  | Centralizar informações relativas ao processo de alistamento                                                                          | Must        |
| RO1   | O usuário deve ser capaz de usar o aplicativo com fluidez.                                                                            | Must        |
| RO2   | O usuário deve ser capaz de abrir e usar o app.                                                                                       | Must        |
| RO3   | O usuário deve ser capaz de fazer login para usar os serviços.                                                                        | Must        |
| RO4   | O usuário deve ser capaz de consultar o status ou situação do serviço que ele usou                                                    | Should      |
| RO5   | O usuário deve ser capaz de pedir a segunda via de documentos, mesmo mediante pagamento                                               | Must        |
| RO6   | O aplicativo deve fazer o usuário sentir-se seguro ao utilizar o aplicativo.                                                          | Must        |
| RO7   | O usuário deve ser capaz de utilizar o aplicativo sem fornecer acesso à localização.                                                  | Must        |
| RO8   | O usuário deve ser capaz de encerrar a execução das mídias do aplicativo ao fechar o aplicativo.                                      | Must        |
| RE1   |  O usuário quer fluidez ao usar o aplicativo                                                                                          | Must        |
| RE2   |  O aplicativo deve ter uma interface moderna e simples                                                                                | Must        |
| RE3   |  O usuário deve ser capaz de acessar o certificado de reservista                                                                      | Must        |

<center><figcaption>Tabela 1: Priorização dos requisitos</figcaption><center>

## Bibliografia

> rfc2119 -- Bradner, S., "Key words for use in RFCs to Indicate Requirement Levels," RFC 2119, March 1997.

> Método MosCoW. Voitto - BR, 01 ago. 2021. Disponível em https://www.voitto.com.br/blog/artigo/metodo-moscow

> First Things First: Prioritizing Requirements. E.Wiegers, Karl. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf

## Histórico de Versão

| Versão | Data | Descrição | Autor | Revisor |
|--------|------|-----------|-------|---------|
| 0.1 | 11/07/22 | Descrição MoSCoW | Guilherme Puida | --- |
| 0.2 | 13/07/22 | Descrição First Things First | Guilherme Puida | --- |
| 0.3 | 13/07/22 | Priorização dos requisitos elicitados | Guilherme Puida | --- |

