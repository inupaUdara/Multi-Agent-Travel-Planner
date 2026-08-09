# Multi-Agent-Travel-Planner

## Environment Variables

Create a .env file in the project root with the following variables:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/travel_db
GROQ_API_KEY=your_groq_api_key
AVIATIONSTACK_API_KEY=your_aviationstack_api_key
TAVILY_API_KEY=your_tavily_api_key
DEFAULT_ORIGIN_IATA=DAC
```

## Installation

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Running the App

Start the FastAPI server:

```bash
python app.py
```

postgresql://inupa:RDtNFyJuwDnNmqGToT8mTvfHgNWDhfp8@dpg-d9s92qf10e5c739fhda0-a.oregon-postgres.render.com/agentmemory_e6u4

RDtNFyJuwDnNmqGToT8mTvfHgNWDhfp8