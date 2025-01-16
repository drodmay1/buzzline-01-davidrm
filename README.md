# Buzzline Streaming Analytics

This project demonstrates streaming analytics using Python with producer and consumer scripts. Below are details about the custom producer and consumer scripts added.

## Custom Producer Script

The custom producer script generates random "buzz" messages and writes them to a log file.

### Running the Custom Producer

Mac/Linux:
```bash
source .venv/bin/activate
python3 producers/basic_producer_davidrm.py`
```

## Custom Consumer Script

The custom consumer script reads log messages in real-time and processes them, monitoring for specific conditions.

### Running the Custom Consumer

Mac/Linux:
```bash
source .venv/bin/activate
python3 consumers/basic_consumer_davidrm.py
```

## Requirements

* Python 3.11
* Virtual environment installed (.venv)
* External dependencies installed (see requirements.txt)

## Installing Dependencies

After activating the virtual environment, install dependencies:

```bash
pip install -r requirements.txt
```

## Commit and Push the Changes

```bash
git add
git commit
git push
```
