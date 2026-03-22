# Module 4: Hands-On Practice with Claude

**Time:** ~45–60 minutes | **Prerequisite: Modules 1–3**

---

## Welcome to the Lab!

You've learned the theory. Now it's time to **actually do it!**

In this module, you'll:
1. Set up your free Claude account
2. Complete guided exercises for each pattern
3. Try a creative challenge project
4. Reflect on what you learned

---

## Step 1: Setting Up Claude (Free Version)

Claude is an AI assistant made by Anthropic. You can use it for free!

### How to Get Started:

1. Open a browser and go to **[claude.ai](https://claude.ai)**
2. Click **"Sign Up"** (it's free — no credit card needed)
3. Sign up with your Google account, Apple ID, or email
4. Verify your email if asked
5. You're in! You'll see a text box where you can type your prompts

> **Note for students under 13:** Ask a parent or guardian to help you set up the account, or use an account they already have.

### What You'll See:
- A large text box at the bottom — this is where you type your prompts
- Your conversation appears above, with your messages and Claude's responses
- You can start a new conversation any time by clicking "New Chat"

---

## Exercise 1: Zero-Shot Prompting (10 minutes)

### Goal: Practice asking direct questions without examples

**Try these prompts one at a time. After each response, think: Did I get what I wanted? If not, how could I improve the prompt?**

---

**Exercise 1a: Basic Zero-Shot**

Type this exactly:
```
What are 5 interesting facts about black holes?
```

*Did you get 5 facts? Were they interesting to you?*

---

**Exercise 1b: Improved Zero-Shot**

Now try this more specific version:
```
What are 5 mind-blowing facts about black holes that would surprise a high school student?
Present them as a numbered list and explain each fact in 1-2 sentences using simple language.
```

*Compare this response to the first one. What's different? Which was more useful?*

---

**Exercise 1c: Your Own Zero-Shot**

Pick a topic you're curious about and write a zero-shot prompt that includes:
- What you want (a list? an explanation? a comparison?)
- Who you are (so Claude can match the level)
- How long or detailed you want it

Write it here before you type it into Claude:
```
My prompt: ___________________________________
```

---

## Exercise 2: Few-Shot Prompting (10 minutes)

### Goal: Use examples to guide Claude's style

---

**Exercise 2a: Style Matching**

Type this prompt:
```
I'll show you examples of how I like study notes to be written, then please create study notes for me in that style.

Example 1:
Topic: Photosynthesis
Notes:
🌿 WHAT IT IS: Plants making food using sunlight
⚡ KEY INGREDIENTS: Sunlight + Water + CO₂
🎯 THE OUTPUT: Glucose (sugar) + Oxygen
💡 FUN FACT: This is why plants are called "producers" in food chains

Example 2:
Topic: The Water Cycle
Notes:
🌿 WHAT IT IS: Water moving continuously through Earth's systems
⚡ KEY INGREDIENTS: Sun's heat + Water + Atmosphere
🎯 THE OUTPUT: Rain, snow, clouds, rivers
💡 FUN FACT: The water you drink today may have been drunk by a dinosaur!

Now create study notes in the same style for: The Human Digestive System
```

*Did Claude match your style? Try asking it to also add an emoji for each section if it didn't!*

---

**Exercise 2b: Write Your Own Few-Shot**

Think of something you've been studying in school (any subject).
1. Write 2 examples of how you want notes to look
2. Ask Claude to create notes on a new topic using your examples

---

## Exercise 3: Chain-of-Thought Prompting (10 minutes)

### Goal: Use step-by-step reasoning to solve problems

---

**Exercise 3a: Math Problem**

First, try WITHOUT chain-of-thought:
```
A store is having a 25% off sale. You have a coupon for an additional 10% off the sale price.
If a jacket originally costs $80, how much do you pay?
```

Then try WITH chain-of-thought:
```
A store is having a 25% off sale. You have a coupon for an additional 10% off the sale price.
If a jacket originally costs $80, how much do you pay?

Think through this step by step, showing each calculation.
```

*Were the answers the same? Was the step-by-step version easier to verify?*

---

**Exercise 3b: Decision Making**

```
I'm trying to decide whether to join the school drama club or the soccer team.
I love performing but I'm also pretty athletic. Drama meets Tuesdays and Thursdays
and has a big spring performance. Soccer has games every Saturday and practices 3 days a week.

Think through the pros and cons step by step, then give me your recommendation.
```

*Notice how asking it to think step-by-step gives you a more thorough analysis!*

---

**Exercise 3c: Your Turn**

Think of a real decision you're trying to make (school choice, which book to read, a project topic). Ask Claude to think through it step by step.

---

## Exercise 4: Role Prompting (10 minutes)

### Goal: Use personas to get expert-level, style-matched answers

---

**Exercise 4a: The Patient Teacher**

```
You are a patient, enthusiastic science teacher who makes everything sound exciting
and uses creative analogies. Your students are 8th graders.

Explain why the sky is blue. Use at least one fun analogy and end with a "mind-blowing
extension question" that students can think about.
```

---

**Exercise 4b: The Career Counselor**

```
You are an experienced career counselor who specializes in helping high school students
explore future careers. You ask thoughtful questions and give honest, practical advice.

I'm a 10th grader who loves art and also loves technology. I'm not sure what careers
combine both. What should I consider?
```

*Ask follow-up questions! Role prompting works great in a conversation.*

---

**Exercise 4c: The Study Buddy**

```
You are my study buddy who is patient, encouraging, and knows everything about history.
You explain things in plain language and use memory tricks (mnemonics) to help me remember.

I need to understand the causes of World War I. Give me a simplified explanation
with a memory trick to remember the main causes.
```

---

**Exercise 4d: Create Your Own Role**

Think of a role that would be helpful to you right now (for a class, a project, a problem you're facing). Design a role prompt and try it out!

Template:
```
You are [describe the role/persona].
Your personality is [describe how they communicate].
Your audience is [describe who you are].

[Your actual question or task]
```

---

## Exercise 5: Instruction / Directive Prompting (10 minutes)

### Goal: Use specific rules to get structured, consistent output

---

**Exercise 5a: Structured Movie Review Helper**

Notice how this prompt has **3 clear layers** — system instruction, format rules, and user input. Try swapping the last line with any movie you like!

```
You are a helpful assistant that writes fun, easy-to-read movie reviews for kids.
Always be enthusiastic and use simple language.

When I give you a movie name, write a review using exactly this structure:

**MOVIE TITLE**
[One sentence with the title and what type of movie it is]

**WHAT IT'S ABOUT**
[2-3 sentences explaining the story — no spoilers!]

**MY FAVORITE PART**
[One sentence]

**WHAT I LEARNED**
[One sentence about the lesson or message of the movie]

**MY RATING**
[X out of 5 stars, and one sentence explaining why]

The movie is: The Lion King
```

*Now try swapping "The Lion King" with your own favorite movie and see what changes!*

---

**Exercise 5b: The Debate Prep Tool**

```
I need to prepare for a debate. Follow these rules exactly:

Rule 1: Give me exactly 3 arguments FOR the position
Rule 2: Give me exactly 3 arguments AGAINST the position
Rule 3: For each argument, provide one piece of evidence or example
Rule 4: End with one sentence telling me which side has stronger arguments and why

Position: "School should start later in the morning for teenagers."
```

---

**Exercise 5c: Design Your Own Template**

Think of something you have to do repeatedly (a type of essay, a type of email, notes for a subject). Create an instruction prompt that produces a reusable template with `[PLACEHOLDERS]`.

---

## Exercise 6: The Grand Challenge — Combine Everything! (15 minutes)

Now put it all together! Your challenge is to use **at least 3 patterns** in a single prompt.

### Challenge Options (pick one):

---

**Challenge A: The Ultimate Study Guide Creator**

Create a prompt that uses:
- **Role** (an expert tutor in the subject)
- **Few-Shot** (show an example of the study guide format you want)
- **Instruction** (give specific rules about length, format, sections)

Topic: Any subject you're currently studying in school

---

**Challenge B: The Story Writing Assistant**

Create a prompt that uses:
- **Role** (a creative writing mentor)
- **Chain-of-Thought** (ask it to plan the story before writing it)
- **Instruction** (specific requirements: word count, elements to include)

Topic: A short story about a student who discovers they have an unexpected talent

---

**Challenge C: The Personalized Explainer**

Create a prompt that:
- Uses **Few-Shot** to show how YOU explain things to yourself (your learning style)
- Uses **Role** (a tutor who matches your style)
- Uses **Chain-of-Thought** (step-by-step explanation)

Topic: Something you've struggled to understand in school

---

## Reflection Questions

After completing the exercises, think about (or write your answers):

1. **Which pattern surprised you the most?** Why?

2. **Which pattern do you think you'll use most often?** For what?

3. **What was the biggest difference between your first prompts and your last prompts today?**

4. **What's one thing you want to try prompting Claude to do this week?**

5. **If a friend asked you "What is prompt engineering?", how would you explain it in 3 sentences?**

---

## Sample Answers for Module 2's "Your Turn" Exercise

Here are strong rewrites of those weak prompts:

**Original:** "Write something about space."
**Improved:** "You are an enthusiastic astronomy teacher. Write a 200-word passage for 8th grade students about the most mind-blowing fact about space. Use at least one analogy to help students relate to the scale of the universe."

**Original:** "Help me study."
**Improved:** "Act as a study skills coach for a 9th grader. I have a history test in 2 days covering the causes and effects of the American Civil War. Give me a step-by-step 2-day study plan with specific activities for each session. Keep each session to 45 minutes."

**Original:** "Explain the American Revolution."
**Improved:** "Act as a storytelling historian. Explain the causes of the American Revolution as if you're telling a dramatic story to a group of curious 7th graders who love action and conflict. Use 3-4 paragraphs, include key figures as 'characters,' and end with a cliffhanger leading up to the Declaration of Independence."

---

## Tips for Continuing to Improve

1. **Keep a "Prompt Journal"** — when you get a great result, save the prompt that worked
2. **Always iterate** — your first prompt is a draft, not the final version
3. **Study great prompts** — search for "prompt engineering examples" to see what others do
4. **Experiment boldly** — there are no wrong answers, only prompts to refine
5. **The more context, the better** — almost always, more specific = better results

---

## You Did It!

Congratulations on completing the course! You now know:

- What Generative AI and Language Models are
- The building blocks of a great prompt (CRAFT framework)
- 5 powerful prompt engineering patterns
- How to combine patterns for the best results
- How to iterate and refine your prompts

These skills will help you use AI tools more effectively in school, creative projects, and beyond. Prompt engineering is one of the most valuable skills you can have in a world where AI is everywhere!

---

## What's Next?

- Try using these techniques in your everyday schoolwork
- Explore other AI tools (Gemini, ChatGPT, Perplexity)
- Look up "advanced prompt engineering" to continue learning
- Share what you've learned with friends and family!

---

*[← Back to Course Overview](README.md)*
