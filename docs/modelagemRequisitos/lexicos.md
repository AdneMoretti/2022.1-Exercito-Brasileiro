# 1 - Léxicos

Trata-se de uma técnica que procura descrever os símbolos de uma linguagem.
O Objetivo principal a ser perseguido pelos engenheiros de requisitos é a identificação de palavras ou frases peculiares ao meio social da aplicação sob estudo.

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
| Verbo | Quem realiza,quando acontece e quais os procedimentos envolvidos | Quais os reflexos da ação no ambiente e quais novos estados decorrentes |
| Objeto | Definir o objeto e definir com quais outros objetos ele se relaciona | Ações que podem ser aplicadas no objeto |
| Estado | Quais ações levaram a esse estado | Identificar outros estados a ações que podem ocorrer a partir do estado que se descreve |

### Léxicos

| Léxico | Noção | Impacto | Sinônimo |Classificação |
|--------|-------|---------|----------|--------------|
| **Alistar** | O usuário pode fazer o alistamento obrigatório pelo aplicativo | O usuário consegue se alistar | Relacionar,Inscrever, Enumerar | Verbo |
| **Carteira Militar** | O usuário consegue consultar sua carteira militar | O usuário tem sua carteira militar de forma digital e de fácil acesso | Identificação Militar | Objeto |
|**Acessar** | O usuário consegue se conectar aos serviços | O usuário usa os serviços que deseja usar, como por exemplo, alistamento militar | Entrar, Conectar | Verbo |
| **Colégios Militares** | Seção que discute sobre os colégios militares | Usuário poderá se informar sobre os colégios militares | Escolas militares, Instituições de ensino militarizadas | Objeto | 
| **Escutar Podcast** | Aba de podcast para o usuário escutar podcast relevantes para o exército brasileiro | O usuário poderá escutar sobre assuntos que lhe interessa e se informar | Ouvir Podcast | Verbo |
| **Ler Notícias** | O usuário consegue visualizar as notícias relevantes ao exército brasileiro | O usuário consegue se informar sobre concursos públicos, ingresso em colégios e se manter atualizado | Se informar | Verbo |
| **Concursos** | O usuário é capaz de se informar sobre concursos | O usuário fica sabendo das informações necessárias sobre os concursos | Processos seletivos | Objeto |


Certificado de reservista
Carteira Militar
Alistamento
Uniforme 
Usuário
Acessar
Colégios militares
Guarda
Veterano
Operacional
Escutar Podcast
Ler notícias
Concursos


| Versão | Data | Descrição | Autor | Revisor |
|--------|------|-------|-----------| ------- |
| 0.1 | 18/7/22 | Documento Inicial | Luan Vasco| Gustavo Martins |
