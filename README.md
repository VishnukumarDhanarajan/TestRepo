# Application Profile Dummy Repo

This repository is a dummy application designed to demonstrate a complete Application Profile document.
It includes a reusable template and a filled sample profile based on repository facts.

## What is included

- `docs/Application-Profile-Template.md`: Blank profile template with placeholders.
- `docs/Application-Profile-Sample.md`: Populated example profile for this dummy app.
- `src/main.py`: Minimal FastAPI service.
- `tests/test_health.py`: Basic test for health endpoint.
- `.github/workflows/ci.yml`: Example CI pipeline.
- `.env.example`: Environment variable names only.

## Run locally

1. Create and activate a virtual environment.
2. Install dependencies:
   `pip install -r requirements.txt`
3. Start server:
   `uvicorn src.main:app --reload`
4. Open:
   `http://127.0.0.1:8000/health`

## Notes

- Main branch is expected to be `main`.
- No secrets are stored in this repository.
