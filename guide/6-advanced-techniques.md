# 6. Advanced Prompting Techniques and Refinement

Crafting great prompts is like fine-tuning a conversation with an expert
collaborator. With advanced techniques, you can push GPT beyond basic
responses to produce sharper, more tailored results. This chapter is
about taking what you already know and refining it---adding clarity,
structure, and creativity to every interaction. Think of it as levelling
up your prompting skills to get the most out of GPT, no matter how
complex or specific your needs.

┬á

### 1. Use Tags for Clarity in Series of Prompts

Tags provide structure, especially in multi-step tasks or long
conversations.

**Example:** \"Summarise the main points of this article. Use the tag
\<Summary\> for your response. Then write three recommendations under
the tag \<Recommendations\>.\"

**Expected Output:**

\<Summary\>\
1. Main point one\...\
2. Main point two\...

\<Recommendations\>\
1. Implement strategy X\...\
2. Explore solution Y\...

**Advice:** Use tags in the **Examples** or **Task** section to define
response organisation and layout.┬á

### 2. Break Tasks into Subtasks

Dividing complex tasks into smaller, manageable parts ensures clarity
and structured outputs.

**Example:** \"Step 1: List three benefits of renewable energy. Step 2:
Write a 100-word explanation for each benefit.\"

**Expected Output:**

Step 1:\
1. Sustainability\
2. Cost-effectiveness\
3. Energy security

Step 2:\
Explanation for benefit 1: \...

**Advice:** Include subtasks in the **Task** section to ensure
sequential and focused actions.┬á

### 3. Experiment with Parameters

Adjust GPT's settings to control the tone, creativity, and precision of
outputs.

**Example 1: Creative Writing** \"Generate three creative taglines for a
tech startup using temperature 0.8.\"

**Expected Output:**

-   Innovate Today, Shape Tomorrow

-   Empower Ideas, Elevate Impact

-   Your Vision, Amplified

**Example 2: Factual Accuracy** \"Summarise this article with
temperature 0.2 for focused and precise output.\"

**Advice:** Specify parameters in the **Constraints** section to
fine-tune output style and accuracy.┬á

### 4. Use Reference Text in Prompts

Incorporate external text or documents to enhance context and relevance.

**Example 1: Providing Reference Text** \"Using the following text,
draft a summary suitable for a non-technical audience: \[insert
text\].\"

**Example 2: Asking for Citations** \"Summarise this reference text and
include inline citations for key claims.\"

**Advice:** Use reference texts in the **Context** section to align
GPT\'s outputs with specific sources.┬á

### 5. Use Placeholder Prompts for Robustness

Placeholders like \"If unsure, say \'I don't know\'\" guide GPT to
handle uncertainties gracefully.

**Example**: \"Explain the impact of climate change on agriculture. If
unsure, say \'I don't know\' and suggest areas for further research.\"\
*Expected Output*: Climate change affects agriculture through increased
droughts and flooding. I don't know the exact percentage of crop yield
loss, but further research could clarify this.

**Advice**: Include placeholders in the **Task** section to handle
ambiguities and ensure accuracy.┬á

### 6. Debug Prompts for Vague or Irrelevant Responses

Refine poorly performing prompts by asking GPT to self-analyse.

**Example:** \"Summarise this document. If the response seems vague,
explain why and suggest improvements.\"

**Expected Output:** \"The summary lacks detail because the prompt did
not specify key sections to focus on. Adding constraints like \'focus on
financial data\' could improve it.\"

**Advice:** Include debugging tasks in the **Task** section to guide
iterative refinement.┬á

### 7. Revise Tasks and Constraints

Fine-tune prompts by rephrasing tasks or adding constraints.

**Example:** \"Rewrite this paragraph to improve readability. Limit each
sentence to 15 words and simplify technical terms.\"

**Expected Output:**

Original: The AI model's capacity to handle diverse tasks stems from its
extensive training data.

Revised: The AI model excels at many tasks because it was trained on
diverse data.

**Advice:** Apply constraints in the **Constraints** section to control
tone and format.┬á

### 8. Summarise and Filter Dialogues or Documents

Condense complex or lengthy inputs into clear and concise summaries.

**Example 1: Summarising Dialogues**

\"Summarise the key points of this conversation, focusing on action
items.\"

**Example 2: Filtering Documents**

\"From this long document, extract only the paragraphs that discuss AI
ethics.\"

**Advice:** Use filtering or summarisation in the **Task** section to
focus on essential details.┬á

### 9. Iterate for Continuous Improvement

Build prompts that enable iterative refinement for better results.

**Example:** \"Draft a press release for this product launch. Then
evaluate tone and structure and rewrite based on your feedback.\"

**Expected Output:**

Initial Draft: \"Product X is launching with innovative features to
transform your workflow.\"

Evaluation: \"The tone is engaging, but include specific features to
enhance clarity.\"

Revised Draft: \"Product X launches today, featuring AI-driven
automation and real-time collaboration tools.\"

**Advice:** Iterative prompts are most effective when refinement
instructions are included in the **Examples** or **Constraints**
section.┬á

### 10. Prevent Losing Prompts When Switching Sessions

Drafting a long prompt and switching sessions can result in unsaved
work.

**Why It Happens:** Unsent prompts aren't saved if you navigate away or
refresh.

**How to Avoid It:**

1.  Copy your draft into a note-taking app before switching sessions.

2.  Use a text editor for composing longer prompts, then paste into
    ChatGPT when ready.

**Pro Tip:** Saving drafts not only prevents data loss but also allows
you to refine prompts before submission.┬á

### 11. Advanced Examples for Practice

**Example 1: Debugging a Prompt**

\"Summarise this document. If unclear, identify why and suggest missing
context.\"

**Example 2: Experimenting with Parameters**

\"Write a formal report using temperature 0.3 and a casual version using
temperature 0.7.\"

**Example 3: Iterative Refinement**

\"Draft a social media post. Evaluate its tone, revise it for clarity,
and suggest improvements, and rewrite based on feedback.\"


### Closing Thoughts

Advanced prompting isn't just about tricks or tools---it's about
building a deeper connection with GPT to make it work smarter for you.
Whether you\'re debugging vague responses, experimenting with settings,
or refining tasks step by step, these techniques empower you to get
exactly what you need. Think of every prompt as a conversation: the
clearer and more thoughtful you are, the better the outcome. So keep
experimenting, stay curious, and remember---every interaction is a
chance to learn, refine, and create something amazing.

[Back to the Top](#) | [Back to the ToC](../README.md)