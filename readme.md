# ezSymbols Mac Keyboard Layout

This is a Mac keyboard layout for programmers or anyone that types symbols a lot. It is QWERTY with all symbols and numbers having been switched such that typing numbers requires shifting. A few high-traffic symbols have also traded places with less used symbols for efficiency:

- `_` and `#`
- `{` and `&`
- `}` and `*`

### Unshifted

![unshifted layout](https://github.com/baldwindavid/ezsymbols/blob/master/unshifted-layout.png)

### Shifted

![shifted layout](https://github.com/baldwindavid/ezsymbols/blob/master/shifted-layout.png)

## Installation

- Copy `ezsymbols.bundle` to `~/Library/Keyboard Layouts/`
- Open `System Preferences` > `Keyboard`
- Click on `Input Sources`
- Click `+`
- Select `ezSymbols` under `English`

- Login/logout for it to take (it will mostly work without, but sometimes there is weirdness)

## FAQ

#### Q: How do I use the layout?
A: Use this layout however you like. I like to use the "ezSymbols" solely in my code editor (iTerm) because that is when I'm typing a lot symbols. Elsewhere, I just use the US keyboard. In Keyboard > Input Sources checking the box to "Automatically switch to a document's input source" will automatically switch to the most recently used keyboard layout for a given app. Thus, I don't tend to manually switch the keyboard layout. If you really want to manually switch you can do so via the toolbar menu. In Keyboard > Shortcuts > Input Sources you can also set a keyboard shortcut to toggle between the two most recent layouts or the next one in the list. I set CMD+i to toggle between the two most recent layouts.

#### Q: What if I like the concept, but not this layout?
A: It is quite easy to create your own Mac layouts using [Ukelele](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele)
