# Empathetic-Chatbot

## Members
KUBIG 19th Jiwoo Choi, 20th Siho Yoon, Seeun Lee

## Introduction
This project aims to develop a chatbot with human-like empathy.

## Structure

* **Dataset**: AI Hub Empathetic Dialogue Dataset  
  [Link to Dataset](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=71305)

* **Response Generation**: KoGPT2, a GPT-2-based Korean language model, was used for generating responses.
  - Converted the empathetic dialogue dataset into Single-turn and Multi-turn formats.
  - Designed a generation function and post-processing pipeline to produce empathetic responses to user emotions.
  - Takes user input text and generates responses accordingly.

* **Emotion Classification Task**: BERT was used for emotion label classification.
  - Extracted text and emotion labels from the empathetic dialogue dataset and encoded the labels.
  - Defined a function to output the emotion label for a given input sentence.
  - Matched chatbot responses with appropriate emotion labels and emojis.

## Results

* **Evaluation**:
  - The chatbot demonstrated a generally human-level ability to empathize, maintain conversational context, and enhance emotional engagement through emoji usage.
  - It occasionally produced irrelevant responses in complex or unique situations.
  - Responses were sometimes overly positive or lacked practical advice appropriate to the situation.

* **Future Directions**:
  - Leverage LangChain to support more complex dialogue recognition and generation.
  - Strengthen the emotion classification and emoji matching process.
