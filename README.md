# Sareena Parikh

I studied cognitive science with an AI focus at Barnard College, Columbia University, with minors in statistics and psychology. I focus on the gap between what an AI system seems to do and what it actually does.

[LinkedIn](https://www.linkedin.com/in/sareena-parikh-80720024b)

## Projects

**[connections](https://github.com/sareenap13/connections)** Did my agents get better or just get closer? In my word-chain game, one agent hides a chain of linked words and another tries to follow it. After every batch, the setter studies its misses and rewrites its own strategy. A held-out GPT-5 mini guesser checks whether the setter got clearer in general or only easier for its partner to read. The strategy notes didn't help. Turning on extended thinking did. Demoed at AI Tinkerers NYC.

**[llm-crisis-response-eval](https://github.com/sareenap13/llm-crisis-response-eval)** How do four LLMs respond when someone describes suicidal thoughts? I rebuilt the labels from a class study with a validated yes/no classifier, and the original conclusion reversed. The models do respond to risk, but very unevenly. Claude and Mistral gave crisis resources in all 11 explicit cases. GPT-4o and LLaMA gave them in about half.

**[voice-briefing-agent](https://github.com/sareenap13/voice-briefing-agent)** Turns an article into a short spoken briefing. A FastAPI backend chains OpenAI (summary) and ElevenLabs (text-to-speech) into one pipeline, with input validation, safety limits and graceful fallbacks when the audio service fails.

**[minivsaas](https://github.com/sareenap13/minivsaas)** Real-time video analytics on YOLOv8 and ByteTrack. It tracks objects, estimates direction of travel, flags loitering and draws a live heat map. A sports mode adapts it to game footage and measures the distance each player covers.

**[bookrecommender](https://github.com/sareenap13/bookrecommender)** Book recommendations from a Goodreads export. It ranks a catalog of about 1,500 books with sentence-transformer embeddings, Bayesian-smoothed ratings and popularity.

**[sunny-streaks](https://github.com/sareenap13/sunny-streaks)** A two-player health competition. Friends log water, steps, workouts, mobility and sleep, and scores sync live and reset every 14 days.

## Background

- Senior thesis, passed with distinction. A 40-person experiment on how competing against a partner changes working memory. Competition reduced misses and sped up recall.
- AI Engineering Intern at Kura Labs. Developed LLM-powered learning advisors that about 30 students tested, plus agentic pipelines with n8n, Canvas and ServiceNow.
- Research assistant in the Davachi Memory Lab at Columbia, working with fMRI data.

## Tools

Python, JavaScript, FastAPI, PyTorch, sentence-transformers, scikit-learn, pandas, YOLOv8, OpenCV, OpenAI and Anthropic APIs, Streamlit, Firebase, PostgreSQL, n8n
