<h1 align="center">📘 Text Summarization with BART</h1>

<p align="center">
  A project demonstrating <b>abstractive text summarization</b> using Facebook's 
  <code>BART-large-CNN</code> transformer model. It processes long input text, generates
  concise summaries, and evaluates performance using <b>ROUGE metrics</b>.
</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>Abstractive summarization with <b>Hugging Face Transformers</b></li>
  <li>Customizable parameters like <code>max_length</code>, <code>min_length</code>, 
      and <code>num_beams</code></li>
  <li>Evaluation with <b>ROUGE</b> metrics</li>
  <li>Pretty formatted output using Python’s <code>textwrap</code></li>
</ul>

<h2>📂 Project Structure</h2>
<pre>
├── summarizer.py      # Main script
├── requirements.txt   # Dependencies
└── README.html        # Project documentation
</pre>

<h2>⚙️ Installation</h2>
<pre>
# Step 1: Clone repo
git clone https://github.com/your-username/text-summarization-bart.git
cd text-summarization-bart

# Step 2: Install dependencies
pip install -r requirements.txt
</pre>

<h2>▶️ Usage</h2>
<pre>
python summarizer.py
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
<p>The project uses <b>ROUGE</b> metrics to evaluate summary quality:</p>
<pre>
ROUGE-1: 0.45
ROUGE-2: 0.29
ROUGE-L: 0.41
</pre>

<h2>📦 Dependencies</h2>
<ul>
  <li>transformers</li>
  <li>sentencepiece</li>
  <li>evaluate</li>
</ul>

<h2>🤝 Contributing</h2>
<p>
Pull requests and contributions are welcome! If you'd like to improve the model, 
add new datasets, or enhance evaluation methods, feel free to fork and submit a PR.
</p>

<h2>📜 License</h2>
<p>
This project is licensed under the <b>MIT License</b>. 
</p>
