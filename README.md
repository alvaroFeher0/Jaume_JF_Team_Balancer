# ⚽ Jaume – JF League Team Balancer

**Jaume** is a charismatic football assistant powered by AI who helps balance teams for the **JF League**.  
He speaks Spanish, quotes Andrés Montes, and uses real performance data from Firebase to create fair, competitive matches.

Built with ❤️ using **Streamlit**, **OpenAI**, and **Firebase**.

---

## 🚀 Features

- 🤖 **AI Assistant** trained with contextual league data (players, matches, and performance actions).
- ⚽ **Automatic Team Balancer** — splits players into *Team Blanc* and *Team Negre*.
- 🧠 **Context-Aware Decisions** — Jaume explains his reasoning for every balance.
- 🗣️ **Interactive Chat** interface — talk to Jaume directly inside the browser.
- ☁️ **Firebase Integration** — dynamically loads up-to-date player and match data.
- 🔒 Secure API key management via Streamlit Secrets.

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| Frontend / UI | [Streamlit](https://streamlit.io) |
| AI Model | OpenAI API (`gpt-5-nano`) |
| Data Source | Firebase (Players, Matches, Actions) |
| Environment | Python 3.10+ |
| Deployment | Streamlit Cloud |

---

## ⚙️ Setup & Installation

### 1. Clone the repo

```bash
git clone https://github.com/<your-username>/jf-league-assistant.git
cd jf-league-assistant
