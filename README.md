
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

Also `open()` or `show()` can be used to show the toast:

Example:

``'
<paper-button on-click="openToast">Open Toast</paper-button>
<mha-paper-alert id="toast" text="Hello world!"></mha-paper-alert>
```

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--mha-paper-alert-background-color` | The mha-paper-alert background-color | `#323232` |
| `--mha-paper-alert-color` | The mha-paper-alert color | `#f1f1f1` |

This element applies the mixin `--paper-font-common-base` but does not import `paper-styles/typography.html`.
In order to apply the `Roboto` font to this element, make sure you've imported `paper-styles/typography.html`.


