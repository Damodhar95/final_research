# 🔬 PRISM - AI Research Assistant

<div align="center">

![PRISM Logo](public/icon.svg)

### Transform complex research papers into crystal-clear insights

An AI-powered research assistant designed to help users understand, analyze, and explore academic research papers.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://finalresearch-vert.vercel.app/)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/Damodhar95/final_research)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Damodhar95/final_research)

</div>

---

## 📌 About the Project

PRISM is an AI-powered research assistant that simplifies the process of understanding complex academic papers.

It uses Google's Gemini AI to help users analyze research documents, extract meaningful insights, ask questions, explore research ideas, and organize technical knowledge.

The goal is to make academic research more accessible, understandable, and productive.

## ✨ Features

### 🧠 Deep Research Analysis
- Analyze research papers and extract important information.
- Understand research methodology and key findings.
- Identify supporting evidence and important insights.

### 💬 AI-Powered Chat
- Ask questions about uploaded research papers.
- Get AI-generated answers based on research content.
- Explore complex topics through interactive conversations.

### 📊 Smart Export
- Export research insights into different formats.
- Supported formats include PDF, Markdown, and PowerPoint.
- Organize and share research findings.

### 💡 Hypothesis Lab
- Generate new research ideas.
- Explore potential research directions.
- Support brainstorming for future studies.

### 📖 Smart Glossary
- Extract technical terms from research papers.
- Understand important terminology.
- Make complex academic content easier to follow.

### 🔒 Privacy-Focused Experience
- Research data is designed to remain local to the browser.
- Users can configure their Gemini API key through application settings.
- API key storage is handled locally by the application.

---

## 🌐 Live Demo

Experience PRISM AI Research Assistant:

**https://finalresearch-vert.vercel.app/**

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React 18 |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| Programming Language | JavaScript |
| AI Integration | Google Gemini API |
| AI Model | gemini-3-flash-preview |
| State Management | Zustand |
| PDF Processing | react-pdf, pdfjs-dist |
| Deployment | Vercel |
| Version Control | Git and GitHub |

---

## 🚀 Getting Started

Follow these instructions to run PRISM on your local computer.

### Prerequisites

Make sure you have installed:

- Node.js 18 or later
- npm
- Git
- Google Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey)

### 1. Clone the Repository

```bash
git clone https://github.com/Damodhar95/final_research.git
```

### 2. Navigate to the Project Folder

```bash
cd final_research
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Your Gemini API Key

1. Open the PRISM application.
2. Navigate to Settings.
3. Enter your Gemini API key.
4. Click Save Key.

Get your API key from:

https://aistudio.google.com/apikey

**Important:** Never upload your personal API key to GitHub. Vite environment variables prefixed with `VITE_` are exposed in the browser bundle and should not be treated as private secrets.

### 5. Start the Development Server

```bash
npm run dev
```

### 6. Open the Application

Open the local URL displayed in your terminal.

The development server in the current project has been tested at:

http://localhost:3000/

---

## ☁️ Deployment with Vercel

PRISM is deployed using Vercel.

### Deploy Your Own Version

1. Open [Vercel](https://vercel.com/).
2. Sign in using your GitHub account.
3. Select **Add New Project**.
4. Import the `Damodhar95/final_research` repository.
5. Configure the project:

| Setting | Value |
|---|---|
| Framework Preset | Vite |
| Root Directory | `./` |
| Build Command | `npm run build` |
| Output Directory | `dist` |
| Install Command | `npm install` |

6. Check the project's API key configuration before deployment.
7. Click **Deploy**.

After successful deployment, Vercel will provide a live website URL.

### Automatic Deployment

When changes are pushed to the connected GitHub `main` branch, Vercel can automatically build and deploy the latest version.

---

## 🔑 In-App API Key Setup

Users can configure their Gemini API key directly inside PRISM.

1. Open the application.
2. Click **Settings** in the header.
3. Enter your Gemini API key.
4. Click **Save Key**.

The application stores the key locally in the browser.

For security, use your own API key and avoid sharing it publicly.

---

## 👥 Project Team

**Built with 💜 by our team**

| Team Member | Role |
|---|---|
| **Mithun** | Team Lead & Full Stack Developer |
| **Damodar** | Backend Developer |
| **Kaifulla** | AI/ML Engineer |
| **Ranjith** | UI/UX Designer |

Each team member contributed to different aspects of the project, including development, AI integration, and user experience.

---

## 🎯 Project Objective

The main objective of PRISM is to simplify academic research by combining artificial intelligence with document analysis.

The project aims to:

- Reduce the time required to understand research papers.
- Make complex academic information easier to understand.
- Help users discover meaningful insights.
- Support research exploration and idea generation.
- Improve the overall research experience.

---

## 🔮 Future Improvements

Potential areas for future development include:

- Support for additional AI models.
- Advanced research paper comparison.
- Improved citation and reference extraction.
- Research library and document management.
- Enhanced analysis and visualization tools.

---

## 📄 License

This project is described as being available under the MIT License.

---

## 🙏 Acknowledgements

- [Google Gemini](https://ai.google.dev/) for AI capabilities.
- [React](https://react.dev/) for the frontend library.
- [Vite](https://vite.dev/) for the development and build tooling.
- [Vercel](https://vercel.com/) for deployment.
- Our project team for their contributions and collaboration.

---

<div align="center">

### ⭐ If you find PRISM useful, consider starring the repository!

**PRISM - Making Research Simpler with AI 💜**

[Live Demo](https://finalresearch-vert.vercel.app/) · [GitHub Repository](https://github.com/Damodhar95/final_research)

</div>