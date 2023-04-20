## Our intended J.A.R.V.I.S. stack:

1. Porcupine wake word (i.e. "sirJarvis")
2. On prem [Mozilla DeepSpeech](https://github.com/mozilla/DeepSpeech) `speech` to `text`
3. query gpt-4 api with `text`
4. On prem [Mozilla TTS](https://github.com/mozilla/TTS)
