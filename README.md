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


```
```
> **TIP:** Always make sure to put a `break` after each command
```
```
```js
message.reply
```
Used to reply to the user's message

Example:
```js
case: bruh momento
  message.reply('bruh momento indeed');
  break;
```

Output:

**User**: !bruh momento

**Bot**: @User, bruh momento indeed
```
```
**TIP:** Always make sure to use semicolons!
```
```
