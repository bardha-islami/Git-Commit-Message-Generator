# Git Commit Message Generator

### Write clearer commits without starting from scratch

**Audience:** Junior developers  
**Duration:** 3–5 minutes  
**Format:** Visual lesson + instructor narration

---

## What you'll learn

By the end of this lesson, you'll be able to:

- Explain why clear commit messages matter.
- Recognize the basic structure of a conventional commit.
- Use Git Commit Message Generator to create a commit message from your code changes.
- Review and edit an AI-generated message before committing.

---

## Let's start with the problem

![A Git history filled with vague commit messages](./screen1.png)

### Script

"Let's start with a situation you've probably seen before.

You open a Git history and find commits called `fix stuff`, `update`, or just `changes`.

You know something happened, but you don't really know what.

That's a problem because a Git history is more than a record of what happened. It's also a source of context for the people working on the project — including you when you come back to the code months later.

So the goal isn't just to make a commit. **It's to make the commit history useful.**"

---

## What is a commit message?

![A code change becoming a Git commit with a commit message](./screen2.png)

### Script

"Before we look at the tool, let's quickly look at what a commit message actually does.

When you make changes and create a Git commit, Git saves a snapshot of those changes. The commit message gives that snapshot a short description.

Think of it like labeling a box.

If the label says `stuff`, you don't know what's inside. If it says `Kitchen equipment`, you immediately have some useful context.

Commit messages work the same way. You don't need to describe every line of code. You just need to give the change a clear, useful label."

---

## What makes a good commit message?

![The anatomy of a useful conventional commit message](./screen3.png)

### Script

"Here's a simple example:

`fix(auth): validate password before login`

There are three useful pieces here.

`fix` tells us the type of change.

`auth` tells us which part of the application is affected.

And `validate password before login` tells us what changed.

Compare that with something like `fix login`. It's shorter, but it doesn't give us nearly as much context.

A good commit message should be **short enough to scan and specific enough to understand.**"

---

## Meet Git Commit Message Generator

![Git Commit Message Generator web app, VS Code extension, and IntelliJ plugin](./git-commit-msg-generator.png)

### Script

"Now let's say you've finished your changes and you're ready to commit — but you're staring at the commit box wondering how to describe everything you just did.

That's where Git Commit Message Generator can help.

It uses your code changes as context and suggests a clear, conventional commit message.

And you can use it where you already work: through the web app or directly in environments like VS Code and IntelliJ.

The idea isn't to add another step to your workflow. It's to make one of the existing steps — writing the commit message — easier."

---

## Let's generate a message

![Generating a commit message from detected code changes](./screen4.png)

### Script

"Let's see what happens.

Here, the tool has detected changes across the authentication and login code.

Instead of asking us to describe every file manually, it analyzes those changes and generates a suggestion.

The important thing is that we're starting with the actual code changes, not a blank text box.

That gives us a useful first draft that we can evaluate."

---

## Look at the suggestion

![AI-generated commit message with an explanation](./screen5.png)

### Script

"The generator suggests:

`fix(auth): validate password before login`

Notice what makes this useful.

It's not simply saying that a login file changed. It's describing the purpose of the change: we're fixing authentication by validating the password before the user can log in.

The tool also explains the suggestion.

`fix` identifies the type of change, `auth` identifies the affected area, and the description tells us what changed.

For someone learning conventional commits, that explanation is useful because you're not just seeing the answer — you're seeing the reasoning behind the structure."

---

## You're still in control

![Developer reviewing and editing the generated commit message](./screen6.png)

### Script

"Now comes the most important part.

**Don't blindly accept the AI suggestion.**

The generator gives you a starting point, but you make the final decision.

Before committing, ask yourself:

- Does this accurately describe my change?
- Is the scope correct?
- Would another developer understand this message six months from now?

If it's good, keep it.

If it isn't, edit it.

The tool helps with the first draft, but your understanding of the code is what determines whether the final message is correct."

---

## Use it where you code

![Git Commit Message Generator available across different development environments](./screen7.png)

### Script

"Once you know how the workflow works, the nice part is that you don't have to completely change how you develop.

The generator can be used across the environments developers already work in.

Whether you're using the web app, VS Code, or IntelliJ, the basic experience stays the same: look at your changes, generate a suggestion, review it, and decide what you want to commit.

That makes the tool useful as part of your normal development workflow rather than as a separate task."

---

## Put it all together

![The complete commit message workflow](./screen8.png)

### Script

"Let's put the whole process together.

First, **make your code changes.**

Then, **generate a commit message.**

Next, **review the suggestion.**

**Edit it if needed.**

And finally, **commit.**

The goal isn't to automate your judgment. It's to make getting to a clear, conventional commit message faster and easier.

So the next time you're about to commit, don't settle for `fix stuff`.

Give your change a useful label — and let the generator help you get there."

---

## Try it on your next commit

Before your next commit, take a few seconds to look at the message you're about to save.

Ask yourself:

> **"Could another developer understand what changed just by reading this?"**

If the answer is no, improve it.

A useful conventional commit pattern to start with is:

type(scope): description


For example:

fix(auth): validate password before login


If you're not sure how to phrase it, use Git Commit Message Generator to get a starting point.

Then follow the habit:

Generate → Review → Edit if needed → Commit

Key takeaway

A good commit message isn't about writing more.

It's about giving the right amount of context to the person reading your Git history later.

Git Commit Message Generator helps you get to that starting point faster, while you stay responsible for the final message.

Generate the message. Review it. Make it yours. Then commit.

---

Instructional Design Approach

I designed this as a problem-first, demonstration-based lesson so junior developers understand the value of good commit messages before being introduced to the product. The lesson progressively moves from a familiar problem, to the concept of a useful commit message, to seeing the generator in context, and finally to a repeatable workflow learners can apply immediately. I intentionally emphasize review and developer judgment so the AI is presented as an assistant rather than an authority, while the product is promoted naturally by showing how it reduces friction and fits into existing development environments. The visual sequence keeps the lesson concise enough for a 3–5 minute learning experience without turning it into a feature-heavy product tour.
