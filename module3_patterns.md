# Module 3: Prompt Engineering Patterns

**Time:** ~30–35 minutes | **Prerequisite: Module 2**

---

## What Is a Pattern?

In Module 2, you learned the ingredients of a good prompt. Now let's talk about **techniques** — proven strategies that prompt engineers use to unlock the full power of AI.

Think of these patterns like **moves in a sport**:
- A soccer player learns the basics (kicking, passing)
- Then they learn advanced moves (bicycle kick, free kick technique)
- Each move is a *pattern* — a proven technique for a specific situation

These 6 patterns are your advanced moves!

---

## Pattern 1: Zero-Shot Prompting

### What It Is
Ask the AI to do a task **without giving any examples**. You just describe what you want directly.

The "zero" means zero examples provided.

### When to Use It
- For straightforward tasks the AI clearly understands
- When you want a quick answer
- As a starting point before trying other patterns

### Example

**Prompt:**
> "Translate the following sentence into Spanish: 'The weather is beautiful today.'"

**AI Response:**
> "El clima está hermoso hoy."

---

**Another Example:**

**Prompt:**
> "List 5 fun facts about penguins."

**AI Response:**
> 1. Penguins are birds that cannot fly, but they are excellent swimmers...
> 2. Emperor penguins can hold their breath for up to 20 minutes...
> *(and so on)*

### Key Insight
Zero-shot works great for **clear, common tasks**. If the AI seems confused or gives a wrong answer, try Pattern 2!

---

## Pattern 2: Few-Shot Prompting

### What It Is
You give the AI **a few examples** of what you want before asking it to do the actual task. You're teaching it by example!

The "few" means a few examples provided.

### When to Use It
- When you have a specific style or format you want matched
- When the task is unusual or custom
- When zero-shot doesn't give you what you want

### Example

**Prompt:**
> "I'm going to give you some examples of how I want you to summarize movie plots, then you'll summarize the next one.
>
> Movie: The Lion King
> Summary: A young lion prince flees his kingdom after his evil uncle blames him for his father's death. Years later, he must return to save his pride.
>
> Movie: Finding Nemo
> Summary: A worried clownfish crosses the ocean to rescue his son after he's taken by a scuba diver, making unexpected friends along the way.
>
> Now summarize this movie in the same style:
> Movie: Spider-Man: Into the Spider-Verse"

**AI Response:**
> A teenager discovers he's not the only Spider-Man when a collider accident brings heroes from parallel universes to his world, forcing him to embrace his own powers to save the day.

---

**Another Example: Custom Writing Style**

**Prompt:**
> "I'll show you examples of how I write social media captions, then you'll write one for me.
>
> Photo of my dog: 'This goof stole my sock AGAIN. Can't even be mad. 🐾'
> Photo of my lunch: 'Attempted cooking. Results: suspicious but edible. Send help. 🍳'
>
> Now write a caption in my style for: a photo of me finishing a 5K race."

**AI Response:**
> "Somehow survived 5K with my dignity mostly intact. My legs have filed a formal complaint. 🏃 #NeverAgain #JK #MaybeAgain"

### Key Insight
Few-shot prompting is **incredibly powerful** for matching styles, formats, or patterns you define. You're essentially teaching the AI your preferences through examples.

---

## Pattern 3: Chain-of-Thought Prompting

### What It Is
You ask the AI to **show its reasoning step by step**, like showing its work on a math problem. This helps the AI think more carefully and get better answers.

### When to Use It
- Math problems
- Logic puzzles
- Multi-step reasoning
- Complex decisions
- Any time accuracy really matters

### Example (Without Chain-of-Thought)

**Prompt:**
> "If a train leaves City A at 9:00 AM going 60 mph, and another train leaves City B (300 miles away) at 10:00 AM going 90 mph, when do they meet?"

**AI might just say:** "11:20 AM" (possibly wrong, with no explanation)

---

### Example (With Chain-of-Thought)

**Prompt:**
> "If a train leaves City A at 9:00 AM going 60 mph, and another train leaves City B (300 miles away) at 10:00 AM going 90 mph, when do they meet? Think through this step by step."

**AI Response:**
> Let me work through this step by step.
>
> **Step 1:** By 10:00 AM (when Train B leaves), Train A has been traveling for 1 hour at 60 mph.
> Distance covered by Train A = 60 × 1 = **60 miles**
>
> **Step 2:** Remaining distance between the two trains at 10:00 AM = 300 - 60 = **240 miles**
>
> **Step 3:** Now both trains are moving toward each other.
> Combined speed = 60 + 90 = **150 mph**
>
> **Step 4:** Time to meet = 240 ÷ 150 = **1.6 hours = 1 hour 36 minutes**
>
> **Step 5:** Meeting time = 10:00 AM + 1 hour 36 minutes = **11:36 AM**

### Variations of the Trigger Phrase

You can activate chain-of-thought reasoning with phrases like:
- "Think through this step by step."
- "Show your work."
- "Walk me through your reasoning."
- "Explain your thinking."

### Key Insight
When you ask the AI to reason step-by-step, it performs significantly better on complex problems. It's like asking a student to "show their work" — the process of explaining leads to more careful thinking.

---

## Pattern 4: Role Prompting

### What It Is
You ask the AI to **act as a specific person, character, or expert**. This shapes its personality, vocabulary, and how it approaches your question.

### When to Use It
- When you need expertise in a specific field
- When you want a specific communication style
- When you're learning something and want a patient teacher
- When you're doing creative writing

### Example 1: Expert Role

**Prompt:**
> "You are an experienced marine biologist who loves making science exciting and easy to understand. Explain how dolphins communicate to a group of curious beginners."

**AI Response:**
> "Alright ocean explorers, buckle up because dolphin communication is absolutely mind-blowing! 🐬
>
> Dolphins are basically the chatty teenagers of the ocean. They use three main types of sounds: clicks, whistles, and burst-pulse sounds...
> *(The response continues in an enthusiastic, kid-friendly style)*"

---

### Example 2: Historical Figure

**Prompt:**
> "You are Albert Einstein explaining, in simple terms, what made you come up with the idea of relativity. Speak as if you're talking to a curious person with no science background."

---

### Example 3: Devil's Advocate

**Prompt:**
> "Play devil's advocate. I think social media is mostly harmful for teenagers. Challenge my view with the strongest arguments for why social media can actually be beneficial for teens."

---

### Example 4: Debate Coach

**Prompt:**
> "Act as a debate coach. I'm preparing to argue that zoos should be banned. Give me the 3 strongest arguments for my position, along with likely counterarguments and how to respond to them."

### Key Insight
Roles give the AI a **persona and perspective**. An answer from "a friendly patient teacher" will be very different from an answer from "a Harvard professor" — even for the same question!

---

## Pattern 5: Instruction / Directive Prompting

### What It Is
You give the AI **very specific, structured instructions** — often with numbered steps, rules, or constraints it must follow throughout its response.

### When to Use It
- When format matters a lot
- When you have strict requirements
- When creating templates or structured content
- When you want predictable, consistent output

### Example 1: Structured Output

**Prompt:**
> "Analyze the book 'The Outsiders' by S.E. Hinton using the following structure:
> 1. **Main Theme** (2 sentences)
> 2. **Main Characters** (bullet list with one-sentence descriptions)
> 3. **Key Conflict** (1 paragraph)
> 4. **Why Everyone Should Read It** (3 reasons in bullet points)
> Keep the total response under 300 words."

---

### Example 2: Rule-Based Prompt

**Prompt:**
> "I'm going to describe a problem to you. Follow these rules:
> - Rule 1: First, restate the problem in your own words
> - Rule 2: Ask me 2 clarifying questions before giving a solution
> - Rule 3: Only offer a solution after I answer those questions
>
> My problem: I can't focus when I'm studying at home."

---

### Example 3: Template Creation

**Prompt:**
> "Create a template I can reuse for writing thank-you notes. The template should:
> - Have [PLACEHOLDER] text wherever I need to fill in personal details
> - Be warm but not overly formal
> - Be 3-4 sentences long
> - Work for thanking someone for a gift, help, or advice"

**AI Response:**
> "Dear [NAME],
>
> Thank you so much for [GIFT/HELP/ADVICE] — it truly meant a lot to me. [SPECIFIC DETAIL ABOUT WHY IT WAS MEANINGFUL]. I really appreciate you taking the time to [SPECIFIC ACTION THEY TOOK].
>
> Warmly,
> [YOUR NAME]"

### Key Insight
Instruction prompting gives you **control and consistency**. You're essentially programming the AI's behavior with rules it must follow.

---

## Pattern 6: The Persona + Task Combo (Combining Patterns)

### What It Is
The most powerful prompts often **combine multiple patterns**. This is where prompt engineering becomes truly creative!

### Example: Role + Few-Shot + Chain-of-Thought

**Prompt:**
> "You are a patient and encouraging math tutor working with a complete beginner who struggles with fractions.
>
> Here's how you explain things (examples of your style):
> - You always start with a real-world analogy (like pizza slices)
> - You break every problem into tiny steps
> - You check in after each step with 'Does that make sense so far?'
>
> Now explain, in your teaching style and step-by-step, how to add two fractions with different denominators. Use the problem: 1/3 + 1/4."

*This combines:*
- **Role prompting** (patient math tutor for a complete beginner)
- **Few-shot prompting** (examples of teaching style)
- **Chain-of-thought** (step-by-step explanation)

---

## Pattern Summary Table

| Pattern | What It Does | Best For |
|---------|-------------|----------|
| **Zero-Shot** | Direct ask, no examples | Simple, common tasks |
| **Few-Shot** | Give examples first | Custom styles, unusual formats |
| **Chain-of-Thought** | Ask for step-by-step reasoning | Math, logic, complex problems |
| **Role** | Give AI a persona/identity | Expert knowledge, specific styles |
| **Instruction/Directive** | Give explicit rules to follow | Structured output, consistency |
| **Combo** | Mix multiple patterns | Complex, high-quality needs |

---

## Key Takeaways

- **Zero-Shot:** Just ask directly — great for simple tasks
- **Few-Shot:** Show examples — great for custom styles
- **Chain-of-Thought:** Ask it to "think step by step" — great for hard problems
- **Role Prompting:** Give the AI a persona — great for expertise and style
- **Instruction Prompting:** Give explicit rules — great for structured output
- **Combining patterns** usually gives the best results!

---

## Your Turn!

Match the pattern to the situation:

1. You need help solving a tricky algebra problem
2. You want the AI to write in your personal journaling style (you have old journal entries as examples)
3. You want a quick translation of a phrase
4. You want the AI to act as a career counselor helping you pick a college major
5. You need the AI to always answer in a specific format with headers and bullet points

*(Answers: 1-Chain-of-Thought, 2-Few-Shot, 3-Zero-Shot, 4-Role, 5-Instruction)*

---

## Check Your Understanding

1. What's the difference between zero-shot and few-shot prompting?
2. Why does chain-of-thought prompting help with math problems?
3. How would you combine role prompting and chain-of-thought to get help with a tricky history essay?

---

*Up next: [Module 4 — Hands-On Practice with Claude →](module4_hands_on.md)*
