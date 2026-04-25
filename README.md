# TOS-IC | Savage Legal Scanner ☢️

TOS-IC (Terms of Service - Intelligence / Check) is an AI-powered, savage legal scanner that analyzes Terms of Service (ToS) agreements, Privacy Policies, and other complex legal documents. Built with Streamlit and the Gemini API, it cuts through the legal jargon to highlight the worst-case scenarios, generate satirical legal-tech threat memes, and tell you what you're _actually_ agreeing to.

## Features

- **Deep Legal Analysis:** Upload or paste legal texts/URLs and get a brutal breakdown of exactly what rights you're signing away.
- **Savage Mode:** Not just an analysis. It gives you the raw, unfiltered truth about the terms you're agreeing to.
- **Threat Meme Generation:** Automatically generates a viral, sarcastic warning meme/poster (SVG/PNG) summarizing the worst parts of the ToS.
- **Document Support:** Analyzes raw text, scrapes URLs (via BeautifulSoup), and reads PDF documents (via PyPDF).
- **Comparison Tool:** Compare different versions of ToS or different companies' policies against each other.

## Prerequisites

Before running TOS-IC, ensure you have:

- Python 3.8+
- A Google Gemini API Key

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/tos-ic.git
   cd tos-ic
   ```

2. **Set up a virtual environment (Recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

   _Note: If meme generation image formats fail, ensure you have system-level dependencies for `cairosvg` installed (like `libcairo2` on Linux)._

4. **Set up your Environment Variables:**
   Create a `.env` file in the root directory and add your Gemini API Key:

   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

## Usage

Run the Streamlit application from your terminal:

```bash
streamlit run app.py
```

The app will launch in your default web browser (usually at `http://localhost:8501`). From there, you can paste text, upload a PDF, or drop a URL to start scanning.

## Disclaimer

**TOS-IC is an AI-powered tool and should NOT be considered actual legal advice.** The threat memes and analyses are generated for satirical, educational, and awareness purposes. Always consult a real, human lawyer for actual legal matters.
