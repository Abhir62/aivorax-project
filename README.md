# 🤖 AivoraX AI: Your Intelligent Assistant

A powerful and feature-rich conversational AI assistant interface built with pure HTML, CSS, and JavaScript. This project provides a clean, responsive UI for interacting with large language models through the OpenRouter API, complete with features like chat history, file analysis, custom instructions, and more.

**[✨ Live Demo](https://your-site-name.netlify.app/)** 👈 *(Netlify पर होस्ट करने के बाद यहाँ अपनी लाइव वेबसाइट का लिंक डालें)*

---

### 🚀 Key Features (मुख्य विशेषताएँ)

-   **Clean & Responsive UI:** Modern, chatbot-style interface that works on both desktop and mobile.
-   **Dark & Light Mode:** Automatic theme detection with a manual toggle for user preference.
-   **Chat History:** All conversations are saved in the browser's local storage.
-   **Folders & Pinning:** Organize your chats into folders and pin important conversations.
-   **Custom Instructions:** Tailor the AI's personality and responses to your needs.
-   **File & Image Uploads:** Analyze images and documents (.pdf, .txt, .docx).
-   **Voice Input:** Use your voice to talk to the AI (Speech-to-Text).
-   **Read Aloud:** Listen to the AI's responses (Text-to-Speech).
-   **Code Syntax Highlighting:** Beautifully formatted code blocks with a copy button.
-   **Export Chat:** Download your conversations as Markdown, HTML, or PDF files.
-   **Secure API Calls:** Uses Netlify Functions to keep the API key safe on the server-side.

---

### 🛠️ Tech Stack (तकनीकी स्टैक)

-   **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
-   **Backend:** Netlify Functions (Serverless)
-   **AI Integration:** [OpenRouter.ai](https://openrouter.ai/) API
-   **Libraries:** Marked.js (for Markdown), highlight.js (for syntax highlighting), jspdf & html2canvas (for PDF export).

---

### 🔧 Setup & Deployment

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/aivorax-ai-chatbot.git
    ```
2.  **Deploy on Netlify:**
    -   Connect your GitHub repository to Netlify.
    -   Create an environment variable named "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"; and add your API key.
    -   Deploy the site. Netlify will automatically use the `netlify.toml` file for configuration.
