## News Summarizer

Small test project using OpenAI free trial.
Summarizer scapres the italian news site ```https://ansa.it/``` for the most recent news, feeds them to the ChatGPT 3.5 turbo model and produces a translated and summarized version of them, saving them to the ```translated_articles.txt``` file.

Additionally, a non-translated version is available in the ```articles.txt``` file.

## How to use

set your OpenAI API key as an environment variable using:

### On Windows

```bash
setx OPENAI_API_KEY "your_key_value"
```
### On Unix Systems

```bash
export OPENAI_API_KEY = "your_key_value"
```

The model can be used to perform various tasks on the input file by editing the ```prompt.txt``` file.

#### Additional Notes
If you're relying on a free OpenAI plan (like me), expect the output to be truncated depending on the maximum request rate allowed. 
