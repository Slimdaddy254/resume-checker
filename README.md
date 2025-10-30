# 🧠 AI Resume ATS Checker

An intelligent web app that evaluates resumes for ATS (Applicant Tracking System) compatibility and provides actionable feedback using AI. Built with **PuterJS** for AI analysis and **React Router** for seamless navigation.

## 🚀 Features

- 📄 Upload or paste your resume
- ✅ Get an ATS score (0–100)
- 🧠 AI-powered feedback on formatting, keywords, and structure
- 📊 Visual breakdown of strengths and weaknesses
- 🔁 Real-time suggestions to improve your resume
- 🌐 SPA architecture using React Router

##🧠 How It Works

1. 	User uploads or pastes resume text
2. 	PuterJS processes the input and returns:
• 	ATS score
• 	Keyword match analysis
• 	Formatting issues
• 	Suggestions for improvement
3. 	Results are displayed with visual feedback and improvement tips

## 🛠️ Tech Stack

| Technology     | Purpose                                  |
|----------------|-------------------------------------------|
| React          | Frontend framework                        |
| React Router   | Client-side routing                       |
| PuterJS        | AI resume analysis                        |
| Tailwind CSS   | Styling and layout (optional)             |

## 📦 Installation

```bash
git clone https://github.com/your-username/ats-resume-checker.git
cd ats-resume-checker
npm install
npm start
## Getting Started

### Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

