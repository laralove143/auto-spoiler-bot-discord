# auto spoiler

[![add it to your server - invite](https://img.shields.io/badge/add_it_to_your_server-invite-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/api/oauth2/authorize?client_id=955408072199766086&permissions=536880128&scope=applications.commands%20bot)  
[![talk to me - join server](https://img.shields.io/badge/talk_to_me-join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/6vAzfFj8xG)

a discord bot that automatically puts possibly triggering words in spoilers

## features

### auto-spoiler

puts swear words or possibly triggering words in spoilers  
- you can allow swear words or trigger words using `/allow`
- add your own custom words with `/custom_word`
- and even suggest words to be added to the list for everyone

**this is not auto-moderation**, it's simply for people that don't realize what words might be triggering

### other commands

#### `/tw message tw_type`
send a possibly triggering message in spoilers, also telling why it might be triggering

#### `/tag message tag`
end your message with one of the listed tone tags, it also says their meaning in case you forgot

## nerdy stuff

don't forget to change the guild id in [main.rs](src/main.rs) if you want to self-host

made by [laralove143](https://github.com/laralove143) with [rust](https://www.rust-lang.org) using [twilight](https://github.com/twilight-rs/twilight) and [sqlite](https://sqlite.org), licensed MIT
