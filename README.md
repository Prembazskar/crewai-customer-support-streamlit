# CrewAI Customer Support Multi-Agent System

A Streamlit app backed by three CrewAI agents that answer customer queries, research the web when needed, and record each support case.

> Part of my Gen AI course practice work (Week 4, Day 5).

## Tech stack

- Python 3
- CrewAI
- Streamlit
- OpenAI
- Serper

## Features

- Customer Support Assistant agent
- Web Research Specialist agent (Serper search)
- Record Specialist agent saving cases to `outputs/support_records.json`
- Streamlit UI

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/Prembazskar/crewai-customer-support-streamlit.git
   cd crewai-customer-support-streamlit
   ```
2. Install and configure:
   ```bash
   pip install -r requirements.txt
   cp .env.example .env   # OpenAI and Serper keys
   ```

Environment variables (set in `.env`, never commit it):

- `OPENAI_API_KEY`
- `SERPER_API_KEY`
- `MODEL`

## Usage

```bash
streamlit run app.py
```

## License

MIT, see [LICENSE](LICENSE).
