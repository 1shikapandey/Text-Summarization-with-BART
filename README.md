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

<h2>▶️ Getting Started</h2>
<p>
Click below to open the notebook in Google Colab:
</p>

<p align="center">
  <a href="https://colab.research.google.com/github/your-username/your-repo/blob/main/Text_Summarization_BART.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
  </a>
</p>

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

<h2>📊 Evaluation</h2>
<p>Summaries are evaluated using <b>ROUGE</b> metrics:</p>
<pre>
ROUGE-1: 0.45
ROUGE-2: 0.29
ROUGE-L: 0.41
</pre>

<h2>📦 Dependencies</h2>
<p>Dependencies are installed automatically in the notebook:</p>
<ul>
  <li>transformers</li>
  <li>sentencepiece</li>
  <li>evaluate</li>
</ul>

<h2>🤝 Contributing</h2>
<p>
Contributions are welcome! Fork the repo, edit the notebook, and submit a pull request 
to improve summarization methods or add new evaluation metrics.
</p>

<h2>📜 License</h2>
<p>
This project is licensed under the <b>MIT License</b>.
</p>
