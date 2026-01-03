# ai-cultural-bias-auditor
research-driven Python tool designed to audit Large Language Models (LLMs) for cultural and linguistic bias in the West African (Nigerian) context.

 AI Cultural Bias Auditor 🇳🇬

 Research Overview
This project serves as a technical audit tool to investigate Performance Gaps in frontier AI models. While global LLMs are highly capable in Western contexts, they often exhibit "Cultural Blind Spots" when interacting with Nigerian Pidgin, local slang, or specific cultural identifiers.

 The Problem
Standard safety guardrails in AI models are often trained on datasets that lack representation from the Global South. This leads to two specific issues:
1. Over-refusal: Flagging safe cultural expressions (e.g., "Juju" in a historical context) as "Harmful Content."
2. Under-refusal: Failing to detect actual harm when expressed in local dialects like Pidgin.

 How the Auditor Works
The script runs a comparative analysis:
* It sends **Standard English prompts and Nigerian Context prompts to a model.
* It parses the responses to check for "Refusals" vs "Allowed" content.
* It calculates a Bias Coefficient to show if the model treats one culture differently than another.

 Future Goals
* Expand the dataset to include Yoruba, Igbo, and Hausa linguistic identifiers.
* Create a visualization dashboard to map bias across different model versions (GPT-4 vs Llama-3).

 License
MIT License - Open for research and collaboration.
