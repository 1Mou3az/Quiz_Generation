Model Card:

Base Model: facebook/bart-base / mistralai/Mistral-7B-Instruct-v0.2

Fine-tuned : using PEFT-LoRa

Datasets : mou3az/Question-Answering-Generation-Choices (merged compilation of QuAIL, RACE, and Cosmos QA)

Task: Generating questions from context and answers

Language: English

Performance Metrics on Evaluation Set:

Training Loss: 1.1.1958

Evaluation Loss: 1.109059

Bertscore: 0.8123

Rouge: 0.532144

Fuzzywizzy similarity: 0.74209

###################################################################################

API: 

Url: https://mou3az-mcqa-quiz.hf.space

Set Headers=> key: Content-Type, value: application/json

Set body=> raw: json

{
    "context": " "
}
