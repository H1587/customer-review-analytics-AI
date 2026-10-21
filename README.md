# Customer Review Analytics

An AI-powered customer review analytics project built using Python and Google Colab.

## Features
- Extracts reviews from a demonstration restaurant website
- Classifies overall sentiment using LLM APIs
- Analyzes food quality, service, and ambience
- Generates customer-service response suggestions
- Exports review analysis to Excel
- Supports importing manager responses into the demonstration website
- Visualizes ratings, sentiment, and review categories in a dashboard

## Technologies
- Python
- Playwright
- Pandas
- Google Gemini API
- Groq API
- Excel (openpyxl)
- Google Colab

## Project Structure
- `notebooks/` - analysis notebook
- `data/` - sample review data
- `outputs/` - example analysis exports

## Setup
Open the notebook in Google Colab and provide your own API keys through
Colab Secrets or secure runtime input. Never commit API keys.

## Data Notice
The restaurant reviews are demonstration-project data and should not be
treated as verified real customer feedback.

## Limitations
API quotas and model availability can affect processing. The notebook
may use different LLM providers for different reviews.

## License
MIT
