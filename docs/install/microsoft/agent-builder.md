# Install in Copilot Chat with Agent Builder

[Back to Microsoft Copilot](README.md)

Skills in Agent Builder are in preview. Today they are only open to organisations in Microsoft's Frontier programme. If you do not see **Skills** in step 3, use [Copilot Studio](copilot-studio.md) or [Copilot Cowork](cowork.md) instead.

One agent holds up to eight skills, so all seven fit.

## Build the agent

1. In Copilot Chat, open **Agents & Skills**, then select **New agent**.
2. Name it, for example `Sales Skills`.
3. On the **Configure** tab, open **Skills** and select **Add**.
4. Upload one file from [dist/one-skill/chatgpt-microsoft](../../../dist/one-skill/chatgpt-microsoft). Upload the whole zip. Do not upload the `SKILL.md` file on its own.
5. Repeat for each of the seven skills.
6. Test the agent on the **Try it** tab.
7. Select **Create**.

## Give the agent to your team

1. Open the agent and select **Share**.
2. Select **Copy chat link**.
3. Send the link to your team. They open it and start chatting.

## Good to know

- Each zip can be up to 50 MB, and the agent instructions must stay under 20,000 characters.
- Agent Builder skills are not available in tenants that use Information Barriers.
- This is a preview feature, so menus may change.

## Connect Humantic AI

Follow the Microsoft Copilot steps in [the setup guide](../../setup-humantic.md#microsoft-copilot).
