# ReplyFlow AI — Email Reply Generator

A polished Streamlit email reply drafting app with animated gradients, floating visuals, glassmorphism panels, editable previews, and tone controls.

## Features
- Professional, Casual, and Friendly reply tones
- Concise, Balanced, and Detailed drafts
- Optional context and recipient name
- Editable preview and download as a text file
- Basic demo mode without an API key
- Optional OpenAI-powered replies using `OPENAI_API_KEY`
- No automatic email sending

## Run locally
```bash
py -m pip install -r requirements.txt
py -m streamlit run app.py
```

## Enable AI replies
Add `OPENAI_API_KEY=your_api_key_here` to a local `.env` file, or configure it in Streamlit Community Cloud app Secrets:
```toml
OPENAI_API_KEY = "your_api_key_here"
```
Never commit your API key or `.env` file.

## Deploy
In Streamlit Community Cloud, create an app from this repository and set the main file path to `app.py`.
