<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="PlaceDB_0"></a>PlaceDB</h1>
<p class="has-line-data" data-line-start="3" data-line-end="4"><a href="https://travis-ci.org/joemccann/dillinger"><img src="https://travis-ci.org/joemccann/dillinger.svg?branch=master" alt="Build Status"></a></p>
<p class="has-line-data" data-line-start="5" data-line-end="6">Esta afim de uma database sem limitação? Voce achou a database perfeita para o seu uso, nossa database foi feita do zero e estamos sempre melhorando.</p>
<h2 class="code-line" data-line-start=7 data-line-end=8 ><a id="Tecnologias_utilizadas_7"></a>Tecnologias utilizadas</h2>
<p class="has-line-data" data-line-start="9" data-line-end="10">PlaceDB usa algumas linguaguens open-source:</p>
<ul>
<li class="has-line-data" data-line-start="11" data-line-end="12"><a href="http://nodejs.org">node.js</a> - E/S de eventos para o back-end</li>
<li class="has-line-data" data-line-start="12" data-line-end="13"><a href="http://expressjs.com">Express</a> - Estrutura de aplicativo de rede rápida node.js <a href="http://twitter.com/tjholowaychuk">@tjholowaychuk</a></li>
</ul>
<h2 class="code-line" data-line-start=15 data-line-end=16 ><a id="Exemplos_de_uso_15"></a>Exemplos de uso</h2>
<p class="has-line-data" data-line-start="17" data-line-end="18">Sera necessario utilizar uma key gerada automaticamente quando cria uma database para utilizar nosso sistema .</p>
<p class="has-line-data" data-line-start="19" data-line-end="20">Primeiro crie seu banco de dados.</p>
<pre><code class="has-line-data" data-line-start="22" data-line-end="25" class="language-sh">https://banco-de-dados.rsr4dmnynb.repl.co/database/create/NAME-DB 
Troque o <span class="hljs-string">'NAME-DB'</span> pelo nome <span class="hljs-keyword">do</span> seu Banco de Dados.
</code></pre>
<p class="has-line-data" data-line-start="25" data-line-end="26">Lembre-se, salve a sua Chave de acesso!</p>
<p class="has-line-data" data-line-start="27" data-line-end="28">Crie uma tabela.</p>
<pre><code class="has-line-data" data-line-start="30" data-line-end="33" class="language-sh">https://banco-de-dados.rsr4dmnynb.repl.co/database/create/table/NAME-DB/NAME-TABLE
Lembre-se de alterar o <span class="hljs-string">"NAME-DB"</span> pelo nome <span class="hljs-keyword">do</span> seu banco de dados criado na etapa anterior e o <span class="hljs-string">"NAME-TABLE"</span> pelo nome da tabela que voce deseja.
</code></pre>
<h2 class="code-line" data-line-start=34 data-line-end=35 ><a id="Exemplos_34"></a>Exemplos</h2>
<p class="has-line-data" data-line-start="36" data-line-end="37">Apartir dai o trabalho vai ser seu, vou disponibilicar abaixo uma lista de exemplos que voce pode utilizar</p>
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
<td>/database/create/NAME-DB</td>
</tr>
<tr>
<td>Inserir-DB</td>
<td>/database/NAME-DB/table/NAME-TABLE/NAME-COLUNA/VALOR/insert/KEY</td>
</tr>
<tr>
<td>Google Drive</td>
<td><a href="https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md">plugins/googledrive/README.md</a></td>
</tr>
<tr>
<td>OneDrive</td>
<td><a href="https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md">plugins/onedrive/README.md</a></td>
</tr>
<tr>
<td>Medium</td>
<td><a href="https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md">plugins/medium/README.md</a></td>
</tr>
<tr>
<td>Google Analytics</td>
<td><a href="https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md">plugins/googleanalytics/README.md</a></td>
</tr>
</tbody>
</table>
<h2 class="code-line" data-line-start=47 data-line-end=48 ><a id="Development_47"></a>Development</h2>
<p class="has-line-data" data-line-start="49" data-line-end="50">Want to contribute? Great!</p>
<p class="has-line-data" data-line-start="51" data-line-end="53">Dillinger uses Gulp + Webpack for fast developing.<br>
Make a change in your file and instantaneously see your updates!</p>
<p class="has-line-data" data-line-start="54" data-line-end="55">Open your favorite Terminal and run these commands.</p>
<p class="has-line-data" data-line-start="56" data-line-end="57">First Tab:</p>
<pre><code class="has-line-data" data-line-start="59" data-line-end="61" class="language-sh">node app
</code></pre>
<p class="has-line-data" data-line-start="62" data-line-end="63">Second Tab:</p>
<pre><code class="has-line-data" data-line-start="65" data-line-end="67" class="language-sh">gulp watch
</code></pre>
<p class="has-line-data" data-line-start="68" data-line-end="69">(optional) Third:</p>
<pre><code class="has-line-data" data-line-start="71" data-line-end="73" class="language-sh">karma <span class="hljs-built_in">test</span>
</code></pre>
<h4 class="code-line" data-line-start=74 data-line-end=75 ><a id="Building_for_source_74"></a>Building for source</h4>
<p class="has-line-data" data-line-start="76" data-line-end="77">For production release:</p>
<pre><code class="has-line-data" data-line-start="79" data-line-end="81" class="language-sh">gulp build --prod
</code></pre>
<p class="has-line-data" data-line-start="82" data-line-end="83">Generating pre-built zip archives for distribution:</p>
<pre><code class="has-line-data" data-line-start="85" data-line-end="87" class="language-sh">gulp build dist --prod
</code></pre>
<h2 class="code-line" data-line-start=88 data-line-end=89 ><a id="Docker_88"></a>Docker</h2>
<p class="has-line-data" data-line-start="90" data-line-end="91">Dillinger is very easy to install and deploy in a Docker container.</p>
<p class="has-line-data" data-line-start="92" data-line-end="95">By default, the Docker will expose port 8080, so change this within the<br>
Dockerfile if necessary. When ready, simply use the Dockerfile to<br>
build the image.</p>
<pre><code class="has-line-data" data-line-start="97" data-line-end="100" class="language-sh"><span class="hljs-built_in">cd</span> dillinger
docker build -t &lt;youruser&gt;/dillinger:<span class="hljs-variable">${package.json.version}</span> .
</code></pre>
<p class="has-line-data" data-line-start="101" data-line-end="104">This will create the dillinger image and pull in the necessary dependencies.<br>
Be sure to swap out <code>${package.json.version}</code> with the actual<br>
version of Dillinger.</p>
<p class="has-line-data" data-line-start="105" data-line-end="108">Once done, run the Docker image and map the port to whatever you wish on<br>
your host. In this example, we simply map port 8000 of the host to<br>
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):</p>
<pre><code class="has-line-data" data-line-start="110" data-line-end="112" class="language-sh">docker run <span class="hljs-operator">-d</span> -p <span class="hljs-number">8000</span>:<span class="hljs-number">8080</span> --restart=always --cap-add=SYS_ADMIN --name=dillinger &lt;youruser&gt;/dillinger:<span class="hljs-variable">${package.json.version}</span>
</code></pre>
<blockquote>
<p class="has-line-data" data-line-start="113" data-line-end="114">Note: <code>--capt-add=SYS-ADMIN</code> is required for PDF rendering.</p>
</blockquote>
<p class="has-line-data" data-line-start="115" data-line-end="117">Verify the deployment by navigating to your server address in<br>
your preferred browser.</p>
<pre><code class="has-line-data" data-line-start="119" data-line-end="121" class="language-sh"><span class="hljs-number">127.0</span>.<span class="hljs-number">0.1</span>:<span class="hljs-number">8000</span>
</code></pre>
<h2 class="code-line" data-line-start=122 data-line-end=123 ><a id="License_122"></a>License</h2>
<p class="has-line-data" data-line-start="124" data-line-end="125">MIT</p>
<p class="has-line-data" data-line-start="126" data-line-end="127"><strong>Free Software, Hell Yeah!</strong></p>
