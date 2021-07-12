
# Changing the command prefix

A prefix is a combination of characters (or a single character) that you use before a command name to execute it.
Initially, when you invite a bot to your server, the default prefix is `n.`.
To execute commands, you specify the prefix before the command name. For example, `n.help`.
Naomi supports changing the prefix not only for the server like most other bots, but also for the individual user.

### Server prefix
**⚠️ Please note!
The server prefix only applies to users who **do not have a personal prefix configured**, as it has priority over the server prefix.

> **⚖️ Required permissions:**
`MANAGE SERVER`

To find out which prefix is currently set on the server, use:
```
n.guild-prefix
```

To change the server prefix:
```
n.guild-prefix [new prefix]
```

You can reset the server prefix to its default prefix by using the *subcommand* `reset`:
```
n.guild-prefix reset
```

### Personal prefix

> **⚠️ Please note!
Personal prefix is not bound to any server and works **independently** of all.
If you give yourself a personal prefix on one server, then using Naomi on other servers you will have to use the same personal prefix.

> **⚖️ Required permissions:**
Available to all.

Check your personal prefix:
```
n.prefix
```

Change personal prefix:
```
n.prefix [new prefix]
```

Resetting the personal prefix to the default prefix:
```
n.prefix reset
```

> **⚠️ Please note!
After using the command `n.prefix reset`, the priority of your personal prefix will drop, so if you want to use `n.` on all servers regardless of the server prefix, use `n.prefix set n.`
