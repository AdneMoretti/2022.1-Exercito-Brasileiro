# Especificação suplementar

## 1. Introdução
Trata-se de um documento em linguagem natural, no qual são explicitados e modelados os requisitos não funcionais, a fim de que fiquem claras as restrições de usabilidade, confiabilidade, funcionalidade, performance e suportabilidade do sistema. 

## 2. Metodologia

Para a definição dos requisitos não funcionais do Exército Brasileiro foi utilizado o FURPS+, que é uma metodologia para definição de requisitos não funcionais de um sistema, sendo os tópicos analisados por esse:

FURPS (_tabela 1_):

<div align="center">
<figcaption>
Tabela 1 - Descrição da sigla FURPS
</figcaption>
</div>
<br>


| Funcionalidade | Significado |
| -------------- | ----------- |
| Funcionalidade | Se trata de requisitos funcionais, as reais funcionalidades de um sistema |
| Usabilidade    | Se trata do quão fácil é para o usuário realizar as suas tarefas |
| Confiabilidade | Se trata do quão confiável o software foi desenhado|
| Performance    | Desempenho do software. É rapido ou não? |
| Suportabilidade | Várias características envolvidas, como manutenibilidade, internacionalização, portabilidade, adaptabilidade, configurabilidade |

Plus: 
- Requisitos de interface: Tratam-se das necessidades não funcional que a interface e design do aplicativo deverão cumprir;

## 3. Avaliações

Para a realização da especificação suplementar, buscamos pelas avaliações dos usuários nas plataformas disponíveis para baixar para encontrar os principais problemas e elicitar requisitos não-funcionais relacionados a usabilidade, confiabilidade e performance que possibilitem a mkelhora da experiência do usuário.

<img src='https://user-images.githubusercontent.com/64036847/180097194-6b97087d-2bd2-470a-9e01-2b205ae94cb2.png' width=550px></img>

<img src='https://user-images.githubusercontent.com/64036847/180097390-151f63d7-2109-451b-85bd-9f1fe605a6a0.png' width=550px></img>

<img src='https://user-images.githubusercontent.com/64036847/180103122-153c45c8-9740-4fee-9e3b-f97ef688ab9d.png' width=550px></img>

<img src='https://user-images.githubusercontent.com/64036847/180103115-0459d1fe-709c-476d-b021-4128cf625c4f.png' width=550px></img>

<img src='https://user-images.githubusercontent.com/64036847/180097410-dce79721-0cb9-4b07-ba55-cee8e495f40a.png' width=550px></img>

<img src='https://user-images.githubusercontent.com/64036847/180097885-2b42fb49-8df8-40bd-a03c-52ad70540dd3.jpeg' width=550px></img>

<img src='https://user-images.githubusercontent.com/64036847/180097894-4158d2b3-6f7f-4079-904a-520ba9dd6261.jpeg' width=550px></img>

Observamos que o aplicativo possui muitos problemas relacionados a usabilidade, performance e dados no banco de dados incorretos. É observável que muitos usuários passam pelos problemas apresentados, pois em uma avaliação vários usuários acabam marcando tal comentário como útil.
## 4. FURPS+
## __Funcionalidades__
As funcionalidades do sistema estão descritas nos casos de uso desenvolvidos e nas técnicas de elicitação de requisitos realizadas nessa documentação. Para melhor visualização, seguem os links para tais abas:

- [Casos de uso](/modelagemRequisitos/casos_de_uso.md)
- [Elicitação de Requisitos (priorização)](/elicitacaoRequisitos/priorizacao.md)

## __Usabilidade__

### Interface intuitiva
Ao acessar o aplicativo Exército Brasileiro, o sistema deve apresentar uma interface intuitiva e de fácil entendimento, não sendo necessário um tutorial para primeiro uso. Para o acesso de todas as funcionalidades do sistema, basta um botão do lado esquerdo da tela inicial que, ao ser clicado, apresente todas as possíveis funcionalidades do Exército Brasileiro em um menu iterativo.

### Facilidade de memorização
O aplicativo deve apresentar elementos simples e padronizados, para facilitar a memorização e distinção por parte do usuário, para que, mesmo após um tempo sem utilizá-lo, este se recorde das funcionalidades e caminhos dos mesmos.

### Segurança
O aplicativo deve evitar que o usuário cometa erros, sendo assim, quando o usuário clicar em qualquer botão ou funcionalidade existente, o aplicativo deve dar a possibilidade de voltar para a tela anterior ou cancelar o processo em questão, transmitindo segurança ao usuário.

### Linguagem do aplicativo
O aplicativo deve apresentar uma linguagem simples e não técnica, para que o entendimento por parte dos usuários seja simples, rápida e fácil.

## __Confiabilidade__

### Tratamento e armazenamento de dados
Para qualquer dado armazenado pelo aplicativo, o mesmo deve considerar as seguintes questões:
- Baixa frequência, extensão, duração e gravidade de falhas no armazenamento ou retorno;
- Possibilidade de recuperação de dados em caso de falha;
- Prevenção de falhas;
- Somente o usuário terá acesso às informações e rotas inseridas no aplicativo, de forma que sua privacidade seja mantida.

### Garantia de disponibilidade

Enquanto o dispositivo em uso possuir acesso à internet, o aplicativo deverá funcionar constantemente, de forma completa e correta.

## __Suportabilidade__

### Compatibilidade 
O aplicativo deve ser compatível aos seguintes dispositivos e suas versões:
- Android (5.0 e versões mais recentes);
- Iphone (IOS 12.0 ou versão posterior);
- Ipad (IPadOS 12.0 ou posterior);
- Ipod touch (IOS 12.0 ou posterior);
- Mac (macOS 11.0 ou posterior ou com chip M1 ou posterior).

## __Performance__

### Armazenamento 
Para baixar o aplicativo, deve estar disponível no dispositvido 52,5 MB, que é a quantidade de memória necessária para o armazenamento do aplicativo.

### Tempo de resposta
O tempo de resposta do aplicativo deve ser de no máximo 1 segundo para que o usuário tenha uma experiência agradável com o aplicativo.

### Energia
O aplicativo deve consumir pouca energia do dispositivo quando utilizado por um grande período de tempo, em uma margem aceitável de 10% de bateria por hora de uso em um aparelho pouco usado, assim permitindo o uso do mesmo de forma livre e sem preocupações.

## __Requisitos de Interface__

### Idioma
Por ser um aplicativo do Governo Brasileiro destinado apenas para fins nacionais, o aplicativo deve estar somente em português brasileiro (PT-BR).

### Cor

As cores padrões da interface utilizadas devem seguir o tema do exército brasileiro, em variações de verde, geralmente verde-oliva, e bege.

## Referência bibliográfica
>[1] - SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13;<br>
>[2] - https://qualidadebr.wordpress.com/2008/07/10/furps/

## Histórico de Versão

| Versão | Data | Descrição | Autor | Revisor |
|--------|------|-------|-----------| ------- |
| 0.1 | 18/07/22 | Documento Inicial | Adne Moretti | Gabriel Moretti |
| 0.2 | 19/07/22 | Adição de elementos aos requisitos | Gabriel Moretti | Adne Moretti |
| 0.2 | 19/07/22 | Adição de exemplos de avaliações | Adne Moretti | Gabriel Moretti |
