# Examples

## Run the provided example

### Script Example

    :::python
    # default model
    python examples/use_vita.py
    # Use other models
    python example/use_{model_name}.py

### Code-Block Example

    :::python
    from vita import TTS
    tts = TTS()
    for i, text in enumerate(["Hello", "How are you?", "Bye"]):
        tts.generate_audio(text, output_path=f"clip_{i}.wav")


