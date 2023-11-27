---
title: "Art of Creating Great Prompts"
date: 2023-11-26
tags: ["ai", "chatbot", "chatgpt"]
image : "https://github.com/StubbornDeer/public-media-files/assets/91156314/87f3f3f5-a419-495f-8b5f-7bf31893c218"

Description  : "Let's Master the Art of Creating Effective ChatGPT Prompts!"
featured: true
---


A good prompt is half the battle for success - alongside the data you provide for your chatbot. However, it may not be very obvious how to create a prompt that the chatbot would understand and strictly follow. Let's review the main principles you should always consider when creating a prompt.

## 7 Principles for Crafting Effective Prompts that Work

### Clarity and Specificity

- Clearly articulate your instruction.
- Avoid ambiguity to ensure the model understands your intent.
- Do not use idioms, abbreviations, or acronyms that the chatbot may not know.
- Avoid using "please," "thanks," and other words that don’t carry significant meaning. While seemingly harmless, they could lower the overall quality of the response.

### Avoid Open-Ended Instructions

If you want specific information, avoid overly open-ended prompts. Instead of "Tell me about dogs," try "List three interesting facts about dogs."

### Break Down Complex Queries

If your prompt involves multiple questions or tasks, break them down into smaller, more manageable parts. This helps the model focus on each aspect separately. Using this approach, you can create the entire workflow, but remember: you must be very clear and specific.

### Utilize the Roles' Capabilities

Provide high-level instructions to guide the model's behavior. For example, start your prompt with "You are an assistant that speaks like Shakespeare" to set a specific tone.

### Experiment with Different Inputs

- Try different types of prompts, such as open-ended questions, specific queries, or creative requests.
- Explore various topics and styles to understand the model's capabilities across different domains. Sometimes, the model works better when we remove common phrases like “you are a helpful assistant” and instead, specify what it exactly means.
- Avoid explanations - don’t tell why the chatbot should do it, but just say clearly what to do and what not to do.

### Understand Model Limitations

- Be aware of the model's limitations and potential biases.
- Adjust your prompts to account for the model's tendency to generate responses that may be overly verbose, repetitive, or off-topic.

### Less is Better

Don’t overcomplicate; make the prompt as short as possible. Move all the information that can be used only if a user asks about it to the data sources.

### Be Patient with Iterative Refinement

Improving prompt effectiveness often requires iterative refinement. Analyze model outputs, adjust prompts, and repeat the process to fine-tune your approach.

## Tips and Tricks:

### Use the question’s language 
You can add this metadata to your prompt: {language} to specify which language it should respond in (Note: use this only if you replace our default prompt, as this logic is already implemented in it).

### Use the date information
We provided the current date and time in the UTC timezone so you can try to use it. For example, you can add to your prompt something like “If the current month is December when you are greeted, say exactly "HowdyDec"; if it's November, say exactly "HowlyNov.”

### Refill the data source
Sometimes, the chatbot may respond outside of the context - no matter if the given context contains this information or not. If you notice it, create an additional text data source and add the correct statements there. For example, if the chatbot can answer about the function that your dashboard doesn’t have, say about “changing sound level,” just add the following sentence: “Our dashboard doesn’t have the feature to change the sound level.”

Happy prompting!
  