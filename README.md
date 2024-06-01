<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Previsão de Vendas de Lojas</title>
</head>
<body>

<h1>Previsão de Vendas de Lojas</h1>

<p>Este projeto tem como objetivo prever as vendas de lojas utilizando dados históricos e vários modelos de aprendizado de máquina. O conjunto de dados utilizado inclui informações sobre vendas, clientes, promoções e concorrência.</p>


<h2 id="uso">Uso</h2>
<p>Após instalar as dependências, você pode executar o script de previsão:</p>
<pre>
<code>
python predict.py
</code>
</pre>

<h2 id="dados">Dados</h2>
<p>O conjunto de dados consiste em dois arquivos principais:</p>
<ul>
    <li><code>train.csv</code>: Dados históricos de vendas incluindo loja, data, vendas, clientes e promoções.</li>
    <li><code>store.csv</code>: Metadados das lojas, incluindo detalhes de concorrência e promoções.</li>
</ul>
<p>Certifique-se de colocar esses arquivos no diretório <code>data/</code> antes de executar o script.</p>

<h2 id="modelo">Modelo</h2>
<p>Este projeto utiliza vários modelos de aprendizado de máquina, incluindo:</p>
<ul>
    <li>Random Forest Regressor</li>
    <li>Regressão Linear</li>
    <li>XGBoost</li>
</ul>
<p>A engenharia de features e a avaliação do modelo são feitas usando validação cruzada. As métricas de desempenho utilizadas são MAE, MAPE e RMSE.</p>

<h2 id="resultados">Resultados</h2>
<p>Os resultados da avaliação do modelo serão exibidos após a execução do script de previsão. As métricas de desempenho são registradas para cada modelo e comparadas para selecionar o modelo de melhor desempenho.</p>

<h2 id="contribuicoes">Contribuições</h2>
<p>Contribuições são bem-vindas! Por favor, faça um fork do repositório e crie um pull request com suas alterações.</p>

<h2 id="licenca">Licença</h2>
<p>Este projeto está licenciado sob a Licença MIT. Veja o arquivo <code>LICENSE</code> para mais detalhes.</p>

</body>
</html>
