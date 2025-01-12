**Expert Knowledge Worker**

A Question-Answering Agent for Insurellm Employees

🔍 Project Overview
A high-accuracy question-answering assistant built for Insurellm, an Insurance Tech company.
Leverages RAG (Retrieval Augmented Generation) for reliable answers.
Prioritizes low cost using the gpt-4o-mini model and open-source tools.

⚙️ Key Features
RAG Workflow: Combines document retrieval with GPT-based generation.
Vector Store: Efficient Chroma database for embedding storage.
Embeddings: Uses OpenAI embeddings for semantic text search.
Visualization: 2D/3D visual exploration of embeddings.
Chat Interface: Gradio provides a simple user-friendly chat system.

🛠️ Tech Stack
Programming: Python
LLM Model:	GPT-4o-mini
Vector Database:	Chroma
Embeddings:	OpenAI, HuggingFace
Visualization:	Plotly, t-SNE (scikit-learn)
Frontend:	Gradio

📂 Workflow
Knowledge Base:
Organize content into subfolders (e.g., knowledge-base/products/).
Chunking & Embedding:
Split content into smaller chunks (1000 chars, 200 overlap).
Embed chunks into vectors.
Vector Search:
Retrieve relevant content using Chroma.
LLM Response:
GPT generates answers based on retrieved data.
Chat Interface:
Gradio provides real-time interaction.

🚀 How to Run
Set Up Environment:
bash
Copy code
pip install langchain chromadb openai gradio matplotlib plotly sklearn
Prepare Knowledge Base:
Add .md files under knowledge-base/ (organized by category).
Add API Key:
Create a .env file:
makefile
Copy code
OPENAI_API_KEY=your_openai_api_key
Run the Project:
bash
Copy code
python main.py

🖼️ Visualizations
2D/3D Plots of Embedding Vectors using t-SNE:
Understand document distribution in vector space.
Explore document types interactively.

🧩 Features in Action
Query Example:
"Who received the IIOTY award in 2023?"
Assistant retrieves relevant chunks → Generates an accurate answer.
Real-Time Interaction:
Launch a browser-based chat using Gradio.

### Chat Interface
![Chat Interface]("https://github.com/thulasiramd2000/Insurance-AI-Knowledge-Assistant/blob/main/Gradio%20Screenshot.png?raw=true")
![Chat Interface2]("https://github.com/thulasiramd2000/Insurance-AI-Knowledge-Assistant/blob/main/Gradio%20Screenshot-2.png?raw=true")

🔮 Future Enhancements
Use open-source embedding models for data privacy.
Add support for PDFs, DOCX, and more file formats.
Implement advanced chunk ranking and filtering.
Expand to multi-turn conversations.

💡 Why RAG for Insurellm?
High Accuracy: Combines retrieval + generation.
Cost-Effective: Lightweight models reduce costs.
Scalable: Modular design supports future growth.
Secure: Future-proofed for on-premise deployments.

🎯 Goals
Build a reliable and cost-effective knowledge worker for Insurellm.
Ensure scalable and secure solutions for enterprise environments.
