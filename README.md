
---

## � **Getting Started**
### 1. Setup Environment
```bash
# Clone this repository
git clone https://github.com/swaminandan/llm_code.git

# Create virtual environment (Python)
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.\.venv\Scripts\activate   # Windows

# Install dependencies
pip install --no-cache-dir -r requirements.txt

# Clean installation within .venv
source .venv/bin/activate
pip freeze > installed.txt
pip uninstall -y -r installed.txt
rm installed.txt