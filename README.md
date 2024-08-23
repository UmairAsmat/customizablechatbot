
## AI Mentor ChatBot

Welcome to **AI Mentor ChatBot**! This repository hosts a Streamlit application designed to provide a customizable AI chatbot experience using OpenAI's GPT-3.5 Turbo API. The chatbot serves as an AI technical expert, helping users with their AI-related questions and providing informative guidance on topics like machine learning, deep learning, natural language processing, computer vision, and more.

## 🌟 Features

- **Interactive Chatbot:** Engage in real-time conversations with an AI technical expert trained to assist with various AI topics.
- **Customizable Responses:** Modify the behavior and tone of the chatbot through customizable prompts.
- **Streamlit Interface:** A user-friendly web interface that allows for seamless interactions with the AI.
- **Secure API Integration:** Utilizes OpenAI's GPT-3.5 Turbo API for generating responses, securely accessed via a secret API key.

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Python 3.7 or later
- OpenAI API Key (You can obtain one by signing up at [OpenAI](https://platform.openai.com/signup))

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/ai-mentor-chatbot.git
   cd ai-mentor-chatbot
   ```

2. **Install Required Packages:**
   Install the dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```
   Make sure your `requirements.txt` file includes:
   ```text
   streamlit
   streamlit-chat
   langchain
   openai
   ```

3. **Set Up Environment Variables:**
   Create a `.streamlit/secrets.toml` file to store your OpenAI API key securely:
   ```toml
   [secrets]
   OPENAI_API_KEY = "your-openai-api-key"
   ```

### Running the App

To run the app, execute the following command:
```bash
streamlit run app.py
```

Replace `app.py` with the name of your Python script if it's different. Open your browser and navigate to the URL provided by Streamlit to interact with the chatbot.

## 🛠 How It Works

The chatbot utilizes OpenAI's GPT-3.5 Turbo model to generate responses based on user input. It is initialized with specific system messages to guide the conversation flow and maintain a focus on AI-related topics. User inputs are processed and sent to the OpenAI API, and responses are generated accordingly.

### Key Components

- **Session State Management:** Maintains the state of user inputs and AI responses to create a cohesive chat experience.
- **Custom Prompts:** Modify the chatbot's behavior by editing the system message in the `build_message_list` function.
- **Response Generation:** Leverages OpenAI's GPT-3.5 Turbo to provide accurate and relevant answers to user queries.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions, feedback, or support, please reach out to [your-email@example.com](mailto:your-email@example.com).

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy chatting with your AI Mentor! 🌐🤖
```

### Tips for Your Repository

- **Include a `requirements.txt` file** in your repository to list all necessary dependencies.
- **Add a `.gitignore` file** to avoid committing sensitive information like your `.streamlit/secrets.toml` file.
- **Include Screenshots or Demos**: Visual aids can significantly enhance your README, showing users what they can expect from the app.
- **Provide Usage Examples**: Consider adding a section with common use cases or examples of questions users can ask the chatbot.

By following this structure and content for your `README.md`, you'll provide a comprehensive and user-friendly guide that encourages more people to use and contribute to your project.
