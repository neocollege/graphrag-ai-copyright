# graphrag-ai-copyright

Based on the YouTube video: https://www.youtube.com/watch?v=JTVx6i6MzVw

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Register the notebook kernel (already done once, repeat after recreating the venv):

```bash
python -m ipykernel install --user --name graphrag-ai-copyright \
  --display-name "Python (graphrag-ai-copyright)"
```

Copy `.env.example` to `.env` and fill in your `SERPAPI_API_KEY`.
