# AI Documentary Studio — Starter v0.1

A mobile-friendly, static planning prototype for a semi-automated documentary workflow.

## What works now
- Enter a documentary topic, target duration, narration language, and style.
- Generate a chapter plan in the browser.
- Create a handoff prompt for an AI writing assistant.
- Copy the prompt or download a plain-text production brief.

## What does not work yet
This starter does **not** call an AI API, perform live research, generate video, create voiceovers, or render MP4 files. Those require separate integrations and, in many cases, paid API usage.

## Deploy free with GitHub Pages
1. Upload `index.html` to the root of your GitHub repository.
2. Open the repository's **Settings**.
3. Open **Pages** under **Code and automation**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for the Pages deployment to finish. Your site URL will appear in the Pages section.

## Security
Never put API keys, passwords, or private tokens in `index.html` or any public repository. Future API integrations must use a secure server-side backend and environment secrets.

## Suggested next milestones
1. Add an editable research and source-review screen.
2. Add script generation through a secure backend.
3. Add chapter-by-chapter approval and scene prompt management.
4. Integrate a video provider and text-to-speech provider.
5. Add background jobs, storage, retries, and FFmpeg rendering.
