# Installing Rasa with Python 3.12 Failed

## ❌ Problem
Rasa fails to install with Python 3.12 due to older dependencies (e.g., absl-py).

## ✅ Solution
Install Python 3.10 and create a new venv:

```bash
sudo apt install python3.10 python3.10-venv
python3.10 -m venv ~/rasa310
source ~/rasa310/bin/activate
pip install rasa
