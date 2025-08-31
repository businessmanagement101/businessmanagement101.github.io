---
icon: material/numeric-1
---

# Working with AI

Throughout this course, you will act as a theorist and business analyst, and just like a professional in the field, you will be empowered by cutting-edge tools to help you do your work more effectively. This lesson introduces you to two powerful AI tools—Gemini and NotebookLM—and teaches you how to use them to elevate the quality of your graded deliverables.

Our goal is not to have AI write your paper for you. Instead, we will treat AI as a research partner—a powerful assistant that can help you find, synthesize, and organize information so that you can focus on the most important part of the assignment: your own critical thinking and unique analysis.

## Learning Objectives

Upon completion of this lesson, you will be able to:

*   Understand the role of AI as a "thinking partner" for learning and analysis.
*   Differentiate between a general-purpose AI assistant (Gemini) and a source-grounded analysis tool (NotebookLM).
*   Construct effective prompts that provide clear context and instructions to AI tools.
*   Critically evaluate AI-generated responses for accuracy, bias, and completeness.
*   Apply best practices for using AI ethically and effectively to deepen your understanding without compromising academic integrity.
*   Use NotebookLM to conduct a source-based analysis of a company.
*   Use Gemini to brainstorm and extend your analysis with creative and strategic thinking.


## The Big Picture
**Why Your Brain is an AI's Best Friend**

To work effectively with AI assistants like Gemini, you first need to understand their fundamental design. At its core, a Large Language Model (LLM), The technology behind AI, is a **next-token prediction engine**.

Think of it like a massive game of "complete the sentence." If I say, "The quick brown fox jumps over the lazy...", your brain instantly predicts the next word is likely "dog." LLMs do the same thing, but on an unimaginable scale. They've been trained on a colossal amount of text from the internet, books, and articles. Based on this data, they calculate the most statistically probable next "token" (a word or piece of a word) to follow any given sequence of text.



This simple-sounding mechanism is incredibly powerful. It's what allows an AI to write an email, summarize a report, or even generate computer code. It is a master of linguistic patterns.

However, this design also has built-in limitations that you **must** understand. Because the AI is just predicting the most *plausible* sequence of words, it has no true understanding, no database of facts, and no inherent sense of truth. This can lead to common problems:

* **Hallucinations**: The AI can generate confident-sounding, plausible, but completely false information because the false words were statistically likely to follow the preceding ones.
* **"Middle-of-the-Road" Responses**: When asked a question, the AI often generates the most common, average, or widely held view from its training data. This can be bland, uninspired, and lack unique insight.
* **Bias Reinforcement**: The model will reflect the biases present in its vast training data, sometimes reinforcing stereotypes or one-sided views without being explicitly asked to.

Your job as a critical thinker is to counteract these tendencies. You are the source of intent, truth-checking, and creativity. Here are four strategies to do just that.

### 1. Be the Pilot, Not the Passenger

The AI's tendency is to follow the most probable path. Your job is to give it a specific, high-quality flight plan to force it off the default route. Actively navigate the conversation with clear and detailed instructions.

* **Instead of this (Passenger)**: "Tell me about Ford's EV strategy." (This invites a generic, predictable summary).
* **Try this (Pilot)**: "Act as a skeptical automotive journalist. Write a three-paragraph analysis of Ford's Q2 2025 earnings call, focusing on how their stated EV production targets conflict with their reported supply chain vulnerabilities. End with a question for the CEO."

This detailed prompt gives the AI a **role** (journalist), a **task** (analysis), **context** (Use Ford's Q2 2025 earnings as the background information for this task), a **constraint** (focus on conflict), and a **format** (three paragraphs with a final question). You are steering it toward insightful output.

### 2. Be a Healthy Skeptic

Never take the AI's first answer at face value. More importantly, use the AI to challenge *your own* thinking. Its ability to instantly adopt a different persona is a powerful tool for spotting weaknesses in your own arguments.

* **Instead of this (Accepting)**: "Okay, that's a good summary of the risks."
* **Try this (Skeptical)**: "Now, act as Ford's Head of Investor Relations. Write a rebuttal to the risks you just outlined. Which of those points is the weakest or most speculative?"

This forces the AI to move beyond the probable first answer and explore the topic from multiple angles. It helps you, the human, develop a more robust and nuanced understanding.

### 3. Experiment and Refine Interactively

Think of your first prompt as a hypothesis. The AI's response is the first set of experimental data. Now, you must refine your experiment to get a better result. Treat the interaction as a dynamic conversation, not a one-shot query.

* **Initial Prompt**: "Brainstorm some marketing slogans for a new Ford electric truck."
* **AI's Generic Response**: "Ford: Powering the Future," "The Electric Workhorse," "Built Ford Tough, Built for Tomorrow."
* **Refining Prompt**: "Those are too generic. Let's try again. The target audience is construction contractors in Texas who are skeptical of EVs. Give me five slogans that directly address their potential concerns about range, toughness, and charging infrastructure."

The second prompt provides crucial context and constraints, leading to a much more targeted and creative output.

### 4. Use AI as Your Personal Tutor 🎓

One of the most powerful uses of an LLM is to make complex information accessible. It can act as a tireless translator or tutor, helping you learn faster and more deeply. This transforms the AI from a tool you wonder about into a partner you learn with.

Let's say you're reading a dense financial document (like a 10-K report) and encounter a difficult concept.

* **Instead of just skipping it, ask the AI**: "This report mentions 'unfunded pension liabilities.' Can you explain what that means in simple terms, using an analogy of a family budget? Why would an investor care about this number?"

This approach allows you to use the AI to build your foundational knowledge. You are not asking it for the answer to an assignment; you are asking it to help you *understand the material* so you can produce a better, more insightful assignment yourself. This is the key to using AI without sacrificing your own learning.


## Meet Your AI Assistants

**The Brainstormer and The Researcher**

Not all AI tools are the same. For this course, we will use two powerful but very different assistants. Knowing which one to use for which task is the key to working effectively. Think of them as two specialists on your team: the creative brainstormer and the meticulous researcher.


### Google Gemini
**Your Creative and Reasoning Partner 🧠**

**Gemini** is your brilliant, world-read collaborator. It has been trained on a vast and diverse dataset of text and code, making it an expert in language, logic, and reasoning. It's the perfect partner for expansive, creative, and exploratory thinking.

Imagine you're sitting down with an expert who has read most of the public internet. They can explain anything from quantum physics to Shakespearean literature, draft a marketing plan, or help you brainstorm ideas for a new product.

**Strengths:**

* **Brainstorming and Ideation**: When you're facing a blank page, Gemini is your best friend. You can ask it to generate ideas, explore different angles, and act as a creative sounding board.
* **Explaining Complex Topics**: It can take a complex idea—like a financial derivative or a piece of legislation—and explain it in simple terms or with an analogy.
* **Drafting and Summarizing (General)**: Gemini can create a first draft of an email, a memo, or an essay on a general topic. It can also summarize broad concepts based on its general knowledge.
* **Strategic Thinking**: You can ask it to "act as a consultant" and propose strategies, analyze hypothetical scenarios, or identify potential market opportunities.

**Key Limitation: It is NOT source-grounded.**
Gemini's knowledge is vast but general. It does **not** know what's in the specific PDF you're reading or the lecture notes on your desk (unless you paste the text directly into your prompt). Because of this, its responses are based on the patterns from its training data, making it susceptible to the hallucinations we discussed earlier. **Always verify its factual claims.**

### Google NotebookLM
**Your Source-Grounded Research Assistant 📚**

**NotebookLM** is your specialist researcher. It's designed to be an expert *only* on the specific documents you provide it. More than just a chatbot, it's a **persistent workspace** designed for projects that span days, weeks, and even months.

Imagine handing a stack of specific reports, articles, and transcripts to a brilliant research assistant and saying, "Read these, and only these. Now, answer my questions based solely on what you've read." That is NotebookLM. It creates a personalized AI model grounded in *your* documents.

**Strengths:**

* **Source-Grounded Answers**: Its most important feature. NotebookLM will only answer questions based on the sources you upload. When it provides an answer, it also provides a citation that takes you to the exact passage in your source document, making verification instant.
* **Summarizing Dense Materials**: You can upload a 100-page annual report and ask NotebookLM to provide a five-bullet-point summary of the key financial results.
* **Finding Connections Across Sources**: It can synthesize information from multiple documents. You can ask, "What are the common themes mentioned in the earnings call transcript and the CEO's interview?".
* **Integrating Your Own Thinking**: NotebookLM allows you to write your own notes or save key AI insights. These notes become part of the source material, turning the AI into a partner that learns from and builds upon your unique ideas.

**Key Limitation: It knows NOTHING beyond your sources.**
NotebookLM's greatest strength is also its limitation. If you haven't uploaded a document about a topic, it can't answer questions about it. This makes it highly accurate and reliable, but also narrowly focused.


### When Should You Use Each?

Here's a simple guide to choosing the right tool for the job:

| Use Gemini when you need to... | Use NotebookLM when you need to... |
| :--- | :--- |
| 🚀 **Go broad** and brainstorm new ideas. | 🎯 **Go deep** into a specific set of documents. |
| 🤔 Understand a **general concept** you're unfamiliar with. | 🔎 Find a **specific fact** within your sources. |
| ✍️ Draft a **first version** of a text from scratch. | 📝 **Summarize** the dense materials you already have. |
| 💡 Think creatively and explore **hypothetical scenarios**. | 🔗 **Synthesize** information across multiple provided reports. |
| 🗣️ Have a **quick, exploratory conversation**. | 🏗️ **Build a long-term project** with sources and your own notes. |

By understanding these distinct roles, you can leverage both the expansive creativity of Gemini and the focused, factual precision of NotebookLM.
