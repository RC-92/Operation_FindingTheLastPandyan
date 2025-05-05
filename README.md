## 1. Purpose

This project enables users to methodically generate prompts using a generative AI model, designed for use with other generative AI models. For a list of supported models, refer to **Applicable Models** below.

---

## 2. Applicable Models

### Version 1

**OpenAI**
- GPT-4  
- GPT-4.5  
- GPT-4o  
- GPT-o1  

**Anthropic Claude**
- Claude Sonnet 3.7  
- Claude Haiku 3.5  

---

# 3. Instructions

## For OpenAI ChatGPT

#### Setup
1. Create an empty project.
2. Title it: `Operation_FindingTheLastPandyans`
3. In the Project's **Instructions** section, paste the contents of `INSTRUCTION.md`.

#### Usage
1. Enter the prompt:  
   `"New Prompt for *XXXYYY*"`  
   Replace `XXXYYY` with the target model (e.g. GPT-4, Claude 3.5, etc.)
2. The model will ask clarifying questions.
3. Respond accordingly.
4. The model will then generate the final prompt.
5. Copy the generated prompt and paste it into a new chat.

---

## For Claude

### Setup
1. Create an empty project.
2. Title it: `Operation_FindingTheLastPandyans`
3. In the **"What are you trying to achieve?"** section, paste the contents of `INSTRUCTION.md`.
### Usage
1. Enter the prompt:  
   `"New Prompt for *XXXYYY*"`  
   Replace `XXXYYY` with the model you plan to use the generated prompt on.
2. Claude will ask you for more context.
3. Provide the information requested.
4. The model will generate a tailored prompt.
5. Copy the prompt and paste it into a new Claude chat.

---
