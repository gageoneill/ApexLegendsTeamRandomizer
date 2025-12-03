# Apex Legends Team Randomizer

A simple, single-page web application to randomly generate Apex Legends squads for you and your friends.

## Features
- **Random Selection**: Picks 3 unique legends from the available pool.
- **Smart History**: Remembers recent teams to avoid duplicate picks in back-to-back rounds.
- **Customizable Pool**: Toggle specific legends on or off if you don't own them or don't want to play them.
- **Discord Integration**: Send your generated team directly to a Discord channel via Webhook.

## How to Use
1. Open `apexlegendsteamrandomizer.html` in any modern web browser.
2. (Optional) Uncheck any legends you want to exclude.
3. Click **Generate Team**.
4. Enter player names if desired.

### Discord Setup
To send teams to Discord:
1. In your Discord Server, go to **Server Settings** > **Integrations** > **Webhooks**.
2. Create a New Webhook and copy the **Webhook URL**.
3. In the Team Randomizer app, expand the **Discord Settings** section.
4. Paste your Webhook URL into the input field. It will be saved automatically to your browser.
5. Click **Send to Discord** after generating a team.

## Privacy
Your Webhook URL is stored locally in your browser (`localStorage`). It is never sent to any server other than the Discord API itself.