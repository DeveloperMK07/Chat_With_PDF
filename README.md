<h1>📄🤖 Chat with Multiple PDFs using LLaMA, Streamlit, Hugging Face & FAISS</h1>
    
<h2>📝 Overview</h2>
<p>
    <b>Chat with Multiple PDFs</b> is an AI-powered chatbot that enables users to interact with multiple PDF documents 
    simultaneously. Using advanced <b>Natural Language Processing (NLP)</b> and <b>machine learning</b>, the system 
    allows users to ask questions and retrieve relevant answers directly from the content of uploaded PDFs.
</p>
<p>
    This application leverages the <b>LLaMA language model</b> for understanding and processing queries, 
    <b>FAISS (Facebook AI Similarity Search)</b> for efficient document indexing and retrieval, and 
    <b>Hugging Face transformers</b> for deep learning capabilities. The user interface is built with 
    <b>Streamlit</b>, ensuring a smooth and interactive experience.
</p>
<p>
    Whether you're analyzing research papers, legal documents, technical manuals, or any other text-heavy PDFs, 
    this project provides a streamlined way to extract key insights without manually searching through documents. 
    It is particularly useful for <b>students, researchers, data analysts, and professionals</b> who frequently work 
    with large sets of documents.
</p>


<h2>🚀 Features</h2>
    <ul>
        <li>✅ Upload Multiple PDFs – Supports multi-document interaction.</li>
        <li>✅ Conversational AI – Ask questions and get answers from PDFs.</li>
        <li>✅ Fast & Accurate – Uses FAISS for efficient vector search.</li>
        <li>✅ LLaMA-powered Chatbot – Advanced NLP capabilities.</li>
        <li>✅ Easy-to-Use UI – Built with Streamlit for seamless experience.</li>
    </ul>

<h2>🛠️ Tech Stack</h2>
    <ul>
        <li>📌 Frontend: Streamlit</li>
        <li>📌 Backend: Python</li>
        <li>📌 Model: LLaMA (via Hugging Face)</li>
        <li>📌 Vector Search: FAISS</li>
        <li>📌 Libraries: LangChain, PyMuPDF, OpenAI API (optional)</li>
    </ul>
<h2>🖥️ Installation & Setup</h2>

  <h3>1️⃣ Clone the Repository</h3>
    <pre><code>git clone https://github.com/DeveloperMK07/Chat_With_PDF.git 
    cd Chat_With_PDF</code></pre>

<h3>2️⃣ Create a Virtual Environment (Optional but Recommended)</h3>
    <pre><code>python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate  # On Windows</code></pre>

  <h3>3️⃣ Install Dependencies</h3>
    <pre><code>pip install -r requirements.txt</code></pre>

  <h3>4️⃣ Run the Application</h3>
    <pre><code>streamlit run app.py</code></pre>
    <p>Now, open <b>http://localhost:8501</b> in your browser to start chatting with your PDFs! 🎉</p>

  <h2>🌟 Future Enhancements</h2>
    <ul>
        <li> Add support for image-based PDFs (OCR)</li>
        <li> Improve response accuracy with RAG-based models</li>
        <li> Deploy on AWS, Hugging Face Spaces, or Render</li>
    </ul>

  <h2>📬 Contact & Support</h2>
    <p>💡 Created by <a href="https://github.com/DeveloperMK07">DeveloperMK07</a></p>
