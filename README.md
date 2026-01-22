# LCS
LEGAL CONTRACT SUMMARIZER
# Legal Summarizer & Risk Highlighter

A lightning-fast, AI-powered contract review assistant. This tool provides concise plain-language summaries, extracts key clauses, and highlights potential risks (like one-sided indemnification or termination clauses) to speed up legal review.

## 🚀 Features

- **Instant Summarization**: Converts complex legal jargon into an executive summary.
- **Risk Analysis**: Automatically flags High, Medium, and Low risks (e.g., Indemnity, Liability Caps).
- **Clause Extraction**: Identifies and isolates key clauses for quick verification.
- **Redline Suggestions**: Offers AI-generated suggestions to mitigate identified risks.
- **Impact Metrics**: Estimates time saved per contract review.

## 🛠️ Tech Stack

- **Frontend**: HTML5, JavaScript (Vanilla), Tailwind CSS (via CDN).
- **AI/ML (Simulation)**: Designed to integrate with **Google Vertex AI** for NLP and **Google Document AI** for OCR.
- **Storage**: Designed for Google Cloud Storage / Drive integration.

## 📦 Installation & Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DyNATgIT/LEGAL-SUMMARIZER.git
   ```

2. **Open the application**:
   Simply open the `index.html` file in any modern web browser. No build step or server is required for the frontend MVP.

3. **Demo Mode**:
   - Click **"Use Sample NDA"** to populate the text area with a sample contract.
   - Click **"Analyze Contract"** to see the simulated AI results.

## 🔮 Future Roadmap

- **Google Drive Integration**: OAuth 2.0 flow for direct file picking.
- **Real-time Backend**: Python/Flask backend connecting to Vertex AI API.
- **User Accounts**: Save and history of analyzed contracts.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---
*Disclaimer: This tool is for demonstration and informational purposes only and does not constitute legal advice. Always review contracts with a qualified attorney.*
