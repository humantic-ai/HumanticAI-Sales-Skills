# Install in Copilot Studio

[Back to Microsoft Copilot](README.md)

Use this page when you build your own agent in Copilot Studio and want the seven sales skills inside it. Each skill is a file, so the install is an upload.

**Do you use the Humantic AI agent from the Microsoft Marketplace instead?** You cannot add skills to that agent. Go to [the Humantic AI agent page](humantic-marketplace-agent.md). Its second route ends here, on this page.

## Before you start

You need three things.

1. A work account that can sign in to Copilot Studio at copilotstudio.microsoft.com.
2. An agent made with the **Agent** card on the Copilot Studio **Home** page. That card carries a small **GitHub Copilot** tag. Microsoft documents skills only for agents made this way. Agents made under **Other ways to build** are not documented to take skills.
3. The skill files, from the table below.

An agent cannot be switched from one type to the other. If your agent was made under **Other ways to build**, make a new one with the **Agent** card.

## Which file to upload

Copilot Studio takes one skill per upload. It accepts either a `SKILL.md` file or a `.zip` with `SKILL.md` inside. Both of these work. The zips are already built with `SKILL.md` at the top, which is the shape Copilot Studio expects.

| Skill | Zip to upload |
| :--- | :--- |
| buyer-read | [buyer-read.zip](https://github.com/humantic-ai-inc/HumanticAI-Sales-Skills/raw/main/dist/one-skill/chatgpt-microsoft/buyer-read.zip) |
| meeting-prep | [meeting-prep.zip](https://github.com/humantic-ai-inc/HumanticAI-Sales-Skills/raw/main/dist/one-skill/chatgpt-microsoft/meeting-prep.zip) |
| pursuit-plan | [pursuit-plan.zip](https://github.com/humantic-ai-inc/HumanticAI-Sales-Skills/raw/main/dist/one-skill/chatgpt-microsoft/pursuit-plan.zip) |
| prospecting | [prospecting.zip](https://github.com/humantic-ai-inc/HumanticAI-Sales-Skills/raw/main/dist/one-skill/chatgpt-microsoft/prospecting.zip) |
| sales-email | [sales-email.zip](https://github.com/humantic-ai-inc/HumanticAI-Sales-Skills/raw/main/dist/one-skill/chatgpt-microsoft/sales-email.zip) |
| buying-committee | [buying-committee.zip](https://github.com/humantic-ai-inc/HumanticAI-Sales-Skills/raw/main/dist/one-skill/chatgpt-microsoft/buying-committee.zip) |
| expansion-play | [expansion-play.zip](https://github.com/humantic-ai-inc/HumanticAI-Sales-Skills/raw/main/dist/one-skill/chatgpt-microsoft/expansion-play.zip) |

Do not unzip them. Each link downloads the file straight away.

If Copilot Studio rejects a zip, upload the `SKILL.md` file from that skill's folder in [skills](../../../skills) instead. Open it on GitHub and select **Download raw file**.

## Step 1: Open your agent

1. Go to copilotstudio.microsoft.com and sign in.
2. In the left menu, select **Agents**.
3. Open your agent. If you have none yet, go back to **Home** and select the **Agent** card to make one.

## Step 2: Upload each skill

1. On the agent page, look at the panel on the right. It lists **Model**, **Channels**, **Skills**, **Tools**, **Knowledge**, **Connected agents** and **Memory**. If you do not see it, select **Build** at the top of the page.
2. Next to **Skills**, select **+**. The **Add skill** window opens.
3. Stay on the **Upload a skill** tab.
4. Drag a skill file into the box, or select the box and choose the file.
5. Wait for the window to close. The skill now shows as a tag under **Skills**, for example `buyer-read`.
6. Repeat steps 2 to 5 for each of the seven skills.

**What the window checks:** the file must be a `SKILL.md` or a `.zip` that includes `SKILL.md`, and `SKILL.md` must start with a `name` and a `description` written as YAML. All seven skills here already do. If a skill fails the check, Copilot Studio skips it, so look for all seven tags before you move on.

There is also a **Create from blank** tab in the same window. Use it only if you want to write your own skill.

## Step 3: Connect Humantic AI

The skills work without it. They get much sharper with it.

1. Next to **Tools**, select **+**. The **Add a tool** window opens.
2. Add the Humantic AI server as an MCP tool. The window has an **MCP** tab for this.
3. Use the server details and sign-in settings in the Microsoft Copilot steps of [the setup guide](../../setup-humantic.md#microsoft-copilot).

On an agent made this way, you can have both a skill and a tool in the same agent. A skill can tell the agent which tool to use.

## Step 4: Test it

1. In the test chat, type `Prep me for my meeting with [a colleague's LinkedIn URL] tomorrow.`
2. Send it.

**It worked if** you get the outcome the meeting has to produce, a read on the person, questions to ask and the ask. **It did not work if** you get a general answer. Check all seven tags show under **Skills**, then try again.

## Step 5: Publish and share

1. Select **Publish** at the top right.
2. Next to **Channels**, check **Teams + Microsoft 365** is listed. Agents made this way publish to Microsoft Copilot and Teams.
3. Share the agent with your team using the share options on the agent page.

Each person who uses the agent for the first time signs in to Humantic AI once, from a **Connect** card in the chat.

## Update a skill later

1. Download the new zip.
2. Open your agent. Under **Skills**, remove the old tag for that skill with the **x** on it.
3. Next to **Skills**, select **+** and upload the new file, as in Step 2.
4. Select **Publish** again.

## Good to know

- A skill name uses lowercase letters, numbers and hyphens only. It cannot start or end with a hyphen. All seven names follow this.
- A skill description is one line, and the file is plain UTF-8 text.
- Skills on agents made this way are a newer Copilot Studio feature. If a menu does not match this page, tell your Humantic AI contact.
