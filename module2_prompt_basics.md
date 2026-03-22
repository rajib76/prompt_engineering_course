# Module 2: Prompt Engineering Basics

**Time:** ~20–25 minutes | **Prerequisite: Module 1**

---

## 2.1 What Is a Prompt?

A **prompt** is anything you type (or say) to an AI to get a response.

It could be:
- A question: *"What is gravity?"*
- A request: *"Write me a poem about rain."*
- An instruction: *"Summarize this article in 3 bullet points."*
- A conversation starter: *"Let's play a trivia game."*

**Every interaction you have with an AI starts with a prompt.**

---

## 2.2 What Is Prompt Engineering?

**Prompt Engineering** is the practice of designing and refining your prompts to get the best possible output from an AI.

Think of it like **cooking a recipe**:
- The AI is your oven
- Your ingredients are the information you give it
- The **recipe** (your prompt) determines what you get out

The same oven + same ingredients can make a great dish or a terrible one — it depends on the recipe!

---

## 2.3 The Building Blocks of a Good Prompt

Great prompts usually include some (or all) of these ingredients:

### 1. Task
**What do you want the AI to do?**

Examples:
- "Write a short story..."
- "Explain..."
- "Summarize..."
- "Give me 5 ideas for..."
- "Compare and contrast..."

### 2. Context
**What background information does the AI need?**

Examples:
- "...for a 7th grade science class"
- "...I am writing a story set in ancient Egypt"
- "...I have no programming experience"

### 3. Format
**How should the response be structured?**

Examples:
- "...in bullet points"
- "...as a table"
- "...in 3 paragraphs"
- "...as a step-by-step guide"

### 4. Tone / Style
**How should it sound?**

Examples:
- "...in a friendly, conversational tone"
- "...formally, like a report"
- "...simply, as if explaining to a child"
- "...with humor"

### 5. Constraints
**Any limits or specific requirements?**

Examples:
- "...in under 100 words"
- "...without using technical jargon"
- "...only use facts from before 2020"

---

## 2.4 Prompt Quality: Bad vs. Good vs. Great

Let's look at the same request written three different ways:

### Topic: Understanding Climate Change

---

**Bad Prompt:**
> "Climate change"

*What happens:* The AI doesn't know what you want. Should it define it? Give statistics? Write an essay? You might get a generic Wikipedia-style paragraph.

---

**Good Prompt:**
> "Explain climate change to me."

*What happens:* Better! But the AI still makes a lot of guesses — your age, how much detail you want, what format you prefer.

---

**Great Prompt:**
> "Explain climate change to a 7th grader in 3 short paragraphs. Use a simple analogy to explain the greenhouse effect. Avoid technical jargon."

*What happens:* The AI has clear instructions. It knows:
- **Who** it's explaining to (a 7th grader)
- **How long** (3 short paragraphs)
- **How** to explain it (simple analogy)
- **What to avoid** (technical jargon)

---

## 2.5 The CRAFT Framework

Here's a simple framework to remember the key ingredients of a great prompt:

```
C — Context      (Who/what is involved?)
R — Role         (What role should the AI play?)
A — Action       (What do you want it to do?)
F — Format       (How should the output look?)
T — Tone         (What style/voice should it use?)
```

### Example using CRAFT:

| Element | Your Input |
|---------|-----------|
| **C**ontext | "I'm a 9th grader writing a history report on World War II" |
| **R**ole | "Act as a history teacher" |
| **A**ction | "Help me write an introduction paragraph" |
| **F**ormat | "One paragraph, about 5 sentences" |
| **T**one | "Formal but easy to understand" |

**Combined Prompt:**
> "Act as a history teacher. I'm a 9th grader writing a history report on World War II. Help me write a formal but easy-to-understand introduction paragraph for my report. It should be about 5 sentences long."

---

## 2.6 Common Prompt Mistakes (and How to Fix Them)

### Mistake 1: Being Too Vague
| Instead of... | Try... |
|--------------|--------|
| "Tell me about dogs." | "What are the top 5 most popular dog breeds in the US and what makes each one unique?" |
| "Help with my essay." | "Review my essay introduction and suggest 3 ways to make it more engaging." |

### Mistake 2: Asking Multiple Unrelated Things at Once
| Instead of... | Try... |
|--------------|--------|
| "Explain photosynthesis, also write a poem, and what's the capital of France?" | Ask each question separately, one at a time |

### Mistake 3: Forgetting to Specify the Audience
| Instead of... | Try... |
|--------------|--------|
| "Explain quantum physics." | "Explain quantum physics to someone who has never taken a physics class." |

### Mistake 4: Not Specifying Format
| Instead of... | Try... |
|--------------|--------|
| "Give me ideas for a school project." | "Give me 5 ideas for a school science project, listed as bullet points with a one-sentence description for each." |

### Mistake 5: Accepting the First Answer
The AI's first response isn't always the best. You can **refine** your prompt:
- "Make it shorter."
- "Use simpler words."
- "Give me another version with more humor."
- "That's good, but can you add an example?"

---

## 2.7 Iterating: The Art of Refining Your Prompt

Prompt engineering isn't always one-and-done. Great results often come from **iteration** — going back and forth with the AI to improve the output.

### The Iteration Cycle:

```
Write Prompt
     ↓
Read Response
     ↓
Is it what you wanted?
  ↓ Yes          ↓ No
Done!       Refine and try again
```

### Example Iteration:

**Round 1:**
> "Write a poem about summer."

*Response:* Generic poem about sunshine and beaches.

**Round 2:**
> "Write a poem about summer that focuses on the bittersweet feeling of summer ending. Make it 8 lines, rhyming, with a melancholy tone."

*Response:* Much more specific and emotionally resonant!

**Round 3:**
> "I love it! Can you change the last 2 lines to be more hopeful, like summer will come back again?"

*Response:* Perfect — exactly what you wanted!

---

## 2.8 One More Tip: Be Specific About What You DON'T Want

Sometimes telling the AI what to avoid is just as important as telling it what to do:

- "Don't use bullet points — I want full sentences."
- "Don't include any spoilers for the book."
- "Avoid using overly technical medical terms."
- "Don't make it too long — keep it under 150 words."

---

## Key Takeaways

- A **prompt** is your instruction to the AI
- Great prompts include: **Task, Context, Format, Tone, and Constraints**
- Use the **CRAFT framework**: Context, Role, Action, Format, Tone
- Avoid vague prompts, multiple unrelated questions, and forgetting your audience
- **Iteration** (refining your prompts) is normal and often leads to better results
- You can also tell the AI what **NOT** to do

---

## Your Turn!

Rewrite these weak prompts using the CRAFT framework:

1. "Write something about space."
2. "Help me study."
3. "Explain the American Revolution."

For each one, think about: Who is asking? What format? What tone? What constraints?

*Sample answers are in Module 4's exercise section!*

---

## Check Your Understanding

1. What does CRAFT stand for?
2. What is "iteration" in prompt engineering, and why is it useful?
3. What's wrong with the prompt: "Tell me everything about animals"?

---

*Up next: [Module 3 — Prompt Engineering Patterns →](module3_patterns.md)*
