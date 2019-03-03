# M-E-A-N-I-N-G-B-O-T
Accountability bot written in [Echo ARS](http://proxikal.github.io/Echo/Commands/) for Akira The Don's Discord Server.

### Installation
**Step 1:** Invite Echo to your discord channel (linked above)

**Step 2:** [Fork this repo](https://github.com/headjoe3/M-E-A-N-I-N-G-B-O-T/fork) to create your own custom version of this bot.

**Optional:** In Notepad++, you can import `Language.xml` to get syntax highlighting for Echo ARS (Language -> Define your Language... -> Import)

**Step 3:** Edit the `[CONFIG]` block in `meaningbot_release.snippet.ars` ([Release](https://github.com/headjoe3/M-E-A-N-I-N-G-B-O-T/tree/master/Release) folder) to set up channel-specific constants.

`MOD_ROLE` should include a comma-separated list of the names of moderator roles in the channel.

`PATH_CHANNEL_ID` should be the ID of the channel in which bot commands can be used. The `meaningbot_release.snippet.ars` file includes a helper function `.getchannelid` for getting this ID.

Once you have these set up, you can upload `meaningbot_release.snippet.ars` to any text channel as long as you have administrator privileges.

**Step 4:** Customize the messages in each of the other files inside of the [Release](https://github.com/headjoe3/M-E-A-N-I-N-G-B-O-T/tree/master/Release) folder. For emojis, the `meaningbot_release.snippet.ars` file also includes a helper function `.getemojiid`.

**Step 5:** Make sure that the `[CONFIG]` blocks in each file matches your custom messages.

In `meaningbot_release.snippet.ars`, the variables `COMMITMENT_RESPONSE_MESSAGE`, `UPDATE_RESPONSE_MESSAGE`, and `GETSOME_RESPONSE_MESSAGE` should be lists that include ONLY the response messages that you want shown to the user for each action.

**Step 5:** Upload your edited files to any text channel. Use `.commands` to view a list of commands that can be used with this bot.
