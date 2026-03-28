# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Comparison Criteria:

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

- Accuracy

- Coherence

- Simplicity

- Speed

- User experience

## Explanation
1. Zero-Shot Prompt

Definition

A zero-shot prompt is a prompt where the AI is asked to perform a task without being given any examples.
The model relies entirely on its pre-trained knowledge to understand the instruction and produce the output.

In other words:
Prompt → Instruction only → No demonstrations

2. Few-Shot Prompt

Definition

A few-shot prompt is a prompting technique where the AI is given a small number of examples (usually 2–5) before the actual task.
These examples show the pattern of input and expected output, helping the model understand how to perform the task correctly.

In simple terms:
Prompt = Instruction + Several Examples + New Input

3. Chain-of-Thought (CoT) Prompting

Definition

Chain-of-Thought prompting is a technique where the AI is encouraged to reason step-by-step before giving the final answer.
Instead of producing a direct output, the model generates intermediate reasoning steps, which improves performance in complex reasoning tasks.

In simple terms:
Prompt → Step-by-step reasoning → Final answer

4. Role-Based Prompt

Definition

A role-based prompt is a prompting technique where the AI is assigned a specific role, profession, or perspective before answering a question.
The role guides the tone, expertise, and style of the response, making the output more relevant and realistic.

In simple terms:
Prompt = Role + Task + Context

## Prompt Chosen under each category and AI tool used
1. Zero-Shot Prompt
Prompt - “Explain photosynthesis.”
AI tool used - Gemini

2. Few shot prompt
Prompt - "Answer the questions briefly.
Question: What is the capital of France?
Answer: Paris

Question: What is the capital of Japan?
Answer: Tokyo

Question: What is the capital of Australia?
Answer:"
AI tool used - Grok AI 

3. Chain of thought prompt
Prompt - "Ravi has 5 apples. He gives 2 apples to his friend and then buys 4 more apples. 
How many apples does he have now? Let's think step by step."
AI tool used - Perplexity AI

4. Role Based prompt
Prompt - "You are a high school science teacher. 
Explain the concept of gravity to a 10th-grade student."
AI tool used - Deepseek

## Comparison 
AI tool used for comparison - ChatGPT
1. Prompting Technique: Zero-shot prompting
Platform: Google Gemini

Strengths
- High scientific accuracy
- Structured explanation
- Fast response generation

Weakness
- Slightly complex for beginners.


2. Prompting Technique: Few-shot prompting
Platform: Grok AI

Strengths
- High accuracy
- Extremely concise answers
- Clear output format

Limitations
- Works best for pattern-based tasks (classification, translation, Q&A).
- Less useful for complex reasoning tasks.


3. Prompting Technique: Chain-of-Thought Prompting
Platform: Perplexity AI

Strengths
- Clear step-by-step reasoning
- High transparency and interpretability
- Excellent for analytical or multi-step problems

Limitation
- Responses can be longer than necessary for simple tasks.


4. Prompting Technique: Role-Based Prompting
Platform: DeepSeek

Strengths
- Audience-appropriate explanation
- Clear educational style
- High clarity and simplicity

Limitations
- Depth may be limited if the audience level is basic.


| Prompting Technique         | AI Platform   | Accuracy                                       | Coherence                              | Simplicity                                   | Speed                                          | User Experience                                       | Overall Assessment                                            |
| --------------------------- | ------------- | ---------------------------------------------- | -------------------------------------- | -------------------------------------------- | ---------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------- |
| **Zero-Shot Prompt**        | Google Gemini | Very High – accurate scientific explanations   | Excellent structure and logical flow   | Moderate – sometimes uses technical terms    | Very Fast – optimized for quick responses      | Very Good – clear formatting and structured responses | Best for **general explanations and summaries**               |
| **Few-Shot Prompt**         | Grok AI       | Very High – follows example patterns correctly | Excellent pattern consistency          | Excellent – short, direct answers            | Fast – small processing overhead               | Very Good – predictable output format                 | Best for **structured Q&A and classification tasks**          |
| **Chain-of-Thought Prompt** | Perplexity AI | Very High – step-by-step reasoning             | Excellent logical reasoning            | High – easy to follow reasoning steps        | Moderate – reasoning increases response length | Excellent – transparent reasoning and explanations    | Best for **math, logical reasoning, and analytical problems** |
| **Role-Based Prompt**       | DeepSeek      | High – correct conceptual explanation          | Very Good – explanation suited to role | Excellent – simplified language for audience | Fast – minimal processing overhead             | Excellent – engaging educational tone                 | Best for **education and audience-specific explanations**     |






## Result
| Best Category                              | Winning Combination           |
| ------------------------------------------ | ----------------------------- |
| **Best Accuracy + Structured Explanation** | Zero-Shot + Gemini            |
| **Best Reasoning and Problem Solving**     | Chain-of-Thought + Perplexity |
| **Best Simplicity for Students**           | Role-Based + DeepSeek         |
| **Best Pattern-Based Tasks**               | Few-Shot + Grok               |

Overall Best Combination:
Chain-of-Thought Prompt + Perplexity AI because it offers high accuracy, clear reasoning steps, and strong user understanding, especially for analytical tasks.



