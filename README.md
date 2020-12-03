# discord.js guide

## What should I put as the subtitle

```js
message.channel.send();
```

Used to send a message in the channel that the command was sent in

Example:

```js
case 'bruh momento':
  message.channel.send('bruh momento indeed');
  break;
```

Output:

**User**: !bruh momento

**Bot**: bruh momento indeed

---
> **TIP:** Always make sure to put a `break` after each command
---
```js
message.reply
```
Used to reply to the user's message

Example:
```js
case 'bruh momento':
  message.reply('bruh momento indeed');
  break;
```

Output:

**User**: !bruh momento

**Bot**: @User, bruh momento indeed

---

>**TIP:** Always make sure to use semicolons!
---
```js
message.edit();
```
Used to edit a message from the bot

Example:
```js
case 'bruh momento':
  message.channel.send('bruh momento indeed');
  message.edit('I said nothing');
  break;
```
Output:

**User**: !bruh momento

**Bot**: [before edit]: bruh momento indeed [after edit]: I said nothing (edited)

---
> **TIP:** Make sure to always use quotes when typing what you want the bot to say
---
