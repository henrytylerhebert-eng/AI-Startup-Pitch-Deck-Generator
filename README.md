# ai-pitch-deck-generator
<div align="center">

<img src="images/banner.png" alt="AI Startup Pitch Deck Content Generator" width="100%" />

<br/><br/>

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Gradio](https://img.shields.io/badge/Gradio-5.0%2B-orange?style=for-the-badge&logo=gradio)](https://gradio.app/)
[![No API Key](https://img.shields.io/badge/No%20API%20Key-Required-green?style=for-the-badge)](https://github.com/)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)
[![Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/)

### Generate a full **12-slide professional investor pitch deck** in seconds — no API key needed!

</div>

---

## 📌 Overview

**AI Startup Pitch Deck Content Generator** is a lightweight, intelligent tool that helps founders, students, and entrepreneurs instantly generate a complete, professional, investor-ready pitch deck — simply by filling in a form.

Built with **Python + Gradio**, it works entirely on pre-built smart templates tailored to **6 industries** and **5 investor types**, meaning you get a fully customized pitch deck with zero AI API cost.

---

## ✨ Features

<img src="images/features.png" alt="Key Features" width="100%" />

| Feature | Details |
|--------|---------|
| 🏭 **6 Industry Templates** | Tech/Software, Healthcare/MedTech, Finance/FinTech, Retail/E-Commerce, Education/EdTech, Sustainability/GreenTech |
| 🎯 **5 Investor Profiles** | Angel Investor, Venture Capitalist (VC), Government Grant, Corporate/Strategic, Crowdfunding |
| 📊 **12 Professional Slides** | From Cover to The Ask — every section a real investor expects |
| ✏️ **Editable Output** | Live-edit the generated deck right inside the app |
| 📥 **Download as .txt** | Export your pitch deck offline |
| 📋 **One-Click Copy** | Copy the full deck to clipboard instantly |
| ⚠️ **Smart Validation** | Warns you if required fields are empty |
| 🆓 **No API Key Needed** | Runs 100% locally with no external dependencies |

---

## 🔄 How It Works

<img src="images/workflow.png" alt="Workflow" width="100%" />

1. **Fill in your startup details** — Name, Tagline, Industry, Investor Type
2. **Describe your business** — Problem, Solution, Target Audience, UVP
3. **Click Generate** — Get a complete 12-slide pitch deck instantly
4. **Edit and Export** — Customize the text, copy to clipboard, or download as `.txt`

---

## 📊 Generated Pitch Deck Structure

<img src="images/slides_overview.png" alt="Slides Overview" width="100%" />

Your generated deck includes all 12 slides that top investors expect:

| # | Slide | What's Included |
|---|-------|-----------------|
| 01 | **Cover / Title Slide** | Company name, tagline, founder, industry, date |
| 02 | **Executive Summary** | Business overview, investor-specific tone |
| 03 | **Problem Statement** | Pain points, current gaps, why it matters |
| 04 | **Our Solution** | Key features, UVP, differentiation |
| 05 | **Market Opportunity** | TAM / SAM / SOM, trends, timing |
| 06 | **Competitor Analysis** | Landscape, comparison table, moat |
| 07 | **Revenue Model** | Revenue streams, pricing tiers, 3-year projections |
| 08 | **Go-To-Market Strategy** | 3-phase launch plan, marketing channels |
| 09 | **Traction & Validation** | Milestones, social proof, early adopters |
| 10 | **Team** | Founders, co-founders, advisors |
| 11 | **Risk Analysis** | Top risks + mitigation strategies |
| 12 | **The Ask & Closing** | Funding ask, use of funds, investor benefits |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/ai-pitch-deck-generator.git
cd ai-pitch-deck-generator

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
python app.py
```

The app will launch in your browser at `http://localhost:7860`.

### Run on Google Colab

You can also open and run the notebook directly on Google Colab:

1. Upload `AI_Startup_Pitch_Deck_Content_Generator.ipynb` to Google Colab
2. Run all cells
3. Use the public Gradio link generated at the end

---

## 🏭 Supported Industries

| Industry | Market Size | Key Trends |
|----------|-------------|------------|
| 🖥️ Tech / Software | $5.2 Trillion | AI, Cloud, SaaS, Cybersecurity |
| 🏥 Healthcare / MedTech | $665 Billion by 2028 | Telemedicine, AI Diagnostics, Wearables |
| 💳 Finance / FinTech | $340 Billion by 2026 | BNPL, Blockchain, Open Banking |
| 🛒 Retail / E-Commerce | $8.1 Trillion by 2026 | D2C, Quick Commerce, AR Shopping |
| 📚 Education / EdTech | $400 Billion by 2025 | AI Tutors, Gamification, Microlearning |
| 🌱 Sustainability / GreenTech | $17 Trillion by 2030 | Carbon Credits, EV, Renewable Energy |

---

## 🎯 Investor Profiles

| Investor Type | Typical Ask | Focus |
|---------------|-------------|-------|
| 👼 Angel Investor | ₹25L – ₹2Cr / $50K–$500K | Team strength, early-stage idea |
| 💼 Venture Capitalist (VC) | ₹2Cr – ₹50Cr / $1M–$10M | Scalability, traction, 10x return |
| 🏛️ Government Grant | ₹10L – ₹5Cr / $20K–$1M | Social impact, job creation |
| 🏢 Corporate / Strategic | ₹5Cr – ₹100Cr / $2M–$20M | Synergies, IP value |
| 👥 Crowdfunding | ₹10L – ₹1Cr / $10K–$200K | Community appeal, product story |

---

## 📁 Project Structure

```
ai-pitch-deck-generator/
│
├── app.py                                        # Main Gradio application
├── AI_Startup_Pitch_Deck_Content_Generator.ipynb # Original Colab notebook
├── requirements.txt                              # Python dependencies
├── .gitignore                                    # Git ignore rules
├── README.md                                     # Project documentation
│
└── images/
    ├── banner.png                                # Project banner
    ├── features.png                              # Features overview
    ├── workflow.png                              # How it works diagram
    └── slides_overview.png                       # 12-slide structure
```

---

## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **UI Framework:** [Gradio](https://gradio.app/) 5.0+
- **Logic:** Pure Python with smart template dictionaries
- **Hosting:** Google Colab (notebook) / Local (app.py)

---

## 📝 Example Output

```
╔══════════════════════════════════════════════════════════════════╗
         🚀  FINSMART AI — INVESTOR PITCH DECK
         Generated on: March 26, 2025
╚══════════════════════════════════════════════════════════════════╝

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 SLIDE 1 — COVER / TITLE SLIDE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🏢 Company Name   : FinSmart AI
💡 Tagline        : "Smart Finance for Everyone"
👤 Presented By   : Rahul Kumar
🏭 Industry       : Finance / FinTech
🎯 Investor Type  : Venture Capitalist (VC)
...
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a new branch (`git checkout -b feature/your-feature`)
3. **Commit** your changes (`git commit -m 'Add your feature'`)
4. **Push** to the branch (`git push origin feature/your-feature`)
5. **Open a Pull Request**

### Ideas for contributions
- Add more industry templates (Real Estate, Agriculture, Logistics, etc.)
- Add PDF export functionality
- Add support for multiple languages
- Integrate with AI APIs for even smarter content generation
- Add slide-by-slide generation mode

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- [Gradio](https://gradio.app/) for the amazing open-source UI framework
- [Google Colab](https://colab.research.google.com/) for free GPU/compute access
- The startup & VC community for pitch deck structure inspiration

---

<div align="center">

**Made with ❤️ for founders, by founders**

⭐ If this project helped you, please give it a star!

</div>
