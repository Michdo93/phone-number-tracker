# phone-number-tracker

This script will create a html file with a map which should show where a phone number is tracked.

---

## Installation

You have to clone this repository and then you have to create at first a virtual environment. After that you have to install different dependencies via `pip`.

### Linux

On Linux you have to run:

```
git clone https://github.com/Michdo93/phone-number-tracker
cd phone-number-tracker
python -m venv .
source bin/activate
pip install -r requirements.txt
```

### Windows

On Windows you have to run:

```
git clone https://github.com/Michdo93/phone-number-tracker
cd phone-number-tracker
python -m venv .
\.Scripts\activate
pip install -r requirements.txt
```

---

## Usage

You have to run 

```
python phone_number_tracker.py -p <phone_number>
```

This will create a html file with the given phone number. After the script is ready you can open this html file in your browser.

---
