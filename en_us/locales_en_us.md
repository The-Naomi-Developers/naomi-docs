# Localization
Localization was created to solve the problem with the growth of the bot, as our goal is to gain as large an audience as possible, and the support of multiple languages facilitates the use of the project in different regions with different languages.

In the beginning, when you first start using Naomi, the default localization for you is `English (US)`. English is more common than the language Naomi's developers use, Russian, which is why it is the default language.

As in the case of prefixes, localization can be personal as well as server-based.

### Server prefix
> **⚠️ Please note!
The server prefix only applies to users who **do not have personal localization configured**, as it has priority over the server localization.

> **⚖️ Required permissions:**
`MANAGE SERVER`

Check the current server localization:
```
n.guild-locale
```

Change the server localization:
```
n.guild-locale [new localization]
```

Reset the server localization to the original:
```
n.guild-locale reset
```

### Personal localization

> **⚠️ Please note!
Personal localization is not bound to any server and works **independently** of all. If you have set your personal localization on one server, then using Naomi on other servers, Naomi's answers for you will be in the language of your personal localization.

> **⚖️ Required permissions:**
Available to all.

Check your personal localization:
```
n.locale
```

Change your personal locale:
```
n.locale [new localization]
```

Reset the personal locale to the default value:
```
n.locale reset
```

> **⚠️ Please note!
After using the command `n.locale reset`, the priority of your personal localization will drop, so if you want to see responses from the bot in English on all servers regardless of server localization, then use `n.locale set en_us`.
