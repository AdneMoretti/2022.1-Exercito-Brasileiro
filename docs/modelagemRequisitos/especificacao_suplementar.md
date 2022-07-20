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

## Funcionalidades
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
