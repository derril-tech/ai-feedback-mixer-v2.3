# 🎛️ FeedbackMixer
**with OpenAI SDK**


🌐 **See the Live Application**: [https://ai-feedback-mixer.vercel.app/](https://ai-feedback-mixer.vercel.app/)

> **Transform messy Typeform feedback into clear, actionable product insights with AI. Get themed clusters, sentiment analysis, and executive reports—instantly.** ⚡

---

## ✨ Features

### 🎯 **Core Functionality**
- 📊 **Typeform Integration** - Connect directly to your Typeform surveys
- 🧠 **AI-Powered Theme Clustering** - Group responses using OpenAI embeddings + K-means
- 💭 **Sentiment Analysis** - Understand positive, neutral, and negative feedback
- 📝 **Executive Reports** - Professional reports with action items and quotes
- 💬 **"Talk to Your Feedback"** - Ask follow-up questions about your data
- 🌌 **Visual Theme Galaxy** - Interactive 2D scatter plot of feedback clusters

### 🎨 **Beautiful UI/UX**
- ✨ **Modern 2025 Design** - Glassmorphism, gradients, micro-animations
- 🌙 **Dark Mode Default** - Smooth theme transitions with animated toggle
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile
- ♿ **Accessible** - Focus states, reduced motion support, screen reader friendly
- 🎉 **Delightful Details** - Confetti celebration on analysis complete

### 📊 **Dashboard Features**
- 📈 **Usage Statistics** - Total analyses, themes identified, responses processed
- 📝 **Recent Runs** - Quick access to previous Typeform analyses
- 🔍 **Persistent History** - Results saved to Supabase (when configured)

### 🚀 **Advanced Features**
- 🎤 **Voice Input** - Ask questions hands-free with Web Speech API
- 📡 **Streaming Responses** - See AI answers appear token-by-token
- ⌨️ **Keyboard Shortcuts** - `Cmd/Ctrl + Enter` to run analysis
- 📤 **Export Reports** - Download as Markdown or JSON, copy to clipboard
- 🔗 **Share Links** - Generate public URLs for stakeholder sharing
- 🧠 **Real-time Thinking UI** - Animated progress steps during analysis

---

## 🏗️ Tech Stack

### **Backend** 🐍
- **FastAPI** - Modern Python web framework
- **OpenAI API** - GPT-4.1-mini for analysis, text-embedding-3-small for clustering
- **scikit-learn** - K-means clustering and PCA visualization
- **Python 3.11+** - Async/await for performance

### **Frontend** ⚛️
- **Next.js 15.5** - React 19 with App Router
- **Tailwind CSS** - Utility-first styling with custom design system
- **shadcn/ui** - Beautiful, accessible component library
- **Recharts** - Interactive data visualization
- **Lucide Icons** - Modern icon set

### **Database & Cache** 💾
- **Supabase** - PostgreSQL for persistent storage
- **Upstash Redis** - Rate limiting and caching (optional)
- **In-Memory Fallback** - Works without database for local dev

### **External APIs** 🔌
- **Typeform API** - Fetch survey responses
- **OpenAI API** - Embeddings, chat completions, structured outputs

### **Deployment** 🚀
- **Railway** - FastAPI backend deployment
- **Vercel** - Next.js frontend deployment

---


### 🏠 Homepage
![Homepage]
*Landing page with video background and clear value proposition*

### 🎮 Playground
![Playground]
*Interactive analysis interface with Typeform integration*

### 🌌 Theme Ga
*Visual 2D scatter plot showing feedback clusters*

### 💬 AI Chat
![AI Chat](public/demo/chat.png)
*Ask follow-up questions about your analyzed feedback*

---

## 📖 User Guide

### 🎮 Using the Playground

1. **Enter Typeform ID**
   - Find your form ID in the Typeform URL: `typeform.com/to/YOUR_ID`
   - Paste it into the Form ID field

2. **Add Instructions (Optional)**
   - Guide the AI: *"Focus on pricing feedback"*
   - Or: *"Analyze responses from enterprise users"*

3. **Run Analysis**
   - Click **"Run FeedbackMixer"** or press `Cmd/Ctrl + Enter`
   - Watch the thinking steps animate

4. **Explore Results**
   - 📊 **Sentiment Overview** - Positive/Neutral/Negative breakdown
   - 🌌 **Theme Galaxy** - Visual cluster map (hover for quotes)
   - 🏷️ **Theme Cards** - Detailed summaries with tags and quotes
   - 📄 **Full Report** - Expandable executive summary

5. **Ask Questions**
   - Use the chat to dive deeper: *"What are the main pain points?"*
   - Click the 🎤 mic for voice input

6. **Export & Share**
   - 📤 **Export** - Download as Markdown/JSON
   - 🔗 **Share** - Copy public link for stakeholders

### 📊 Using the Dashboard

1. **View Stats**
   - Total analyses run
   - Themes identified
   - Responses processed

2. **Recent Runs**
   - Click any previous run to reload the Form ID
   - Quick access to re-run analyses

---

## 🎨 Customization

### Theme Options
- 🌙 **Dark Mode** (default) - Easy on the eyes
- ☀️ **Light Mode** - Clean, bright interface
- 🔄 **Animated Toggle** - Smooth transitions with icon rotation

### Analysis Options
- **Extra Instructions** - Custom prompts to focus the AI
- **Urgency Ratings** - Themes are rated high/medium/low
- **Tag Extraction** - 3-5 keywords per theme

---


## 👨‍💻 Creator

**Created by Derril Filemon**

---

## 🙏 Acknowledgments

- **OpenAI** - For GPT-4.1-mini and embeddings API
- **Typeform** - For the survey platform and API
- **Supabase** - For PostgreSQL database
- **Upstash** - For Redis caching
- **Railway** - For backend deployment
- **Vercel** - For frontend deployment
- **shadcn/ui** - For beautiful components
- **Recharts** - For data visualization

---


<div align="center">


Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
