# BreezeFlow

All-in-one productivity management platform that helps you organize your life with intelligent task management, calendar synchronization, bill payments, and more.

## Features

- **Task Management**: Create, organize, and prioritize tasks
- **Calendar Integration**: View and manage your schedule
- **Bill Payment Tracking**: Stay on top of your financial obligations
- **Errand Management**: Keep track of your to-do items
- **ROI Dashboard**: See how much time and money you've saved
- **BreezeMind AI Assistant**: Get help with tasks and schedule optimization

## 100% Free Offline AI with BreezeMind-Lite

BreezeFlow includes BreezeMind-Lite, a completely offline, free AI assistant that helps you manage your productivity without sending data to external APIs.

### How BreezeMind-Lite Works

- **Ollama Integration**: Runs Llama3, a powerful open-source large language model, directly on your system
- **Local Processing**: All AI processing happens on your machine, ensuring privacy
- **Memory-Safe**: Auto-unloads after 10 minutes of inactivity to conserve system resources
- **Schedule Optimization**: Uses a custom algorithm to optimize your daily schedule

### BreezeMind-Lite Features

- **Task Creation**: "Create a task to finish my presentation by Friday"
- **Schedule Optimization**: "Optimize my calendar for today"
- **Natural Language Assistance**: Ask questions about productivity, time management, and more

### Usage Limits

- **Free Plan**: 5 AI requests per hour
- **Paid Plans**: Unlimited AI requests

## Getting Started

1. Clone the repository
2. Install dependencies with `npm install`
3. Run the application with `npm run dev`
4. Access the application at `http://localhost:5000`

### First-time Setup for BreezeMind-Lite

1. Run `bash scripts/setup_ollama.sh` to set up the Llama3 model
2. Wait for the model to download and configure (this may take some time depending on your internet connection)
3. Once complete, BreezeMind will be ready to use

## Technology Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT-based with secure cookie storage
- **AI**: Ollama running Llama3 (offline, no API keys required)

## 🧪 Running Functional Tests

BreezeFlow includes a comprehensive suite of end-to-end tests to verify core functionality:

1. Clone the repository
2. Install dependencies with `npm install`
3. Run the tests with `npm run test:e2e`

The test suite verifies:
- User authentication flows (signup, login, logout)
- Task creation, completion, and management
- ROI calculation for completed tasks
- AI task parsing and schedule optimization

### Test Structure

- `tests/e2e/auth.test.ts` - Authentication flow tests
- `tests/e2e/task.test.ts` - Task management tests
- `tests/e2e/roi.test.ts` - ROI calculation tests
- `tests/e2e/ai.test.ts` - AI feature tests

These tests help ensure quality before each deployment and verify that all critical user flows are working correctly.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.