# Draughts Pro - FastAPI Backend

This is the backend for Draughts Pro, built with FastAPI.

## Setup Instructions

1. Create a virtual environment:
   ```bash
   python3 -m venv venv
   ```

2. Activate the virtual environment:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   ```bash
   cp .env.example .env
   ```
   (Then, fill in any necessary values in your new `.env` file.)

5. Start the development server:
   ```bash
   python main.py
   ```
