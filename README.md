# SnapCode AI ⚡
> See it. Code it. — Powered by Qubrid AI × Kimi K2.5

## What it does
Upload any UI screenshot or mockup → get complete HTML + Tailwind CSS code 
that recreates it. Powered by Kimi K2.5's native vision-to-code capability 
via the Qubrid AI platform.

## Setup
1. Clone the repo
2. Install [uv](https://docs.astral.sh/uv/) if you haven't already.
3. Copy `.env.example` → `.env` and add your `QUBRID_API_KEY`
4. Launch the app with: `uv run streamlit run app.py` (uv will automatically install all dependencies!)

## Architecture
- `app.py`: Main Streamlit entry point.
- `backend/`: API interactions and image processing utilities.
- `frontend/`: Custom UI components and styling definitions.
- `config/`: App settings and constants.

## Powered by
- Kimi K2.5 (Moonshot AI) via Qubrid AI API
- Streamlit
- Tailwind CSS (generated output)
