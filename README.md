# Playwright Speedometer

Runs Speedometer 3.1 in Playwright and prints the final score.

## Setup

```bash
python -m venv venv
source venv/bin/activate
pip install playwright
playwright install firefox chromium
```

## Usage

Headless (default):

```bash
python3 firefox-playwright/run_speedometer.py
```

Headful:

```bash
python3 firefox-playwright/run_speedometer.py --headful
```

Run in Chrome:

```bash
python3 firefox-playwright/run_speedometer.py --browser chrome
```

`--browser chrome` uses Playwright's Chrome channel and requires Google Chrome to be installed on the host.

Run both Firefox and Chrome:

```bash
python3 firefox-playwright/run_speedometer.py --browser firefox --browser chrome
```

JSON output:

```bash
python3 firefox-playwright/run_speedometer.py --json
```
