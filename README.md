## Pulsar Dark UI theme

A dark purple UI theme that adapts to most syntax themes.

![Pulsar Dark UI]

This screenshot uses the File-Icon package. This theme also includes recolors for those icons.

### Credit

This theme is based on the theme created for the screenshots on the Atom IDE product page:
Link to Atom IDE

And is also based on the One Dark UI theme that comes with Atom.
Link to One Dark UI


### Install

Install Instructions


### Settings

In the theme settings you can:

- Change the __Font Size__ to scale the whole UI up or down.
- Choose between 3 __Tab Sizing__ modes.
- Hide the  __dock buttons__.

To make changes, go to `Settings > Themes > Pulsar Dark UI > Settings` or the cog icon next to the theme picker.


### Customize

It's also possible to resize only certain areas by adding the following to your `styles.less` (Use DevTools to find the right selectors):

```css
.theme-one-dark-ui {
  .tab-bar { font-size: 18px; }
  .tree-view { font-size: 14px; }
  .status-bar { font-size: 12px; }
}
```


### FAQ

__Why do the colors change when I switch Syntax themes?__
This UI theme uses the same background color as the chosen syntax theme. If that syntax theme has a light background color, it only uses its hue, but otherwise stays dark. This lets you use dark-light combos.
