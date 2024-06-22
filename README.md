# stolen-vc-css

my quickcss for vencord was so confusing and weird so i have this repo to fix that.
message links / original repo links to each original thing are in their specific files, ty to all of them!

shame on me though :p 

**Important**: The CSS in this repo is not actively maintained (just whenever i stop procrastinating/get bored) and may break with new Discord Updates, I recommend going to the original message urls and getting them from there if it does break.

## Imports
```css
@import url(https://thetahalo.github.io/stolen-vc-css/css/albumoncontrols.css);
@import url(https://thetahalo.github.io/stolen-vc-css/css/betterspotify.css);
/*@import url(https://thetahalo.github.io/stolen-vc-css/css/cherry-titlebar.css);*/
@import url(https://thetahalo.github.io/stolen-vc-css/css/dashless.css);
@import url(https://thetahalo.github.io/stolen-vc-css/css/hover-animation.css);
@import url(https://thetahalo.github.io/stolen-vc-css/css/lineuptxtbox.css);
@import url(https://thetahalo.github.io/stolen-vc-css/css/roundeduserpanel.css);
@import url(https://thetahalo.github.io/stolen-vc-css/css/compressgithubwebhook.css);
/*@import url(https://thetahalo.github.io/stolen-vc-css/css/boticons.css);*/
@import url(https://thetahalo.github.io/stolen-vc-css/css/betterconnectedaccounts.css);
```

### Even QUICKER css!
---
__**Block Certain Built-In Emojis**__

```css
[data-name*="Replace With Emoji Name (Example: pleading_face)"] {
    display: none;
  }
```
  
__**Block certain custom Emojis**__
NOTE: This will block all emojis with that name, there are defo better ways to do this but I'm lazy
```css
  img[aria-label="Replace with Emoji Name (Example: :custom_emoji:)"] {
  display: none;
}
```