# Chatbot 

## Pre-reqs

Sign up for Open AI and take note of the API key.

Create an assistant in the Open AI Playground and take note of the assistant ID.

## Setup

You need [Node.js](https://nodejs.org/en/) installed to use this code.

First install pnpm:

```bash
npm install -g pnpm
```

Unzip the chatbot folder then follow the steps below: 

## Run the backend

Open a terminal and change into the backend subdirectory:

```bash
cd chatbot/backend
```

Now set required environment variables.

On MacOS and Linux

```bash
export OPENAI_API_KEY=<your api key>
export ASSISTANT_ID=<your assistant id>
```

Or on Windows:

```bash
set OPENAI_API_KEY=<your api key>
set ASSISTANT_ID=<your assistant id>
```

Run the backend in dev mode:

```bash
pnpm run dev
```

## Run the frontend

Open a terminal and change to the frontend subdirectory:

```bash
cd chatbot/frontend
```

Run the frontend in dev mode:

```bash
pnpm run dev
```

## Build the static web page

```bash
cd chatbot/frontend
pnpm run build
```

## Build the TypeScript code

Do this if you want to check for compile errors.

```bash
cd chatbot/frontend
pnpm run compile
```
