# Liberating claude with prefills

Jailbreaking anthropic models using assistant prefill. 

With great power comes great responsibility, please wield wisely. 

## Try it out

1. Clone the repository:
```bash
git clone https://github.com/arjunkmrm/anthropic-jailbreak.git
cd anthropic-jailbreak
```

2. Set up a virtual environment (optional but recommended):
```bash
python -m venv ".venv"
source .venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies from requirements.txt:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
   - Copy the `.env.example` file to a new file named `.env`:
     ```bash
     cp .env.example .env
     ```
   - Open the `.env` file and add your Anthropic API key:
     ```
     ANTHROPIC_API_KEY=your_api_key_here
     ```

5. Go to prefill-jailbreak notebook and play around!