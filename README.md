# paletteable

Paletteable is a custom CSS file for Mastodon instance administrators to colorize their Mastodon instances, without modifying any of the source. Users can also use this with an extension like [Stylus](https://github.com/openstyles/stylus) to override the theme of any Mastodon instance within their own browser.

The CSS reassigns the colors of various elements of the UI to custom variables (prefixed with `pal`), and includes a couple of sample color palettes to apply to the UI. These should be easy for you to customize to your requirements.

### How to Install

In the Preferences view, go to "Administration", then "Site Settings", then "Appearance." There's a Custom CSS field - drop the CSS into there 😊

### Bear In Mind

* This is tested on a single server running [Glitch](https://glitch-soc.github.io/docs/) (version `v4.1.3` at time of writing). Though it should mostly work with vanilla Mastodon instances or different versions of Mastodon, there are no guarantees.
* This is not *extensively* tested - there are likely to be some UI elements that have been missed. Consider this alpha quality at best.
* The colors are applied the old-fashioned way: each class is written into the CSS. When future updates to Mastodon UI introduce new classes, the CSS will need updating. This will also break down if these classes ever become dynamically generated.
* The admin interface is outside the scope of these changes. Some of the classes are shared between both admin and main, but most are not, so the admin interface will look a little goofy.

Contributions are very welcome, as there is definite room for improvement!