# <center> Backlog

## Introdução

<div align="justify">&emsp;&emsp;
        O registro pendente de trabalhos (Backlog) é um artefato que consiste em uma lista, geralmente no formato de tabela, contendo a 
        descrição de todas as funcionalidades desejadas para um determinado produto. Tais descrições possuem alta granularidade, isto é, baixo grau de detalhamento, 
        além de evidenciarem os requisitos funcionais e não funcionais de um projeto, os quais são priorizados de acordo com o valor agregado ao cliente.
        <br>&emsp;&emsp;
        Sendo assim, 
        essas descrições podem se dividir em uma ou mais tarefas a serem desenvolvidas pela equipe de desenvolvimento, facilitando a definição do que deve ser feito em cada sprint. 
        Além disso, vale ressaltar que este artefato é um documento dinâmico, visto que o mesmo evoluir em conjunto com o desenvolvimento do projeto. Em outras palavras,
        mudanças devem ocorrer caso surjam novas necessidades que satisfaçam o cliente.
</div>

## Scrum

<div align="justify">&emsp;&emsp;
        O Scrum consiste em um método de desenvolvimento ágil de software cujos princípios são consistentes com o manifesto ágil e são usados para orientar as atividades de desenvolvimento dentro de um processo que incorpora as seguintes atividades estruturais: requisitos, análise, projeto, evolução e entrega.
        <br>&emsp;&emsp;
        Sendo assim, Em cada atividade metodológica, ocorrem tarefas a realizar dentro de um padrão de processo chamado sprint. Somado a isso, o trabalho realizado dentro de um sprint, além de ser definido pela equipe Scrum, é adaptado ao problema em questão. É nesse contexto que, o product backlog, consiste em um dos principais artefatos ligados a metodogia scrum.
        <br>&emsp;&emsp;
        A figura 1 a seguir, retirada do livro Engenharia de Software de Pressman, explica com mais detalhes o fluxo geral do processo Scrum.	
</div>

![image](https://user-images.githubusercontent.com/72039007/181885570-f9ecd2f3-d3f6-45c9-85ca-fd01edbf5ad1.png)	

<p>figura 1: fluxo do processo Scrum - Cap. 3 Desenvolvimento Ágil - Engenharia de Software, Pressman - Página 96<p/>

## SAFe (Scaled Agile Framework)

<div align="justify">&emsp;&emsp;
	O SAFe consiste em uma framework baseada em processos ágeis, tais como o scrum, que permite escalar práticas ágeis em corporações ou grandes projetos. Tal framework propõe um mecanismo definindo diferentes níveis de times cuja dinâmica varia considerando a importância da prioridade e a previsão de entrega.
        <br>&emsp;&emsp;
        Sendo assim, o backlog do produto é um dos artefatos de máxima importância dentro dessa framework, visto que é a partir dele que outras atividades, de menor granularidade, são derivadas e priorizadas.
</div>

## Metodologia
	
<div align="justify">&emsp;&emsp; 
	A tabela 1 expressa a primeira versão do backlog do aplicativo Exército Brasileiro. Observe que tal artefato leva em consideração histórias dos usuários com eventuais comentários que auxiliam seu entendimento, assim como um identificador único denominado ID, o tipo do requisito modelado e sua prioridade.
        <br>&emsp;&emsp;
        Para realizar a confecção dessa tabela e da tabela 2, foi utilizado o método da entrevista, levando em conta a <b>Persona 1</b> criada nesse mesmo projeto. Podemos encontrar o vídeo dessa entrevista a seguir, juntamente com um arquivo que representa a transcrição dessa entrevista.
</div>

#### Vídeo

[![LINK ENTREVISTA BACKLOG](http://img.youtube.com/vi/33XM100vzRE/0.jpg)](https://www.youtube.com/watch?v=33XM100vzRE)

[Link do Vídeo](https://www.youtube.com/watch?v=33XM100vzRE)


#### Transcrição

[Entrevista - Backlog - Exército Brasileiro](https://github.com/Requisitos-de-Software/2022.1-Exercito-Brasileiro/files/9255774/Entrevista.-.Backlog.-.Exercito.Brasileiro.pdf)
	
#### Backlog - Versão 1
	
A seguir, encontra-se a tabela em questão:
<br>
<table cellspacing="0" border="0" class="table table-striped table-bordered table-responsive-sm" style="font-size: 10px;">
	<colgroup width="24"></colgroup>
	<colgroup width="95"></colgroup>
	<colgroup width="144"></colgroup>
	<colgroup width="342"></colgroup>
	<colgroup width="304"></colgroup>
	<colgroup width="85"></colgroup>
	<colgroup width="110"></colgroup>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">ID</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Tipo</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Eu, como</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Gostaria de </font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Para que eu possa</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Comentários </font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Prioridade</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">1</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar o youtube oficial do exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">assistir vídeos online do exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">2</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar o sistema do exercito responsável pela carteira de identidade militar</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">solicitar minha segunda via</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FF0000"><b><font color="#000000">Alta</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">3</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar os podcasts do exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">conhecer figuras importantes do exército brasileiro brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>	</tr>
 </tr>
 <tr>
		<td align="center" valign=bottom><b><font color="#000000">4</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar a rádio verde oliva</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acompanhar as noticias via rádio sobre o exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>	</tr>
  </tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">5</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">ler noticiário sobre o exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">obter as informações mais atuais sobre o exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FFFF00"><b><font color="#000000">Média</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">6</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">obter informações sobre os sistemas digitais disponíveis pelo exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">verificar os serviços online ofercidos pelo exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Alistamento online, Identidade militar, EBMail, etc.</font></b></td>
		<td align="center" valign=bottom bgcolor="#FF0000"><b><font color="#000000">Alta</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">7</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">obter informações sobre os concursos oferecidos pelo exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">escolher qual concurso irei me inscrever</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FF0000"><b><font color="#000000">Alta</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">8</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar o sistema do exercito responsável pelo alistamento militar</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">realizar meu alistamento militar online</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FF0000"><b><font color="#000000">Alta</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">9</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar o facebook oficial do exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acompanhar as postagens do exército</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>	</tr>
  </tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">10</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar o sistema do exercito responsável pela reserva ativa</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">encontrar um emprego</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FF0000"><b><font color="#000000">Alta</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">11</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">obter informações sobre resultados dos processos seletivos do exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">verificar se eu passei no concurso o qual me inscrevi</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FFFF00"><b><font color="#000000">Média</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">12</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar o blog oficial do exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acompanhar as notícias sobre o exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">13</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar o sistema do exercito responsável pela Revista Verde Oliva</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">baixar uma edição da Revista Verde Oliva de minha preferência </font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>
	</tr>
    <tr>
		<td align="center" valign=bottom><b><font color="#000000">14</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">obter informações sobre os uniformes disponíveis pelo exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">escolher qual uniforme irei comprar</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FFFF00"><b><font color="#000000">Média</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">15</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">obter informações sobre os diferentes hotéis de trânsito disponíveis pelo exército brasileiro</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">decidir qual hotel irei me hospedar</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">16</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">obter informações sobre o aplicativo</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">aprender como utilizá-lo</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">17</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Não funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar as informações sobre o exército brasileiro em um único lugar</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">me atualizar sobre o exército brasileiro de uma maneira mais prática</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FF0000"><b><font color="#000000">Alta</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">18</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Não funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">que o aplicativo seja disponível tanto para IOS quanto para android</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">baixar o aplicativo em meu smartphone</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FF0000"><b><font color="#000000">Alta</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">19</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Não funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">que o aplicativo permitisse o acesso às informações sem a necessidade de internet</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">obter informações sobre o exército brasileiro sem a disponibilidade de internet</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#00FF00"><b><font color="#000000">Baixa</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">20</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Não funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">conseguir aprender a utilizar as funcionalidades do aplicativo de forma intuitiva</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">atender meu obtivo sem a necessidade de um treinamento prévio</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FFFF00"><b><font color="#000000">Média</font></b></td>
	</tr>
  <tr>
		<td align="center" valign=bottom><b><font color="#000000">21</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">Não funcional</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">usuário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">acessar o conteúdo do aplitivo a qualquer momento do dia</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000">atender meu objetivo quando eu achar necessário</font></b></td>
		<td align="center" valign=bottom><b><font color="#000000"> </font></b></td>
		<td align="center" valign=bottom bgcolor="#FF0000"><b><font color="#000000">Alta</font></b></td>
	</tr>
</table>
<p align="center">Tabela 1: Product Backlog v1 - Exército Brasileiro<p/>

#### Backlog - Versão 2

Posteriormente, encontramos um modelo que faria mais sentido para o nosso projeto, por já englobar os épicos, as features e dividi-las de forma a facilitar o entendimento. Sendo assim, foi feita uma segunda versão para o backlog do projeto, que contém hyperlinks para as histórias de usuários definidas e para os épicos. Podemos visualiza-lo na _Tabela 2_
<table cellspacing="" border="0" class="table table-striped table-bordered table-responsive-sm" style="font-size: 16px">
    <thead>
        <tr>
            <th style="text-align:center">Épico</th>
            <th style="text-align:center">Feature</th>
            <th style="text-align:center">US ID</th>
            <th style="text-align:center">História de Usuário</th>
	    <th style="text-align:center">Prioridade</th>
	   <th style="text-align:center">Tipo</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="2"><a
                    href="./#/modelagemRequisitos/epicos?id=Épico-01-notícias">Épico 01 - Notícias </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Notíciário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us01">US01</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um novo
                usuário do sistema, desejo ler notícias sobre o exército brasilileiro para que eu possa obter
                informações mais atuais.</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">Blog
            </td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us02">US02</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um
                usuário do sistema, desejo acessar o blog oficial do exército brasileiro para acompanhar as notícias
                sobre o exército brasileiro</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="11"><a
                    href="./#/modelagemRequisitos/epicos?id=Épico-02-informações">Épico 02 - Informações </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="3">
                Concursos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us03">US03</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um
                usuário do sistema, desejo acessar informações sobre os concursos abertos para que eu possa saber qual
                concurso quero me inscrever.</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us04">US04</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um
                usuário do sistema, desejo acessar links de inscrição dos concursos abertos para que eu possa me
                inscrever</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Must</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us05">US05</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo obter informações sobre resultados dos processos seletivos do exército brasileiro para verificar
                se eu passei no concurso o qual me inscrevi.</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">
                Uniformes</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us06">US06</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um
                usuário do sistema, desejo obter informações sobre os uniformes disponíveis pelo exército brasileiro
                para que eu possa escolher um para comprar</td>
	   <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">Hotéis
            </td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href"./#/modelagemRequisitos/userstories?id=us07">US07</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um
                usuário do sistema, desejo obter informações sobre os diferentes hotéis de trânsito disponíveis pelo
                exército brasileiro decidir qual hotel irei me hospedar</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Could</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="3">
                Orientações/Atendimento</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us08">US08</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo entrar em contato com o com a MAX, inteligência artificial do exército brasileiro, para resolver
                algum problema ou tirar uma dúvida </td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us09">US09</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo entrar em contato com o com o exército brasileiro pelo email, para resolver algum problema ou
                tirar uma dúvida </td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Must</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us10">US10</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo obter informações sobre o aplicativo para que eu possa aprender como utiliza-lo.</td>
	     <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
	     <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="2">
                Postagens</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us11">US11</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo acessar o youtube oficial do exército brasileiro para que eu possa assistir vídeos online do
                exército brasileiro </td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Could</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us12">US12</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo acessar o facebook oficial do exército brasileira para que eu possa acompanhar as postagens do
                exército.</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Could</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">
                Reserva Ativa</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us13">US13</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo acessar o sistema do exercito responsável pela reserva ativa para que eu possa encontrar um
                emprego</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
	<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="3"><a
                    href="./#/modelagemRequisitos/epicos?id=Épico-03-entretenimento">Épico 03 - Entretenimento </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">Rádio
            </td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us14">US14</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuario,
                desejo acessar a rádio verde oliva para ouvir músicas e notícias.</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Could</td>
	   <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">
                Podcast</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us15">US15</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário
                ,desejo acessar os podcast do exército brasileiro para conhecer figuras importantes e
                hitórias do exército</td>
	   <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Could</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">
                Revista</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us16">US16</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
               desejo acessar o sistema do exercito responsável pela Revista Verde Oliva para que eu possa
                baixar uma edição da Revista Verde Oliva de minha preferência</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Could</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="2"><a
                    href="./#/modelagemRequisitos/epicos?id=Épico-04-alistamento">Épico 04 - Alistamento </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">
                Realizar alistamento</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us17">US17</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuario,
                desejo acessar o sistema de alistamento do exército brasileiro para que eu possa me alistar.</td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Must</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">Status
            </td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us18">US18</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário
                já alistado, desejo verificar o status do meu alistamento para que eu possa acompanhar e me apresentar
                nas datas agendadas </td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Must</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="3"><a
                    href="./#/modelagemRequisitos/epicos?id=Épico-05-carteira-de-identificação-de-militar">Épico 05 - Carteira de Identificação de militar </a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="2">
                Autenticar</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us19">US19</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo me autenticar no sistema com minha identidade militar e a minha senha</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Must</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us20">US20</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo recuperar a minha senha esquecida para que eu possa acessar minha identificação</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Must</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="1">
                Acessar</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us21">US21</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como um
                usuário do sistema, desejo acessar o sistema de carteira de identificação para que eu possa pedir a
                minha segunda via</td>
	   <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Must</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="5"><a
                    href="./#/modelagemRequisitos/epicos?id=Épico-06-utilidade">Épico 06 - Utilidade</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="5">
                Disponibilidade</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us22">US22</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo que o aplicativo permitia o acesso às informações sem a necessidade de internet, desde que sejam funcionalidades internas, para que eu possa obter informações sobre o exército brasileiro sem a disponibilidade de internet </td>
	    <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Could</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Não funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us23">US23</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo acessar o conteúdo do aplicativo, desde que não sejam funcionalidades externas, a qualquer momento do dia para que eu possa atender meu objetivo
                quando eu achar necessário.</td>
	   <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Should</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Não funcional</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a
                    href="./#/modelagemRequisitos/userstories?id=us24">US24</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Eu, como usuário,
                desejo acessar as informações sobre o exército brasileiro em um único lugar me atualizar sobre o
                exército brasileiro de uma maneira mais prática.</td>
	<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Must</td>
		<td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Não funcional</td>
        </tr>
    </tbody>
</table>
<p align="center">Tabela 2: Product Backlog v2 - Exército Brasileiro<p/>

## Referências
> - SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;
> - Pressman; Engenharia de Software; Desenvolvimento Ágil - Capítulo 3 - Páginas 95 e 96
> - https://www.youtube.com/watch?v=z4ubaBwjCsU&feature=youtu.be

### Histórico de versão

| Versão | Data       | Descrição                                 | Autor        | Revisor |
| ------ | ---------- | ----------------------------------------- | ------------ | -------- |
| 0.1    | 24/07/2022 | Criação do documento                      | Gustavo Martins e Gabriel Moretti | Adne Moretti
| 0.2    | 03/08/2022 | Adição da segunda versão do backlog                    | Adne Moretti | Gustavo Martins
