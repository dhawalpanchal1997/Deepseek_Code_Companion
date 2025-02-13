# 🧠 DeepSeek Code Companion  
🚀 **Your AI Pair Programmer with Debugging Superpowers**

## 📌 Project Overview  
DeepSeek Code Companion is an interactive AI-powered coding assistant built using **Streamlit**, **LangChain**, and **Ollama**. It offers a seamless debugging and coding experience for developers by providing instant suggestions, explanations, and solutions to coding problems. With an intuitive user interface and advanced AI capabilities, DeepSeek transforms the way developers write and debug code.

## ✨ Features  
- **🐍 Python Expert:** Get precise Python code suggestions and solutions.  
- **🐞 Debugging Assistant:** Diagnose issues in your code with strategic print statements for debugging.  
- **📝 Code Documentation:** Automatically generate high-quality documentation for your Python code.  
- **💡 Solution Design:** Receive recommendations for best practices and optimized solutions.

## 🛠️ Built With  
- **[Streamlit](https://streamlit.io/):** For creating the interactive web-based user interface.  
- **[LangChain](https://python.langchain.com/):** For managing AI-driven conversations and prompt generation.  
- **[Ollama](https://ollama.ai/):** As the underlying AI model for generating intelligent responses.

## 🔧 How It Works  
1. **Model Selection:** Choose between `deepseek-r1:1.5b` and `deepseek-r1:7b` from the sidebar for different levels of response complexity.  
2. **Interactive Chat Interface:** Input your coding question in the chat and get instant responses with explanations.  
3. **Session Persistence:** Chat history is maintained for the session, ensuring context-aware responses.  
4. **Custom Styling:** The UI is enhanced with a dark theme for a modern coding environment feel.  

## 🚀 Getting Started  

### Prerequisites  
- Python 3.9 or higher  
- Streamlit installed (`pip install streamlit`)  
- Ollama running locally (`base_url="http://localhost:11434"`)  
- LangChain modules installed (`pip install langchain-core langchain-ollama`)  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/deepseek-code-companion.git
   cd deepseek-code-companion
2. Install the required packages:
   ```bash
    pip install -r requirements.txt
3. Run the Streamlit app:
   ```bash
   streamlit run app.py

## 🎨 Custom CSS Styling
The project includes custom styling for a sleek and consistent dark theme in both the main interface and sidebar components.

### 🏗️ Project Structure
         deepseek-code-companion/
         │
         ├── app.py                # Main Streamlit application file  
         ├── requirements.txt      # Dependencies  
         └── README.md             # Project documentation  
 
## 🛡️ System Prompt Configuration
The system prompt is designed to ensure responses are always:

- Concise and to the point
- Correct with code solutions
- Helpful for debugging and learning

## 🌟 Acknowledgments
Built with ❤️ using Ollama and LangChain for an innovative coding experience. Special thanks to the open-source community for their contributions.
