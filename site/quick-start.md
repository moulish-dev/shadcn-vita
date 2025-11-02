# Quick Start

## Install (fast path)

> Requires **Python 3.11** (as per the project README).

    :::python
    git clone https://github.com/moulish-dev/vita.git
    cd vita
    python3.11 -m venv .venv
    source .venv/bin/activate   # Windows: .venv\Scripts\activate
    pip install -r requirements.txt
    pip install -e .
    

### Code-Block Example

    :::python
    from vita import TTS
    tts = TTS()
    tts.generate_audio("This is VITA speaking.", output_path="demo.wav")

### CLI Example

    :::python
    python -m vita --text "Hello from VITA!" --output hello.wav

---

