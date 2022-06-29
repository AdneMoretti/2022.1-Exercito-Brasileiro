# Metodologia

## Métodos Ágeis
Os métodos ágeis se baseiam em uma abordagem incremental para a especificação, (Sommerville, Ian; ) o desenvolvimento e a entrega do software. Eles são mais adequados ao desenvolvimento de aplicativos nos quais os requisitos de sistema mudam rapidamente durante o processo de desenvolvimento (Sommerville, Ian).

![desenv_agil](https://user-images.githubusercontent.com/56610229/176553362-597e2271-9784-4a00-8890-7ce80a0839f5.png)
<figcaption>Imagem 1: Princípios dos métodos ágeis, retirado do livro "Engenharia de Software" de Ian Sommerville.</figcaption>

## Scrum
No SCRUM, o foco está no gerenciamento do desenvolvimento iterativo, ao invés das abordagens técnicas específicas da engenharia de software ágil.

## Pair Programming
O Pair Programming consiste em duas pessoas trabalhando nas mesmas linhas de código e se ajudando mutuamente. Uma escreve as linhas de código, enquanto a outra fica de observadora analisando e percebendo possíveis problemas no código. De tempo em tempo definido as posições são trocadas. Essa técnica é eficiente para a elaboração do código de forma limpa e com menos erros, além de não se tornar preocupando o fato de um desenvolvedor tirar férias, por exemplo, pois terá um parceiro que esteve presente o tempo todo.

![xp](https://user-images.githubusercontent.com/56610229/176553394-f0233d20-3fbc-4772-9ec3-802e5c0ba439.png)
<figcaption>Imagem 2: Práticas de Extreme Programming, retirado do livro "Engenharia de Software" de Ian Sommerville.</figcaption>

## Extreme Programming (XP)
Extreme Programming tem como objetivo melhorar a qualidade do software e a capacidade de resposta às mudanças no requisitos dos clientes. Nesse método, também foi enfatizado o conceito de "Pair Programming" que consiste em duas pessoas trabalhando nas mesmas linhas de código, uma como obervadora e outra como programadora, tendo suas funções trocadas de tempo em tempo. Os programadores também desenvolvem testes para cada tarefa antes de escreverem o código.


## Git Flow
O Gitflow é um conceito abstrata do fluxo de trabalho Git, que dita que tipos de ramificações configurar e como fazer o merge.

Fluxo de trabalho:

    1) Deve-se criar uma branch nova a partir da main.
    2) Ao acabar a implementação na branch nova, deve ser criado um pull request para ser avaliado, preenchendo os campos necessários do modelo pré-determinado. Lembrando que cada pull request é uma oportunidade de revisar o código.
    3) Caso a solicitação de pull request seja aprovada, a branch nova branch remota será deletada e seu conteúdo fará parte da main.

## Referências Bibliográficas

> - Sommerville, Ian. **Engenharia de software**. 10. ed. São Paulo: Pearson Addison Wesley, 2019.

> - Metodologias ágeis: o que é Pair Programming?. **Programadores Brasil**, 2020. Disponível em: https://programadoresbrasil.com.br/2020/04/o-que-e-pair-programming/

## Histórico de versão

| Versão | Data       | Descrição                                 | Autor        |
| ------ | ---------- | ----------------------------------------- | ------------ |
| 0.1    | 29/06/2022 | Criação do documento                      | Vitor        |
