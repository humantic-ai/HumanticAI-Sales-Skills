# Install the skills

Pick your assistant. Each page has a copy-paste route and step-by-step instructions.

| Assistant | Install guide | All seven in one go? |
| :--- | :--- | :--- |
| **Claude** | [Claude guide](docs/install/claude.md) | Yes. Paste one prompt, or add the repo from the menu |
| **ChatGPT** | [ChatGPT guide](docs/install/chatgpt.md) | Yes, through your workspace admin or the desktop app. One at a time on the web |
| **Microsoft Copilot** | [Microsoft Copilot guides](docs/install/microsoft/README.md) | Yes. One page for each Copilot product: Cowork, Copilot Studio, Agent Builder, one chat, and admin rollout |

**Two separate things, in this order:**

1. **Connect Humantic AI** to your assistant, once. That is [the setup guide](docs/setup-humantic.md).
2. **Install the skills**, using the guide for your assistant.

The skills work without Humantic AI connected. They get much better with it.

Steps checked in October 2026. These assistants change their menus often. If a screen does not match, tell your Humantic AI contact.

---

## Which download to use

| File | Use it for |
| :--- | :--- |
| `dist/humantic-sales-skills-copilot.zip` | Microsoft Copilot Cowork: all seven in one upload |
| `dist/humantic-sales-skills-claude.zip` | Claude, uploaded by an Owner for the whole organisation |
| `dist/humantic-sales-skills-chatgpt.zip` | ChatGPT desktop app: all seven as one plugin |
| `dist/all-skills.zip` | All seven skill folders in one download |
| `dist/one-skill/claude/` | One skill at a time in Claude |
| `dist/one-skill/chatgpt-microsoft/` | One skill at a time in ChatGPT, Copilot Studio, Cowork or Agent Builder |

Everything in `dist/` is built from `skills/` by `scripts/build-packages.py`. See [CONTRIBUTING.md](CONTRIBUTING.md) to change a skill.

---

## Paste into a chat

Good for trying the skills. It lasts for that chat only.

### If your assistant can open links (Claude or ChatGPT)

1. Start a new chat.
2. Turn on web search. In Claude, select **+** at the bottom left of the message box, then switch on **Web search**. In ChatGPT, select **+**, then **Web search**.
3. Copy the block below with the copy button at its top right.
4. Paste it into the chat and send it.
5. The assistant lists the seven skill names. Now ask for what you need.

```text
Load the Humantic AI sales skills and use them for the rest of this
conversation. Read all seven files:

https://raw.githubusercontent.com/humantic-ai-inc/HumanticAI-Sales-Skills/main/skills/buyer-read/SKILL.md
https://raw.githubusercontent.com/humantic-ai-inc/HumanticAI-Sales-Skills/main/skills/meeting-prep/SKILL.md
https://raw.githubusercontent.com/humantic-ai-inc/HumanticAI-Sales-Skills/main/skills/pursuit-plan/SKILL.md
https://raw.githubusercontent.com/humantic-ai-inc/HumanticAI-Sales-Skills/main/skills/prospecting/SKILL.md
https://raw.githubusercontent.com/humantic-ai-inc/HumanticAI-Sales-Skills/main/skills/sales-email/SKILL.md
https://raw.githubusercontent.com/humantic-ai-inc/HumanticAI-Sales-Skills/main/skills/buying-committee/SKILL.md
https://raw.githubusercontent.com/humantic-ai-inc/HumanticAI-Sales-Skills/main/skills/expansion-play/SKILL.md

From now on, when what I ask matches one of them, follow that skill and
tell me in one line which one you used. List the seven names, then ask
me what I am working on.
```

### If it cannot open links (Copilot Chat)

1. Open the skill you want in the [skills](skills) folder, then open its `SKILL.md`.
2. Select the **Copy raw file** button at the top right of the file.
3. Start a new chat in your assistant.
4. Type the two lines in the block below, then paste the skill underneath them.
5. Send it. The assistant confirms in one line. Now ask for what you need.

```text
Below is a skill definition. Follow it for the rest of this conversation.
Reply with one line to confirm, then ask me what you are working on.

[open a skill in the skills folder of this repo, copy all of it,
and paste it here]
```

---

## Check it worked

1. Pick a colleague who is happy to be the test, and copy their LinkedIn URL.
2. Start a new chat in your assistant.
3. Copy the block below, paste it in, and swap in their URL and company.
4. Send it.

```text
Prep me for my meeting with [their LinkedIn URL] at [their company]
tomorrow. The goal is to book a second meeting with their manager.
```

**It worked if** the answer has all of these: the outcome the meeting has to produce and a fallback, a short read on the person, what changed at their company, two to four questions, the objection to expect, and the ask.

**It did not work if** you get a general answer with none of that structure. Go back to the install guide for your assistant and check each step.

---

## Trouble

**The upload is rejected.**

1. Check which folder you downloaded from.
2. For Claude, download again from [dist/one-skill/claude](dist/one-skill/claude).
3. For ChatGPT or Microsoft Copilot, download again from [dist/one-skill/chatgpt-microsoft](dist/one-skill/chatgpt-microsoft).
4. Upload the new file.

**The skill installed but never runs.**

1. Start a new chat.
2. Ask in plain words, for example `prep me for my meeting with Acme tomorrow`.
3. If it still does not run, type `/` in Claude, or `@` in ChatGPT, and pick the skill by name.

**The answers have no Humantic AI research in them.** Connect Humantic AI with [the setup guide](docs/setup-humantic.md).

**A screen does not match these steps.** Tell your Humantic AI contact and we will fix the page.
