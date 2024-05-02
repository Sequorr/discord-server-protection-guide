# Discord Server Protection Guide: Safeguard your Discord Server!

I'm in 200 different Discord servers. Time and time again, I find myself spammed by bots linking to adult-themed servers or NFT content en masse. Most of the time, this is due to settings within the Discord server not being set up correctly. Here's how to fix it, and what to do if you find your own community being spammed!

## I. Disable `@everyone` for the Default Role
This should honestly be a no-brainer, but I always see communities rush into opening their doors without fully checking the permissions that the standard user is given.
<details>
  <summary><h3>Instructions</h3></summary>

  1. Visit the Server Settings.

  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/3ef25df7-195d-4009-8a1e-acb09bb8cc73)
  
  2. Visit the Roles tab.
  
  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/38d39fff-0712-43a7-a56a-3f3e5142d3db)
  
  3. Click on the Default Permissions (`@everyone`) button.
  
  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/a808e05b-e865-43d8-a91c-5756f4b94f7b)
  
  4. Scroll down to the `Mention @everyone, @here, and All Roles` option and ensure it's disabled.
  
  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/8a960b77-c99b-4e34-94f5-d45ca11062cd)
  </details>

## II. Check Your Server's Vanity Roles
It's pretty normal for Discord servers to use non-essential fun/vanity roles. These could be color roles, mentionable game roles, activity-based roles, etc. If it's not related to moderation, consider it to be a vanity role. Whatever the use you may have for them, these roles are almost always the culprit behind bots being able to mention the entire server.

<details>
  <summary><h3>Instructions (The Easy Way)</h3></summary>

  1. Have a trusted user assist you. Grant them all vanity roles.
  
  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/0d1c5a16-f173-4caa-80a2-22498259bfed)
  
  2. Visit the Members section within the Channel List.
  
  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/29e1a19e-bfc0-43bc-848a-c51a35414c93)
  
  3. Find the user in the Members section. Click on the user to open the details panel.
  
  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/1f3dc4cf-21f7-499f-9a08-d2d3c7b474d6)
  
  4. Find the `Mod Permissions` section and click on the `All (#) >` button.
  
  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/a7eeb06a-d9b3-49ab-9892-d8ba327ba6c9)
  
  5. Scroll down to the `Mention @everyone, @here and All Roles` section and see which roles have this permission. You can click on the role to visit its permissions page and remove the permission.
  
  ![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/26cb268a-67cb-4fd5-8759-a1eab2cb5141)

</details>
<details>
  <summary><h3>Instructions (The Hard Way)</h3></summary>

  1. Visit the Server Settings.
  2. Visit the Roles tab.
  3. Go through each role, one by one, checking the permissions to ensure that they can't mention `@everyone`.
</details>

## III. Set up AutoMod
I haven't seen this abuse method myself, but was brought to my attention by another server owner, so I figured I'd include a way to prevent it. Apparently, there are scripts out there set up to mass ping users or roles based on a few factors. The scripts are designed to stay within the text limit, so there's a limit to how many people they can annoy. Nonetheless, this method is easy to curb, thanks to [Discord's AutoMod](https://discord.com/safety/auto-moderation-in-discord) settings.
<details>
  <summary><h3>Instructions</h3></summary>
1. Visit the Server Settings.

![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/3ef25df7-195d-4009-8a1e-acb09bb8cc73)

2. Visit the Safety Setup tab, underneath the Moderation section.

![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/d2ece639-5a50-4cd4-b6c8-8fed9566eaff)

3. Click on the `Edit` button on the AutoMod.

![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/babc91d3-6dd6-492d-b0bf-bae04a2843b7)

4. Enable the `Block Mention Spam` rule and change the `Unique mentions (role + user) per message` option to a low value, such as **4** or **5**. You can define its response values as you wish, but its imperative that you ensure `Block message` is checked. I personally have alerts sent to a custom staff channel so we can be notified of such posts and remove those who try to abuse it.

![image](https://github.com/Sequorr/discord-server-protection-guide/assets/141674738/0aae809c-1f10-46a7-9d25-58342770b6da)

</details>
