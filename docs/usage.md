# Usage

### Python API

    :::python
    from vita import TTS

    tts = TTS()  # defaults to Kokoro-82M if configured that way
    tts.generate_audio(
        "This is VITA speaking.",
        output_path="demo.wav"
    )

Tips
Pass different model names/voices (as VITA exposes them) once multi-model switches are live.

Keep outputs as .wav for clean pipelines; convert to MP3/OGG in your app if needed.

### CLI

    :::python
    python -m vita --text "Hello from VITA!" --output hello.wav

### Typical flags (as implemented)

- --text – text to synthesize
- --output – path to save the generated .wav


