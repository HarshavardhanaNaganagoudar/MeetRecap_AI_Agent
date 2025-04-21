# 🤖 MeetRecap — AI-Powered Meeting Summarizer

**Your meeting assistant that listens so you don't have to take notes.**

---

## 📌 What is MeetRecap?

Have you ever finished a long meeting and thought:
> “Wait, what did we decide again?” or “Who was supposed to do what?”

**MeetRecap** is an AI agent that takes a recorded meeting audio file (`.wav`) and summarizes everything important:
- 👥 **Attendees**
- 💬 **Key Discussion Points**
- ✅ **Action Items**
- 📎 **Decisions Made**

---

## 🚀 Live Demo

Try it out now with one click:

[👉 Launch on Hugging Face Spaces](https://huggingface.co/spaces/nharshavardhana/MeetRecap)

---

## 🛠 How It Works (in 4 Simple Steps)

1. **Upload** your `.wav` meeting recording.
2. **Click Summarize** – the AI listens using Whisper and generates a transcript.
3. The transcript is **analyzed and summarized** by a language model (like Mistral).
4. You get a clean summary with **attendees**, **key points**, **action items**, and **decisions**.

---

## 💡 Real-World Use Cases

- Teams who don’t have a dedicated note-taker.
- Project managers who want summaries of daily standups.
- Students or professionals who want a quick recap of lectures or discussions.

---

## 🧠 Under the Hood (For Curious Minds)

| Task | Model Used |
|------|------------|
| Transcription | [`Whisper`](https://github.com/openai/whisper) |
| Summarization | [`Mistral-large-latest`](https://mistral.ai) |
| Workflow Orchestration | [`LangGraph`](https://www.langgraph.dev/) |
| UI | [`Gradio`](https://gradio.app) |

---

## 🌍 Language Support

Currently supports **English** only.  
Multilingual support (e.g., German, Spanish) is on the roadmap. Stay tuned!

---

## 🖼 Example Summary Output

```text
📌 Attendees:
- Alice Johnson
- Bob Smith
- Carol Zhang

💬 Key Points:
- Discussed Q2 product roadmap and new feature rollout.
- Marketing strategy needs more budget allocation.
- Customer feedback loop is underdeveloped.

✅ Action Items:
- Alice to draft revised roadmap by next Monday.
- Bob will reach out to marketing for budget realignment.
- Carol to analyze customer feedback trends.

📎 Decisions:
- Move feature launch to mid-June.
- Allocate 10% more budget to digital marketing.

