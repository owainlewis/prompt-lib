# Prompt Lib

This is a collection of LLM prompts for personal use. 

My main interests are productivity and content creation.

These prompts assume that you have LLM installed. 

```
$ brew install llm 

$ llm keys set openai

# Install claude
$ llm install llm-claude-3
$ llm keys set claude
$ alias claude="llm -m claude-3.5-haiku"

# Install other models as needed
$ llm install llm-gemini
```

# Usage 

```
➜  prompt-lib claude "Fun facts about penguins"
Here are some fun facts about penguins:

1. Habitat
• Penguins live primarily in the Southern Hemisphere
• They can be found in Antarctica, South America, New Zealand, and South Africa
```