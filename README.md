# 🌟 Astra Core

A tool-using AI agent in a Jupyter notebook that runs **free, with no API key and no extra installs**.

## Features
- Agent loop: plan → pick a tool → act → reply
- Tools: calculator, time & date, Wikipedia, weather, notes (saved to a file), jokes, coin/dice
- Remembers your name and notes
- Only Wikipedia and weather need internet; everything else works offline

## Run it
```bash
pip install jupyter
jupyter notebook Astra_Core_Agent.ipynb
```
Click **Run All**, then chat in the last cell. Works in Jupyter, VS Code, and Google Colab.

## Optional: LLM version
`Astra_Core_Agent_API.ipynb` is the same idea powered by the Anthropic API. It needs an API key
(`ANTHROPIC_API_KEY`) and `pip install anthropic requests`. Never commit your key.

## Example prompts
`what is 25 * 4 + 10` · `time in Tokyo` · `who is APJ Abdul Kalam` · `weather in Coimbatore` · `remember buy milk`
