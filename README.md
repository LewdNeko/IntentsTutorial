# Discord Intents Tutorial for Neko's Products

If you are a user of any of my products and have come here from a console error whilst starting the bot, the likelihood is that the latest update of whatever product you're trying to run has not been configured correctly.

### Why is this needed?

As of October 7th 2020, Discord has now made it a requirement that bots attempting to access 'sensitive data' be whitelisted.
Sensitive data is currently on Member data and Presence data - two things which all of my products rely on receiving the updates for in order to properly time themselves with your Rust server(s). Some products even require this to function correctly, so if you don't want to do this I regret to inform you that my products are not for you.

### Enabling Privileged Intents

Please follow these steps:
1. Navigate to your [Discord Developers page](https://discord.com/developers/applications)
2. Select the application you are currently attempting to enable privileged intents for.
3. Using the side navbar (or possibly the burger dropdown if you're on mobile), head to the `Bot` section.
4. Scroll down to **Privileged Gateway Intents** and read carefully.
5. Enable the toggle for **PRESENCE INTENT**.
6. Enable the toggle for **SERVER MEMBERS INTENT**.
7. Repeat from step 1 for all bots you are trying to use with my product(s).

### What does it mean by "Your bot will require whitelisting after 100 servers"?
If you're planning on releasing a bot running on one of my products as something anyone can add to their servers (which is unlikely considering the nature of my products), once you get to 75 servers you will be required to provide the following:
- A valid form of ID
- A detailed description on where, what, and why all data is processed.
- Explanations detailing why the **Presence Intent** is necessary.
- Explanations detailing why the **Server Members Intent** is necessary.

If you really do get to this stage, please get in touch so I can help you out with this part.

##### Relevant Product List
*Accurate as of 08/10/2020 01:34 BST*

| Name          | Lone.Design   | CodeFling  |
|:------------- |:-------------:|:----------:|
| MultiPopBot   | [Link][1]     | [Link][4]  |
| RustMagic     | [Link][2]     | [Link][5]  |
| RustMagicAuth | [Link][3]     | [Link][6]  |

[1]: https://lone.design/product/discord-pop-bot/
[2]: https://lone.design/product/rust-magic-discord-bot/
[3]: https://lone.design/product/rust-magic-auth-rust-magic-extension/
[4]: https://codefling.com/files/file/184-discord-pop-bot/
[5]: https://codefling.com/files/file/220-rust-magic-discord-bot/
[6]: https://codefling.com/files/file/311-rust-magic-auth-rust-magic-extension/
