# Assignment: Emoji Translator

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ORG_NAME/REPO_NAME/blob/main/emoji_map.ipynb)

In this exercise, you will build a simple emoji translator in Python.
The goal is to replace certain emotion adjectives (like happy, sad, angry) with matching emojis.

# Task

You are given a dictionary of words mapped to emojis:

```python
EMOJI_MAP = {
    "happy": "😀",
    "joyful": "😄",
    "excited": "🤩",
    "proud": "😌",
    "calm": "🙂",
    "confident": "😎",
    "playful": "😜",
    "silly": "🤪",
    "angry": "😡",
    "frustrated": "😤",
    "sad": "😢",
    "lonely": "🥺",
    "scared": "😱",
    "worried": "😟",
    "tired": "😴",
    "confused": "🤔",
    "surprised": "😮",
    "loving": "❤️",
    "grateful": "🙏"
}
```

Write Python codes in **emoji_map.ipynb** to:

* Splits the input text into words.

* Replaces words found in EMOJI_MAP with their emoji.

* Keeps all other words unchanged.

For example, "I am happy but also tired" will be converted to "I am 😀 but also 😴"


