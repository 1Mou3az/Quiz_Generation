Model Card:

Base Model: facebook/bart-base

Fine-tuned : using PEFT-LoRa

Datasets : squad_v2, drop, mou3az/IT_QA-QG 

and the second version was traiend on : mou3az/Question-Answering-Generation-Choices (merged compilation of QuAIL, RACE, and Cosmos QA)

Task: Generating questions from context and answers

Language: English

Performance Metrics on Evaluation Set:

Training Loss: 1.1.1958

Evaluation Loss: 1.109059

Bertscore: 0.8123

Rouge: 0.532144

Fuzzywizzy similarity: 0.74209
