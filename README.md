<p align="center">
  <img src="icons/icon128.png" alt="LoopNote logo" width="96" height="96">
</p>

# LoopNote

### A parallel thinking space for ChatGPT.

LoopNote is a lightweight AI notebook that lives directly inside ChatGPT.

If you've ever been deep inside a long ChatGPT conversation and suddenly needed to ask a small side question, look up a definition, save an insight, or jot down a thought, you've probably experienced the same frustration that inspired LoopNote.

You can either:

* Ask the question in the current chat and clutter the conversation.
* Open a new chat and lose the context of what you were reading.
* Scroll away from your current position and later struggle to find your place again.

When this happens repeatedly during study sessions, research, coding, or deep work, it breaks momentum.

LoopNote solves this by providing a dedicated workspace alongside ChatGPT for quick questions, personal notes, and saved insights—without interrupting your primary workflow.

---

## Features

### ⚡ Fast AI Assistant

Powered by Groq's ultra-fast inference for instant clarifications, definitions, summaries, and follow-up questions.

### 📝 Save Insights

Save useful AI responses directly into your notebook with a single click.

### 📒 Personal Notes

Create and manage your own notes without leaving ChatGPT.

### 🕘 Question History

Browse and reopen previous conversations whenever you need them.

### 📥 Markdown Export

Export conversations as Markdown files for Obsidian, Notion, GitHub, or personal archives.

### 🎨 Notebook-Inspired Design

A warm graph-paper aesthetic designed to feel like a digital study notebook.

### 🔒 Privacy First

Runs entirely in your browser with no backend servers and no tracking.

---

## Installation

### Option 1: Download ZIP

1. Download this repository as a ZIP.
2. Extract it to a folder on your computer.

### Option 2: Clone Repository

```bash
git clone https://github.com/yourusername/loopnote.git
```

---

## Load Into Chrome

1. Open Chrome.
2. Navigate to:

```text
chrome://extensions
```

3. Enable **Developer Mode**.
4. Click **Load unpacked**.
5. Select the `loopnote` folder.

The extension will now be installed locally.

---

## Setup

The first time you open LoopNote, you'll be asked for a Groq API key.

### Get a Free Groq API Key

1. Create an account at:

```text
https://console.groq.com
```

2. Generate an API key.
3. Paste it into LoopNote.
4. Click **Save Key**.

Your key is stored locally using Chrome Storage and is never hardcoded into the extension.

---

## How To Use

1. Open ChatGPT.
2. Open the LoopNote sidebar.
3. Ask quick side questions without affecting your main conversation.
4. Save useful responses as insights.
5. Create personal notes.
6. Revisit previous questions from History.
7. Export conversations whenever needed.

Everything happens inside the same ChatGPT page.

---

## Example Workflow

Imagine you're reading a long explanation about neural networks.

Halfway through, you wonder:

> "What exactly is backpropagation?"

Instead of disrupting the main conversation:

1. Open LoopNote.
2. Ask the question.
3. Get a quick answer.
4. Save the explanation.
5. Continue reading exactly where you left off.

No chat switching.

No extra tabs.

No lost scroll position.

---

## Privacy & Security

LoopNote is designed to be simple and transparent.

### What LoopNote Does Not Do

* Access ChatGPT cookies
* Intercept ChatGPT requests
* Read WebSocket traffic
* Modify ChatGPT conversations
* Send your notes to external servers
* Collect analytics or tracking data

### What LoopNote Does Do

* Store notes locally using Chrome Storage
* Send your questions directly to Groq using your own API key

That's it.

---

## Bring Your Own API Key

LoopNote follows a BYOK (Bring Your Own Key) model.

Benefits:

* No subscriptions
* No shared rate limits
* No server costs
* Full control over usage
* No dependency on a third-party backend

Your API key remains stored locally in your browser.

---

## Tech Stack

* Chrome Extensions Manifest V3
* Vanilla JavaScript
* Chrome Storage API
* Groq API
* llama-3.1-8b-instant
* Zero dependencies
* Zero build tools

---

## Who Is It For?

* Students studying complex subjects
* Researchers navigating long conversations
* Developers working through technical problems
* Writers and knowledge workers
* Anyone who spends hours inside ChatGPT

---

## Philosophy

ChatGPT helps you explore ideas.

LoopNote helps you stay in flow while doing it.

Because sometimes the biggest productivity killer isn't a difficult problem—it's losing your place while trying to solve a small one.

---

Built for learners, researchers, developers, and curious minds.
