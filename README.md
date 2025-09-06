# Creative AI Agent – Example Repo

This is an example repository for the [Creative AI Agents Hackathon](https://tally.so/r/3Njjdl).  
It shows how to structure your submission so the jury can easily understand and test your project.

---

## 🚀 Project Overview

This project demonstrates how to connect **n8n** automation workflows with **Black Forest Labs (BFL)** generative AI.

**What it does:**
- Takes a text prompt (e.g. from Google Sheets, Discord, or a webhook).
- Passes the prompt to BFL to generate an image.
- Saves the image to a folder and posts it to Discord.

---

## 🛠️ Setup Instructions

### Requirements
- [n8n](https://n8n.io) (self-hosted or cloud)
- Black Forest Labs API key ([get it here](https://docs.bfl.ai/quick_start/introduction))
- (Optional) Discord bot/webhook for posting results

### Steps
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/creative-ai-agent-demo.git
   cd creative-ai-agent-demo
