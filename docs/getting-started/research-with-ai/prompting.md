---
icon: material/numeric-2
---

# Writing Good Prompts 


**The Art of the Prompt: How to Talk to an AI**

We've all been trained by years of using search engines to communicate in short, keyword-driven phrases like "Ford stock price" or "EV market risks." This works for search engines because their job is to *find* and rank existing web pages.

AI assistants, however, work differently. Their job is to *generate* new text based on the instructions you provide. Giving an AI a search-style query is like walking up to a brilliant but very literal assistant and just saying "market risks." You might get an answer, but it won't be tailored, specific, or particularly insightful.

To get a truly valuable response, you need to shift from *searching* to *instructing*. You need to provide the same kind of detail you would give a human collaborator. The good news is that there's a simple, robust framework for doing this.


## The Four Pillars of a Robust Prompt

Think of every great prompt as having four pillars that support it. You might not use every single one every time, but knowing them will help you craft much more effective requests.

1.  **👤 Role:** Tell the AI who to be. Assigning a role is the fastest way to change the tone, style, and perspective of the response.
    * *Example*: "Act as a skeptical investor," or "Explain this to me like I'm a 15-year-old," or "You are a marketing executive..."

2.  **📝 Task:** State precisely what you want the AI to do. Use clear, specific action verbs instead of vague questions.
    * *Example*: Instead of "What about the risks?", try "Summarize the top 3 risks..." or "Compare and contrast the risks mentioned in these two documents..."

3.  **CONTEXT:** Provide the necessary background information. This is where you ground the AI in the same reality you're in, preventing generic answers.
    * *Example*: "...based on the attached 10-K report," or "Given that our primary marketing goal is to reach a new demographic..."

4.  **FORMAT:** Specify exactly how you want the output presented. This saves you time and makes the response immediately useful.
    * *Example*: "...in a bulleted list," or "...as a three-paragraph email draft," or "...in a table with two columns."


## Putting It All Together: A Before-and-After Example

Let's see how this framework transforms a vague query into a powerful instruction.

### The "Search Engine" Prompt (Before)

Imagine you want to understand the challenges Ford is facing. You might type:

> `Ford risks`

**Likely Outcome:** You'll get a generic, Wikipedia-style paragraph listing common business risks like "economic downturns," "competition," and "market shifts." It's true, but it's not insightful or specific to the company's current situation. It's not actionable.

### The "Robust" Prompt (After)

Now, let's build a prompt using the four pillars:

> **[👤 Role]** "Act as a financial analyst for a major investment firm. **[📝 Task]** Your task is to summarize the top 3 strategic risks for your client. **[CONTEXT]** Use only the information found in Ford's most recent annual 10-K report. Focus specifically on risks related to their transition to electric vehicles. **[FORMAT]** Please present your summary as a bulleted list. For each risk, provide a one-sentence explanation of its potential impact on the company's profitability."

**Likely Outcome:** You will receive a targeted, specific, and professionally-toned summary that looks something like this:

* **Supply Chain Disruptions for EV Components:** A failure to secure a stable supply of batteries and semiconductors could delay production targets, directly impacting revenue and market share.
* **Intensifying Competition in the EV Market:** The influx of new and established competitors could lead to price wars and higher marketing costs, potentially squeezing profit margins.
* **Uncertainty in Consumer Adoption Rates:** A slower-than-expected adoption of EVs by the mass market could result in underutilized factory capacity and losses on capital investments.

This second response is infinitely more valuable. It's tailored, contextual, and formatted for immediate use. By taking 30 seconds to design your prompt, you save yourself from wading through generic information and get directly to the insight you need.


## Pro-Tips for Better Prompts

Beyond the four pillars, here are a few extra techniques you can use to level up your AI collaboration.


### 1. Provide an Example of What You Want 🎨

If you need the AI to follow a very specific style or format, the easiest way to get it right is to show it exactly what you mean. This is far more effective than trying to describe the format with words.

* **Instead of describing:** "Please summarize the key points of the article in a very concise, journalistic style."
* **Try showing an example:** "Summarize the key points of the attached article. Follow this example format:
    * **Headline:** A short, catchy title (e.g., 'Ford Pivots to EV Dominance')
    * **Key takeaway:** A single sentence summary (e.g., 'Ford's latest strategy bets heavily on electrifying its most popular truck lines to capture the commercial market.')
    * **Key statistic:** One impactful number (e.g., 'A $30 billion investment in EV and battery development by 2025.')"

By providing a "few-shot" example, you give the model a precise template to follow, resulting in a much more consistent and useful output.


### 2. Ask the AI to "Think Step-by-Step" 👣

For complex questions, especially those involving reasoning, data, or logic, you can get more accurate answers by asking the AI to show its work. Forcing it to slow down and explain its process often prevents it from making a quick, intuitive leap to the wrong conclusion.

* **Standard prompt:** "Based on the attached sales data, what is our fastest-growing customer segment?"
* **A better prompt:** "Based on the attached sales data, **think step-by-step** to determine our fastest-growing customer segment. First, identify all the customer segments. Second, calculate the year-over-year growth rate for each. Finally, state which segment has the highest growth rate and what that rate is."

This "chain-of-thought" approach not only improves the accuracy of the answer but also makes the reasoning transparent, allowing you to easily verify its logic.


### 3. Give the AI Your Documents 📎

The most powerful way to provide context is to give the AI your actual source material. Instead of describing a document, chart, or data table, upload it directly. This grounds the AI's response in your specific reality, eliminating generic answers.

* **Instead of describing:** "My company's latest report shows that sales in the Northeast region have declined while sales in the South have grown. Why might this be?"
* **Try uploading the file:** "Here is our Q3 sales report (sales_report.pdf). Analyze the regional performance data on page 8 and provide three potential hypotheses for the sales decline in the Northeast."

This is the entire principle behind **NotebookLM**. By uploading your documents, you turn the AI into an expert on *your* content.


### 4. Choose the Right Tool for the Job: Speed vs. Power ⚡

Many AI systems offer different models, often a faster, lighter version (like "Flash") and a more powerful, advanced one (like "Pro"). It's helpful to know when to use each.

* **Use the Fast Model (Flash) for:** Quick, simple tasks where speed is important. This includes summarizing a short email, brainstorming a quick list of ideas, or reformatting text. Think of it as a nimble sports car for everyday errands.
* **Use the Powerful Model (Pro) for:** Complex, nuanced tasks that require deep reasoning. This includes analyzing a dense research paper, drafting a detailed strategic plan, or solving a multi-step problem. Think of this as a heavy-duty truck for a major project.

**A good workflow:** Start with the faster model. If the quality of the response isn't good enough or the task is very complex, switch to the more powerful model.