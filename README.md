# LLM Meeting Transcriber

Create meeting minutes from an Audio file

Exercise from the LLM Engineering week 3 / day 5 project [here](https://github.com/ed-donner/llm_engineering/blob/main/week3/day5.ipynb).

## Install and run

This requires that you set your Hugging Face token, `HF_TOKEN`, in a local `.env` file.

**NOTE**: you need to provide your own audio file and save it with the name `sample.mp3` in the [audio](./audio/) folder.

```bash
uv run main.py
```

You might need to install `ffmpeg`. Using `brew` run:

```bash
brew install ffmpeg
```