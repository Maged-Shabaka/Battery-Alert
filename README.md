# 🔋 Battery Alert

A simple Python application that monitors your laptop battery and sends a Windows notification when the battery level drops to 30% or below while the charger is disconnected.

## ✨ Features

🔋 Monitors the current battery percentage.

🔌 Detects whether the charger is connected.

⚠️ Sends a Windows notification when the battery is low.

⏱️ Checks the battery status every 60 seconds.

🚫 Prevents repeated notifications while the battery remains low.

## 🚀 Installation

Clone the repository:
```text
git clone https://github.com/Maged-Shabaka/Battery-Alert.git
cd Battery-Alert
```

Create and activate a virtual environment:
```text
python -m venv .venv
```
On Windows PowerShell:
```text
.venv\Scripts\Activate.ps1
```

Install the required dependencies:
```text
pip install -r requirements.txt
```
▶️ Usage

Run the application with:
```text
python Battery.py
```

The program will continuously monitor the battery.

When the battery reaches 30% or below and the charger is disconnected, a Windows notification will appear asking you to plug in the charger.

⚙️ Configuration

The battery threshold and checking interval can be changed directly in `Battery.py`.

For example:
```text
LOW_BATTERY_THRESHOLD = 30
CHECK_INTERVAL = 60
```

LOW_BATTERY_THRESHOLD → Battery percentage that triggers the notification.

CHECK_INTERVAL → Time between battery checks in seconds.

📁 Project Structure
```text
Battery-Alert/
├── Battery.py
├── requirements.txt
├── .gitignore
└── README.md
```
