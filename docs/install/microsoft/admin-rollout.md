# Roll the skills out to your organisation

[Back to Microsoft Copilot](README.md)

For Microsoft 365 admins. This puts all seven skills in front of everyone you choose, with nothing for them to install.

## Step 1: Upload the plugin

1. Download [humantic-sales-skills-copilot.zip](https://github.com/humantic-ai-inc/HumanticAI-Sales-Skills/raw/main/dist/humantic-sales-skills-copilot.zip). Do not unzip it.
2. Open the Microsoft 365 admin center at admin.microsoft.com.
3. Go to **Agents**, then **Tools**, then **Registry**.
4. Select **Upload** and choose the file. Review it and select **Next**.
5. Under **Scope users**, choose **All users** or **Specific users or groups**.
6. Select **Install**.

People see it labelled **Managed by your organization**, and it stays installed for them.

## Step 2: Check Cowork is switched on for those people

Cowork is off until an admin turns it on.

1. In the Microsoft 365 admin center, open **Copilot**.
2. Go to **Cost Management**, then **Configuration**.
3. Select **+ Add spending policy**, or open the policy you already have.
4. Include Cowork, and add the same users or groups you chose in Step 1.
5. Save the policy.

## Step 3: Tell people where to find it

1. Send this to the people you chose: "Open Cowork, select **+**, then **Customize**. Your Sales Skills plugin is already in **Plugins**. Start a new session and ask for what you need."

If your admin center looks different from these steps, Microsoft keeps the current screens in its page on managing Cowork plugins. Tell your Humantic AI contact and we will update this page.

## If your team builds agents in Copilot Studio

Skills in Copilot Studio are uploaded to each agent, not rolled out centrally from the admin center. Point your agent builders to [Install in Copilot Studio](copilot-studio.md).

## If you installed the Humantic AI agent from the Marketplace

That agent carries the connection to Humantic AI but not the skills. Roll out the plugin above next to it. See [the Humantic AI agent page](humantic-marketplace-agent.md).

## Connect Humantic AI for everyone

Follow the Microsoft Copilot steps in [the setup guide](../../setup-humantic.md#microsoft-copilot). Your Humantic AI contact also has a full admin guide with screens.
