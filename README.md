
<!---

This README is automatically generated from the comments in these files:
mha-paper-alert.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->



## mha-paper-alert


`mha-paper-alert` provides a subtle notification toast. Only one `mha-paper-alert` will
be visible on screen.

Use `opened` to show the toast:

Example:

```
<mha-paper-alert id="alert" opened></mha-paper-alert>
document.querySelector("mha-paper-alert").withText("Hello world").withDuration(1000).open();

```

