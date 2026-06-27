# Customizing the Skill

The skill works out of the box, but the more you train it on your actual threads, the sharper the output gets. Here's how to make it yours over time.

---

## How to Edit the Skill

1. Open `SKILL.md` in this repo
2. Click the **pencil icon** (top right of the file) to edit
3. Make your changes
4. Click **Commit changes** at the bottom to save

That's it. No code knowledge required.

---

## The Most Powerful Thing You Can Add: Your Own Threads

The skill already has voice guidelines built in. But nothing trains it better than real examples of threads that landed for you.

**How to add them:**

Open `SKILL.md` and find the section that starts with `## Step 3 — Write the Thread`. Just above the style rules, add a section like this:

```
## Examples of Good Threads

Here are threads that worked well. Match this voice and structure:

**Example 1 — [Topic]:**
1/ [your hook tweet]
2/ [next tweet]
[continue...]

**Example 2 — [Topic]:**
1/ [your hook tweet]
2/ [next tweet]
[continue...]
```

Add 2–5 of your best threads. The more specific and varied the examples, the better the skill performs.

---

## Other Things Worth Customizing

**Your handle**
If you want the skill to tag your account in the attribution tweet, find this line in `SKILL.md`:

```
Full breakdown at duethedilly.com
Watch on YouTube: youtube.com/@duedillypod
```

And add your handle:

```
Full breakdown at duethedilly.com
Watch on YouTube: youtube.com/@duedillypod
— @CJoeBlack
```

**Default thread length**
The skill aims for 8–12 tweets by default. If you want shorter or longer, find this line in the style rules:

```
- 2–3 sentences per tweet max
```

And add below it:

```
- Default thread length is [X] tweets unless instructed otherwise
```

**Topics you cover regularly**
If you want the skill to know your beat — music rights, catalog finance, entertainment law — add a short context block near the top of `SKILL.md`:

```
## Context
This skill is used by Carl, an entertainment and music finance lawyer who writes about catalog acquisitions, deal structures, tax law, and the business of music. Threads should reflect that expertise.
```

---

## Updating Your Claude Project or Custom GPT After Changes

Whenever you edit `SKILL.md`, you need to update wherever you installed it.

**Claude Project:**
1. Go to your project → Project Instructions
2. Select all, delete, and paste the updated `SKILL.md` content

**Custom GPT:**
1. Go to your GPT → Edit
2. Replace the Instructions field with the updated `SKILL.md` content
3. Click Save

---

## A Simple Workflow for Getting Better Over Time

1. Run the skill on a piece of content
2. Edit the draft until it's exactly right
3. When a thread performs well on X, add it to the Examples section in `SKILL.md`
4. Update your Claude Project or Custom GPT

The skill gets sharper every time you do this.
