# 🤖 Autonomous LinkedIn Multi-Agent Content Engine

An enterprise-grade, fully automated content pipeline built on **n8n** using an advanced **AI Multi-Agent System**. With just a single form input (Topic, Audience, Email), this system conducts real-time research, crafts highly engaging LinkedIn posts, designs high-quality visual prompts, generates custom marketing graphics, publishes directly to LinkedIn, and notifies your team via Slack.

---

## 🔄 How the Workflow Works
[n8n Form] ➔ [Tavily Web Search] ➔ [Gemini: Post Writer] ➔ [Gemini: Image Prompter] ➔ [Gemini: Title Hook Generator] ➔ [Pollinations AI] ➔ [LinkedIn API] ➔ [Slack Alert]

1. **Trigger:** User submits a topic and target audience via an **n8n Form**.
2. **Research Agent:** Uses **Tavily AI Search** to fetch real-time, factual insights, trends, and statistics.
3. **Copywriting Agent:** Powered by **Google Gemini**, it structures a high-impact LinkedIn post with hooks and CTAs.
4. **Design Agent:** Extracts core insights to generate a minimalist visual design prompt.
5. **Graphics Engine:** Hits the **Pollinations.ai API** to generate customized marketing images on the fly.
6. **Hook Generator:** Creates an attention-grabbing title (20–30 words) for the post media.
7. **Publisher:** Instantly deploys the structured text and generated image to **LinkedIn**.
8. **Notifier:** Sends a success notification with the post title to a designated **Slack** channel.

---

## 🛠️ Tech Stack & Integrations

* **Workflow Automation:** n8n (Advanced AI Nodes)
* **LLM Orchestration:** Google Gemini (via Google AI Studio)
* **Search Engine:** Tavily AI API (For real-time web research)
* **Image Generation:** Pollinations.ai API
* **Social Integration:** LinkedIn Developer API
* **Communication:** Slack Webhooks

---

## 🚀 Features & Agent Specializations

* **Factual & Context-Aware:** No hallucinated data; the integration with Tavily ensures every post has current facts.
* **Brand-Consistent Design Language:** The Image Prompt Agent acts like a senior brand designer, avoiding typical messy AI artifacts.
* **Completely Autonomous:** Handles the entire research-to-publication cycle without human-in-the-loop intervention.

---

## 💻 Setup Instructions

### Prerequisites
* An active **n8n** instance (with Advanced AI features enabled).
* API Keys for:
  * Google AI Studio (Gemini)
  * Tavily AI
  * LinkedIn Developer Account
  * Slack App Webhook

### Installation
1. Download the `Linkedin Automation_ Multi Agent System.json` file from this repository.
2. Open your n8n instance.
3. Create a new workflow, click on the top-right menu (three dots), and select **Import from File**.
4. Upload the downloaded JSON file.
5. Configure your credentials for **Google Gemini**, **Tavily**, **LinkedIn**, and **Slack**.
6. Switch the workflow toggle to **Active**.

---

## 📌 Repository Tags (Topics)
`n8n` `multi-agent-systems` `linkedin-automation` `generative-ai` `workflow-automation` `google-gemini` `ai-agents` `content-marketing`
