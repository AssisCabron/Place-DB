<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="PlaceDB_0"></a>PlaceDB</h1>
<p class="has-line-data" data-line-start="3" data-line-end="4"><a href="https://travis-ci.org/joemccann/dillinger"><img src="https://travis-ci.org/joemccann/dillinger.svg?branch=master" alt="Build Status"></a></p>
<p class="has-line-data" data-line-start="5" data-line-end="6">Esta afim de uma database sem limitação? Voce achou a database perfeita para o seu uso, nossa database foi feita do zero e estamos sempre melhorando.</p>
<h2 class="code-line" data-line-start=7 data-line-end=8 ><a id="Tecnologias_utilizadas_7"></a>Tecnologias utilizadas</h2>
<p class="has-line-data" data-line-start="9" data-line-end="10">PlaceDB usa algumas linguaguens open-source:</p>
<ul>
<li class="has-line-data" data-line-start="11" data-line-end="12">[node.js] - E/S de eventos para o back-end</li>
<li class="has-line-data" data-line-start="12" data-line-end="13">[Express] - Estrutura de aplicativo de rede rápida node.js [@tjholowaychuk]</li>
</ul>
<h2 class="code-line" data-line-start=15 data-line-end=16 ><a id="Exemplos_de_uso_15"></a>Exemplos de uso</h2>
<p class="has-line-data" data-line-start="17" data-line-end="18">Sera necessario utilizar uma key gerada automaticamente quando cria uma database para utilizar nosso sistema .</p>
<p class="has-line-data" data-line-start="19" data-line-end="20">Primeiro crie seu banco de dados.</p>
<pre><code class="has-line-data" data-line-start="22" data-line-end="25" class="language-sh">https://banco-de-dados.rsr4dmnynb.repl.co/database/create/NAME-DB 
Troque o <span class="hljs-string">'NAME-DB'</span> pelo nome <span class="hljs-keyword">do</span> seu Banco de Dados.
</code></pre>
<p class="has-line-data" data-line-start="25" data-line-end="26">Lembre-se, salve a sua Chave de acesso!</p>
<p class="has-line-data" data-line-start="27" data-line-end="28">Crie uma tabela.</p>
<pre><code class="has-line-data" data-line-start="30" data-line-end="34" class="language-sh">https://banco-de-dados.rsr4dmnynb.repl.co/database/create/table/NAME-DB/NAME-TABLE
Lembre-se de alterar o <span class="hljs-string">"NAME-DB"</span> pelo nome <span class="hljs-keyword">do</span> seu banco de dados criado na etapa anterior
E o <span class="hljs-string">"NAME-TABLE"</span> pelo nome da tabela que voce deseja.
</code></pre>
<h2 class="code-line" data-line-start=35 data-line-end=36 ><a id="Exemplos_35"></a>Exemplos</h2>
<p class="has-line-data" data-line-start="37" data-line-end="38">Apartir dai o trabalho vai ser seu, vou disponibilicar abaixo uma lista de exemplos que voce pode utilizar</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th>Nome</th>
<th>Exemplo</th>
</tr>
</thead>
<tbody>
<tr>
<td>Create-DB</td>
<td>/database/create/name-db</td>
</tr>
<tr>
<td>Create-Table</td>
<td>/database/create/table/name-db/name-table/key</td>
</tr>
<tr>
<td>Inserir-DB</td>
<td>/database/name-db/table/name-table/name-coluna/valor/insert/key</td>
</tr>
<tr>
<td>Remove-Table</td>
<td>/database/name-db/name-table/delete/key</td>
</tr>
<tr>
<td>Select-DB</td>
<td>/database/name-db/table/name-table/select/key</td>
</tr>
<tr>
<td>Google Analytics</td>
<td><a href="https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md">plugins/googleanalytics/README.md</a></td>
</tr>
</tbody>
</table>
<p class="has-line-data" data-line-start="48" data-line-end="49">Mais Informações em breve</p>
