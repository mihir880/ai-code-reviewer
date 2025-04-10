# Ollama AI Code Reviewer

Discover a streamlined AI-powered code review tool built in TypeScript. This frontend application accepts source code as input and leverages the power of Meta's Codellama—running on the Ollama7B model—to generate insightful, automated code comments.This project shows you how to rapidly integrate ready-to-use AI tools into your development workflow.

## Overview

This is  TypeScript-based frontend application and a simple backend server that work together to provide automated code reviews. The process is straightforward: a developer enters their code into the app, and the backend communicates with the Codelllama model running via Ollama, which then returns helpful commentary and suggestions for improvement.

## Features

- **Effortless Setup:** Launch the project quickly with minimal configuration.
- **Smart Code Feedback:** Utilize Meta's Codellama powered by Ollama7B to automatically comment on your code.
- **Modern Frontend:** Written in TypeScript for a robust and scalable user experience.
- **Seamless Integration:** Demonstrates how off-the-shelf AI tools can be combined with existing tech stacks.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/ollama-code-reviewer.git
   cd ollama-code-reviewer
    install Dependencies:

  For the root application:
  
   ```bash
  Copy
  npm install
  ```

2. Running the AI Model
Start the Codellama model using Ollama with the following command:

 ```bash
ollama run codellama:7b
```
3. Client Application
```bash
npm run dev
```
Navigate to the server directory:
```bash
cd server
node index.js
```
Contributing
Contributions are welcome! If you find any issues or have suggestions for new features, please open an issue or submit a pull request.
