# currency-quote-api

<h3>API desenvolvida para realizar a conversão de moedas, utilizando cryptocompare para taxa de câmbio, desenvolvido em NodeJs</h3>

<h4>Conteúdo do projeto</h4>

- <b>Dois endpoints:</b> Currency e Quote.

- `/currency` responsável pelo CRUD das moedas suportadas pela API.
- `/quote` responsável por realizar a conversão entre duas moedas.

- Processo separado em models, controllers e routes para ambos os endpoints.

- Utilizado API **cryptocompare** para realizar as verificação de moedas válidas, e para obter a taxa de câmbio de cada moeda.

- Adicionado tratamento para não permitir inserção de moedas duplicadas.

- Evidências de testes disponíveis na pasta <b>tests</b>.

- <b>Framework utilizado:</b> Express.

<hr>

<h4>Testes da API realizados utilizando Postman:</h4>

<h5>Método GET:</h5>

- Listagem de moedas: `/currency`
- Consulta de planos por código: `/currency/:code`
- Conversão de moedas: `/quote?from=BRL&to=CAD&amount=10`

<h5>Métodos POST e DELETE:</h5>

- Para cadastro e exclusão: `/currency/:code`

<hr>
<h4>Utilização da API:</h4>

- git clone `https://github.com/raphael-ferreira/currency-quote-api.git`
- cd `currency-quote-api`
- npm i
- npm start

<hr>
> Desenvolvido por: Raphael D. Ferreira
