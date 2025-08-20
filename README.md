This application allows you to generate short 8-seconds videos from text prompts in a Chabot-styled UI. The app uses n8n workflow for the backend. The workflow calls Replicate’s google/veo-3 model, waits for completion, and returns a playable MP4 (or a URL) back to the page.

Features:
Chat-style UI with typing dots & error bubbles
Google VEO-3 via Replicate API
Robust polling until the video is ready (no half-baked responses)
Two response modes

To do:
Fix the error - Return JSON { video_url }
Stream the MP4 directly from n8n (best reliability)
Hosting and scaling 

Prerequisites:
Replicate account + API token: https://replicate.com/account/api-tokens
n8n (Docker or npm)

Setup:
1) Run n8n locally
Docker or NodeJS

Tutorial here: 

2) Sign-in and then import the workflow

3) Setup "api_token"

4) 
