### 0.1.0
 - migration of all features from chatbot to merely - music module added.
### 0.2.0
 - improved logging and created the merelybot api at http://yiaysmc.noip.me:8000
#### 0.2.1
 - server owners now have more commands available to them, they recieve instructions when merely is added to their server.
#### 0.2.2
 - help command overhauled
#### 0.2.3
 - merelybot api improved and redundant 'please wait...'-like messages removed. cleaned up references to non-existant commands.
#### 0.2.4
 - music module replaced with JMusicBot. m/thonk added.
 - added interactive server list (m/servers). commands re-arranged to not conflict with JMusicBot.
### 0.3.0
 - migrated to discord.py[rewrite] to take advangage of new features.
 - m/janitor, m/welcome, m/farewell, m/purge and m/clean were broken.
 - musicbot functionality removed after being banned from a bot list for using JMusicBot.
### 0.4.0
 - fixed `m/welcome` and `m/farewell`.
 - fixed a variety of small bugs and removed all references to the long-gone music bot functionality.
 - added more information to `m/stats`.
 - added more thonks to `m/thonk`, including new gif emojis!
 - our moderators have overhauled the meme list.
 - moderators now have the ability to lock out misbehaving users from being able to abuse the bot.
#### 0.4.1
 - `m/meme` doesn't repeat memes as often.
 - added `m/meme repeatstats` and `m/meme count`.
 - merely can now notify server owners whenever an update rolls out.
#### 0.4.2
 - `m/clean, m/purge` have been fixed. however `m/janitor` is still broken.
#### 0.4.3
 - made it possible to opt out of update news if server owners don't want them.
 - fixed a major bug related to `m/echo` that thankfully was never exploited.
 - fixed a major bug related to `m/lockout` that prevented it from working properly.
#### 0.4.4
 - merely's censorship system (for image search) has been even further improved.
 - improved error handling for all commands that have a tendancy to fail when given strange input.
#### 0.4.5
 - improved the relevancy of search results in `m/command`
 - added tonnes of aliases to commands eg. `m/command, m/commands | m/image, m/images | m/stats, m/status` to reduce user error.
 - added `m/vote` - a vote command with progress bars, multiple choice, and custom countdown timers!
#### 0.4.6
 - overhauled statistics collection for compatibility with the [updated website](http://yiaysmc.noip.me)
#### 0.4.7
 - overhauled settings storage and saving, more settings will be persistent between restarts of merely now.
 - added `m/watching, m/streaming, m/listening` on top of `m/playing`.
 - you can now use `m/image more` multiple times or use `m/images` to automatically get 5 images.
 - yiaysmc.noip.me is down.
### 0.5.0
 - censor module overhauled, there may be more false positives now, but in general it's way more effective.
 - `m/image` can finally fetch full-size images from google images.
 - migrated to a faster server. *turns out merely was down because the old server couldn't keep up with all the servers.*
 - yiaysmc.noip.me is still down, no idea why.
 - several commands, like `m/google` no longer work with embeds, no idea why.
 - `m/censor` is a new command for server owners to test for false positives and false negatives in the censor module directly.
#### 0.5.1
 - All embeds should render normally again. 😠
#### 0.5.2
 - `m/stats` and yiaysmc.noip.me are back online.
 - `m/image` now checks to see if google autocorrected your search before showing results.
 - `m/blacklist` now supports adding words that are already covered by the blacklist if they're not identical in order to make it possible to catch more mispellings of words that previously weren't blacklisted directly.
### 0.6.0
 - Fixed an issue that was preventing `m/playing` from persisting after a restart
 - Created a meme database and an [accompanying website](https://meme.yiays.com) for better `m/meme` results.
 - Created a background service that can scan specific channels for memes and allow members to vote which are added to the meme database.
 - Moved merely's documentation website to [merely.yiays.com](https://merely.yiays.com) and updated all links. Old links work for now, but will be removed in the future.