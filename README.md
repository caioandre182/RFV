# RFV - Referência, Frequência e Valor

Projeto para consolidar o conhecimento na técnica RFV.

## Descrição do projeto

<b>RFV</b> é uma técnica de segmentação para agrupar clientes com caractéristicas parecidas.
<ul>
<li><b>Recência</b> -> Última vez que o cliente utilizou/comprou o serviço/produto, <i>quanto menor for o valor, melhor para a empresa</i>, significa que é um cliente ativo.</li>
<li><b>Frequência</b> -> A quantidade de vez que o cliente utilizou/comprou um serviço ou produto, <i>quanto menor for o valor, melhor para a empresa</i>.</li>
<li><b>Valor</b> -> O montante em dinheiro que o cliente gastou com serviços/produtos da empresa, <i>quanto menor for o valor, melhor para a empresa</i>.</li>
</ul>
Segmentando os grupos, em 4 categorias, <code>(A,B,C,D)</code>, a partir da técnica de Quartis, podemos determinar campanhas de marketing, se vale a pena ou não insistir em um determinado grupo de clientes, diversos usos são aplicados.

## Utilização

### Dependencias

<ul>
	<li>pandas -U</li>
	<li>streamlit -U</li>
	<li>install xlsxwriter -U</li>
</ul>

### Executando o projeto

O projeto está hospedado no heroku, pode ser acessado clicando <a href="https://rfv-test.herokuapp.com/">aqui</a>.

O arquivo .csv para realizar a segmentação, estará disponível no repositório do github<a href=""></a>.


## Autores

[@CaioAndre](https://github.com/caioandre182)
