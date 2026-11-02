# Gemini API for Xia Jarvis

LifeOS already accepts an OpenAI-compatible remote LLM, so Gemini needs no code change.

## Local configuration

Create your Gemini key in Google AI Studio. In the local .env file only, set:

LIFEOS_LLM_BACKEND=remote
LIFEOS_REMOTE_LLM_LABEL=Gemini Flash
LIFEOS_REMOTE_LLM_URL=https://generativelanguage.googleapis.com/v1beta/openai/
LIFEOS_REMOTE_LLM_MODEL=gemini-3.8-flash
LIFEOS_REMOTE_LLM_API_KEY=PASTE_KEY_HERE
LIFEOS_REMOTE_LLM_TIMEOUT=90

## Safety

Never commit .env or paste the key into GitHub, chat or screenshots. Keep approval checks on for messages, calendar changes, purchases, cancellations and deletion.

Gemini Free Tier is rate-limited and Google may use Free Tier prompts and responses to improve products. Do not route sensitive personal data through it unless you accept that trade-off.

## Test

Start LifeOS, select Gemini Flash, then ask: Say hello in one sentence.

If authentication fails, create a new key in AI Studio. If the quota is exhausted, wait for its reset or choose another available free-tier model.