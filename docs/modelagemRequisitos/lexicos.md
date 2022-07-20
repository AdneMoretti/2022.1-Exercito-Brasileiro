# 1 - <center> Léxicos

As atividades associadas ao processo de requisitos podem envolver leitura de documentos que impactem de alguma forma o sistema em desenvolvimento. Exemplos de documentos incluem padrões da organização, legislação pertinente, atas de reuniões ou entrevistas ocorridas durante o processo de elicitação e também o próprio documento de requisitos sendo elaborado. Nesse processo, a construção do léxico da aplicação é tarefa prioritária, pois nele são registrados os símbolos próprios do domínio da aplicação. O léxico é a base para o entendimento entre clientes, usuários e profissionais de software [Sayão, Carvalho, 2006]. É nesse contexto que, um léxico, consiste em uma técnica que procura descrever os símbolos de uma linguagem e, de acordo com o fato emncionado, é um dos principais objetivos a ser perseguido pelos engenheiros de requisitos, pois facilita a identificação de palavras ou frases peculiares ao meio social da aplicação sob estudo..

## 2 - Descrição 

Cada símbolo é descrito com noção e impacto.
    - Noção: é o que significa o símbolo.
    - Impacto : descreve efeito/uso/ocorrência do símbolo na aplicação ou do efeito de algo na aplicação.

## 3 - Regras gerais

    - Cada símbolo tem zero ou mais sinônimos.
    - Cada símbolo tem uma ou mais noções.
    - Cada símbolo tem um ou mais impactos.

# 4 - Metodologia 

Observando o aplicativo do Exército Brasileiro, serão escolhidos vocábulos e o papel dele dentro do sistema. Os léxicos podem ser do tipo Verbo,Objeto ou Estado.

Padrão de tabela :

| Verbo | Noção | Impacto |
|-------|-------|---------|
| Verbo | Quem realiza, quando acontece e quais os procedimentos envolvidos | Quais os reflexos da ação no ambiente e quais novos estados decorrentes |
| Objeto | Definir o objeto e definir com quais outros objetos ele se relaciona | Ações que podem ser aplicadas no objeto |
| Estado | Quais ações levaram a esse estado | Identificar outros estados a ações que podem ocorrer a partir do estado que se descreve |

### Léxicos

| Léxico | Noção | Impacto | Sinônimo |Classificação |
|--------|-------|---------|----------|--------------|
| **Alistar** | O usuário pode fazer o alistamento obrigatório pelo aplicativo | O usuário consegue se alistar | Relacionar, Inscrever, Enumerar | Verbo |
| **CIM** | O usuário consegue consultar sua carteira militar | O usuário tem sua carteira militar de forma digital e de fácil acesso | Carteira de Identidade Militar | Objeto |
|**Acessar** | O usuário consegue se conectar aos serviços | O usuário usa os serviços que deseja usar, como por exemplo, alistamento militar | Entrar, Conectar | Verbo |
| **Colégios Militares** | Seção que discute sobre os colégios militares | Usuário poderá se informar sobre os colégios militares | Escolas militares, Instituições de ensino militares | Objeto | 
| **Escutar Podcast** | Aba contendo podcasts gravados para o usuário escutar quando desejado | O usuário poderá escutar sobre assuntos que lhe interessa e se informar | Ouvir Podcast | Verbo |
| **Ler Notícias** | O usuário consegue visualizar as notícias relevantes sobre o exército brasileiro | O usuário consegue se informar sobre concursos públicos, ingresso em colégios militares e se manter atualizado | Se informar | Verbo |
| **Concursos** | O usuário é capaz de se informar sobre concursos | O usuário fica sabendo das informações necessárias sobre os concursos | Processos seletivos | Objeto |
| **Escutar Podcast** | Aba contendo podcasts gravados para o usuário escutar quando desejado | O usuário poderá escutar sobre assuntos que lhe interessa e se informar | Ouvir Podcast | Verbo |


| Versão | Data | Descrição | Autor | Revisor |
|--------|------|-------|-----------| ------- |
| 0.1 | 18/7/22 | Documento Inicial | Luan Vasco e Vitor Eduardo| Gustavo Martins |
