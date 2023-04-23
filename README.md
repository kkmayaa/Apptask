<h1>Flask MongoDB API</h1>
	<p>This is a Flask application for performing CRUD operations on a MongoDB database.</p>
	<h2>Prerequisites</h2>
<ul>
	<li>Python 3.x</li>
	<li>Flask</li>
	<li>pymongo</li>
	<li>bson</li>
	<li>MongoDB</li>
</ul>

<h2>Installation</h2>
<ol>
	<li>Clone the repository to your local machine.</li>
	<li>Install the prerequisites.</li>
	<li>Start MongoDB.</li>
	<li>Open a command prompt and navigate to the cloned repository.</li>
	<li>Run the following command to start the Flask application:</li>
	<pre><code>python app.py</code></pre>
</ol>

<h2>Usage</h2>
<p>Once the Flask application is running, you can use the following endpoints to perform CRUD operations on the database:</p>

<h3>Create</h3>
<p>Create a new record in the database.</p>
<pre><code>POST /data</code></pre>
<p>Request body:</p>
<pre><code>{
"id": "string",
"field1": "string",
"field2": "string",
...
}</code></pre>
<p>Response body:</p>
<pre><code>{
"id": "string"
}</code></pre>
<h3>Read all</h3>
<p>Get a list of all records in the database.</p>
<pre><code>GET /data</code></pre>
<p>Response body:</p>
<pre><code>[{	"id": "string",	"field1": "string",	"field2": "string",	...},{	"id": "string",	"field1": "string",	"field2": "string",	...},...
]</code></pre>
<h3>Read one</h3>
<p>Get a specific record from the database by its ID.</p>
<pre><code>GET /data/{id}</code></pre>
<p>Response body:</p>
<pre><code>{
"id": "string",
"field1": "string",
"field2": "string",
...
}</code></pre>
<h

