<h1>Text Summarization with BART: Abstractive NLP Pipeline</h1>

<p>
  Abstractive text summarization using Facebook's <code>BART-large-CNN</code> model, 
  implemented in a Google Colab Notebook. Generate concise summaries from long texts 
  and evaluate them with <b>ROUGE metrics</b>.
</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>Runs entirely in <b>Google Colab</b> (no local setup)</li>
  <li>Uses Hugging Face’s <code>transformers</code> for summarization</li>
  <li>Evaluation with <b>ROUGE</b> metrics</li>
  <li>Clean output formatting using Python’s <code>textwrap</code></li>
</ul>

<h2>📂 Project Structure</h2>
<pre>
├── Text_Summarization_BART.ipynb   # Main Google Colab Notebook
└── README.html                     # Documentation
</pre>

<h2>📝 Example</h2>
<p><b>Input:</b></p>
<pre>
Artificial Intelligence (AI) is rapidly transforming various industries...
</pre>

<p><b>Generated Summary:</b></p>
<pre>
AI is revolutionizing industries such as healthcare, finance, and education. 
It enhances diagnostics, detects fraud, and personalizes learning, while raising 
ethical concerns around privacy, bias, and job displacement.
</pre>



<h2>📦 Dependencies</h2>
<p>Dependencies are installed automatically in the notebook:</p>
<ul>
  <li>transformers</li>
  <li>sentencepiece</li>
  <li>evaluate</li>
</ul>
