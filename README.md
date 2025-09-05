
# Brano AI Music Generation

Welcome to Brano AI Music Generation! This project lets you generate original music using AI, with a modern SaaS platform built using Next.js, React, Python, FastAPI, and more. All code and setup are tailored for easy deployment and customization.

## Features

- AI-powered music generation
- Custom lyric and prompt support
- Instrumental and vocal track options
- Serverless GPU processing
- Background queue system
- Credit-based user system
- User authentication
- Community music feed
- Personal track dashboard

## Setup

Clone this repository:

```bash
git clone https://github.com/ukmarodia/Brano-AI-Music-Generation.git
```

### Backend

Navigate to the backend folder and install dependencies:

```bash
cd backend
pip install -r requirements.txt
```

### Frontend

Navigate to the frontend folder and install dependencies:

```bash
cd frontend
npm install
```

Run the frontend:

```bash
npm run dev
```

### Queue

Run the local queue development server:

```bash
npx inngest-cli@latest dev
```

## Google Cloud Setup

Create a Google Cloud Storage bucket and configure IAM roles to allow your application to upload, retrieve, and manage music assets securely.

---

This project is maintained by ukmarodia. For questions or collaboration, please open an issue on GitHub.
