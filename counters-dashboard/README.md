# Counters Dashboard

A dashboard application for processing and visualizing counter data.

## Project Structure

```
counters-dashboard/
  dropzone/       # Drop files here for processing
  processed/      # Processed files are moved here
  db/             # Database storage
  app/
    app.py        # Main application
  src/
    __init__.py
    config.py     # Configuration settings
    db.py         # Database utilities
    ingest.py     # Data ingestion logic
    transforms.py # Data transformation utilities
  requirements.txt
  README.md
```

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the application:
   ```bash
   python app/app.py
   ```

