<img src="app/assets/DALL·E%202025-03-25%2020.36.13%20-%20A%20playful,%20satirical%20logo%20representing%20an%20application%20that%20humorously%20'roasts'%20GitHub.%20Incorporate%20cartoonish%20flames%20around%20a%20GitHub-like%20cat%20silhouet.jpg" width="300" alt="Coco Logo">

# 🔥 COCO

✨ **A brutally honest AI that roasts your GitHub code with savage yet constructive feedback**

---

## 🌟 Roasting Features

🔥 **Savage Code Reviews**  
   - Brutally honest feedback on your worst code  
   - Finds and mocks common anti-patterns  
   - Rates your code on a "spiciness" scale  

🔪 **Pull Request Roasts**  
   - Hilarious commentary on questionable PRs  
   - Detects and calls out lazy commits  
   - Generates meme-worthy reactions  

💀 **Vulnerability Shaming**  
   - Publicly shames security flaws  
   - Creates "Wall of Shame" for bad practices  
   - Suggests fixes with sarcastic tone  

🤖 **AI-Powered Burns**  
   - Custom roasts based on your coding style  
   - Compares your code to famous disasters  
   - Generates savage one-liners for bad code  

---

## 🛠️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/coco.git
cd coco

# 2. Install dependencies
pip install -r requirements.txt

# 3. Set up environment (see below)
```

---

## ⚙️ Configuration

Create `.env` file:

```ini
# GitHub Configuration
GITHUB_TOKEN=your_personal_access_token
GITHUB_ORG=your_organization  # Optional

# AI Configuration
OPENAI_API_KEY=your_api_key
ANTHROPIC_API_KEY=your_api_key  # Optional

# App Settings
DEBUG=True  # Set to False in production
PORT=5000
```

---

## 🚦 Usage

Start the application:

```bash
python run.py
```

**Example API Requests:**

```python
import requests

# Get repository analysis
response = requests.get(
    "http://localhost:5000/api/repositories/analysis",
    params={"repo": "username/reponame"},
    headers={"Authorization": "Bearer YOUR_TOKEN"}
)
```

---

## 🏗️ Project Structure

```text
app/
├── api/          # 🚪 API endpoints and routes
├── models/       # 🏛️  Data models and schemas
├── services/     # ⚡ Business logic
└── utils/        # 🧰 Helper functions
```
