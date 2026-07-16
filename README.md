# Email-Automation-System-
# 📧 AI Email Automation System

An AI-powered email automation application that analyzes email content, identifies intent and sentiment, generates concise summaries, and creates context-aware draft replies using Large Language Models.

🔗 **Live Demo:** https://emailautomation77.netlify.app/

---

## 🚀 Features

- 📩 Email intent classification
- 😊 Sentiment detection
- 📝 Automatic email summarization
- 🤖 AI-generated draft replies
- 🎭 Multiple reply tone selection
- ⚡ Serverless backend using Netlify Functions
- 🔒 Secure API key management through environment variables
- 📱 Responsive and user-friendly interface

---

# 🛠 Tech Stack

### Frontend
- HTML5
- JavaScript
- Tailwind CSS

### Backend
- Netlify Functions

### AI
- Groq API
- Llama 3.3 70B Versatile

### Deployment
- Netlify

---

# 📂 Project Structure

```
Email-Automation-System
│
├── index.html
├── netlify.toml
├── README.md
│
└── netlify
    └── functions
        └── categorize.js
```

---

# ⚙️ System Workflow

```
User enters email
        │
        ▼
Frontend Interface
        │
        ▼
Netlify Serverless Function
        │
        ▼
Groq LLM
        │
        ├── Intent Classification
        ├── Sentiment Analysis
        ├── Email Summary
        └── Draft Reply Generation
        │
        ▼
Results Displayed to User
```

---

# ✨ Functionalities

### Email Classification

Automatically categorizes emails into:

- Inquiry
- Support
- Complaint
- Feedback
- Sales
- Spam

### Sentiment Detection

Detects whether an email is:

- Positive
- Neutral
- Negative
- Urgent

### AI Response Generation

Generates:

- Concise email summary
- Context-aware draft reply
- Tone-specific responses

Supported tones:

- Professional
- Friendly
- Formal
- Concise

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/Smriti2929/Email-Automation-System.git
```

Move into the project

```bash
cd Email-Automation-System
```

Install Netlify CLI

```bash
npm install -g netlify-cli
```

Create a `.env` file

```env
GROQ_API_KEY=YOUR_GROQ_API_KEY
```

Run locally

```bash
netlify dev
```

---

# 🔑 Environment Variables

```env
GROQ_API_KEY=YOUR_GROQ_API_KEY
```

---

# 📌 API Endpoint

```
POST /.netlify/functions/categorize
```

### Example Request

```json
{
  "subject": "Unable to login",
  "body": "I cannot access my account.",
  "tone": "Professional"
}
```

### Example Response

```json
{
  "category": "Support",
  "sentiment": "Urgent",
  "summary": "The customer cannot access their account.",
  "draftReply": "Hello, thank you for reaching out..."
}
```

---

# 📈 Future Improvements

- Gmail API integration
- One-click email sending
- Email history dashboard
- User authentication
- Batch email processing
- Custom prompt templates
- Multi-language support
- Analytics and reporting
- Conversation history
- Human approval before sending responses

---

# 💼 Use Cases

- Customer Support
- Business Operations
- Sales Teams
- HR Communication
- Helpdesk Automation
- Internal Email Management

---

# 👩‍💻 Author

**Smriti Asthana**

- GitHub: https://github.com/Smriti2929
- LinkedIn: https://www.linkedin.com/in/smriti-asthana-3518bb315/
- Portfolio: https://smriti-ai-portfolio-tsmk.vercel.app/
- Hashnode: https://buildingwithsmriti.hashnode.dev/

---
