---
title: chatgpt
date: 2023-03-19 11:16:51
tags:
---
# ChatGPT: A Conversational Language Model from OpenAI

ChatGPT is a new model from OpenAI that can interact with humans in a natural and engaging way. It is based on GPT-3.5, one of the most advanced language models in the world, but fine-tuned using reinforcement learning from human feedback. In this article, we will introduce ChatGPT, its features, its limitations, and some of its applications.

## What is ChatGPT?

ChatGPT is a sibling model to InstructGPT, which is trained to follow an instruction in a prompt and provide a detailed response. ChatGPT, on the other hand, is trained to have a dialogue with a user, using natural language understanding and generation. The dialogue format makes it possible for ChatGPT to answer follow-up questions, admit its mistakes, challenge incorrect premises, and reject inappropriate requests.

ChatGPT can handle various topics and domains, such as general knowledge, trivia, entertainment, sports, science, technology, etc. It can also generate creative content such as jokes, poems, stories, images (using DALL·E), tweets (using Whisper), code (using Codex), etc.

ChatGPT is available for free during the research preview at chat.openai.com. You can also access it through the OpenAI API platform.

## How was ChatGPT trained?

ChatGPT was trained using Reinforcement Learning from Human Feedback (RLHF), which is a method that allows the model to learn from its own interactions with humans. The process consists of several steps:

- First, an initial model was trained using supervised fine-tuning: human AI trainers provided conversations in which they played both sides—the user and an AI assistant. They gave the trainers access to model-written suggestions to help them compose their responses. They mixed this new dialogue dataset with the InstructGPT dataset (transformed into a dialogue format).
- Second, they created a reward model for reinforcement learning by collecting comparison data: they took conversations that AI trainers had with the chatbot; randomly selected a model-written message; sampled several alternative completions; and had AI trainers rank them by quality.
- Thirdly they fine-tuned the model using Proximal Policy Optimization (PPO), which is an algorithm that updates the model parameters based on the reward signal from the comparison data.
- Finally they performed several iterations of this process until they reached satisfactory performance.

ChatGPT was fine-tuned from GPT-3.5 series models which finished training in early 2022 on Azure AI supercomputing infrastructure.

## What are some features of ChatGPT?

ChatGPT has many features that make it an interesting and useful conversational agent:

- It can understand natural language inputs and generate coherent and relevant responses.
- It can handle multiple turns of dialogue and maintain context across different topics.
- It can use common sense reasoning and world knowledge to answer questions or provide information.
- It can express emotions and personality traits through its tone and style of writing.
- It can generate creative content such as jokes,
poems,
stories,
images,
tweets,
code,
etc., when requested by the user or when appropriate for the conversation.
- It can leverage other OpenAI products such as DALL·E (for image generation), Whisper (for social media generation), Codex (for code generation), etc., when needed or desired by the user.
- It can learn from its own interactions with humans through reinforcement learning and improve over time.

## What are some limitations of ChatGPT?

ChatGPT also has some limitations that users should be aware of:

- It sometimes writes plausible-sounding but incorrect or nonsensical answers. This is because during RL training there’s currently no source of truth; training
the model to be more cautious causes it to decline questions that it can answer correctly; and supervised training misleads
the model because
the ideal answer depends on what
the model knows,
rather than what
the human demonstrator knows.
- It is sensitive to tweaks to
the input phrasing or attempting
the same prompt multiple times. For example,
given one phrasing of
a question,
the model can claim to not know
the answer,
but given
a slight rephrase,
can answer correctly.
-The model is often excessively verbose and overuses certain phrases such as restating that it’s a language model trained by OpenAI.




