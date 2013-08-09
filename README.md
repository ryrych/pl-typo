# Polish Typographic Keyboard Layout
![Polish Typographic Keyboard Layout][1]

I created the layout a few years ago and I still use it with success. For more information you can read [this article](http://web.archive.org/web/20120207122427/http://www.santyago.pl/) (in Polish). The layout itself should be easy to adapt to other languages

## Compatibility
I have used it in various version of Kubuntu and in OpenSuse.

## How to install
Content of `pl_typo_keyboard_layout` copy to `/usr/share/X11/xkb/symbols/pl`  
`cat pl_typo_keyboard_layout | sudo tee -a /usr/share/X11/xkb/symbols/pl`

Copy `evdev*` files to `/usr/share/X11/xkb/rules`  
`sudo cp evdev.* /usr/share/X11/xkb/rules/`

Run in terminal
`setxkbmap -layout pl -variant typographic -v`

In keyboard layout switcher in your system choose the new layout

## Need help?
I provide it as is. Though I'm kind of ‘power user’ I only use Linux to get things done, not to play around it. That’s why
if you need help how to install the layout in the system of your choise, please ask the relevant question on StackOverflow.

## Licence
Truth be told, I don’t card. Let it be *CC BY-SA*, OK? But if you break it, I will not be chasing you or hunting down. Do whatever you want.
Be nice to other people. As I don't drink alcohol, you can send me *good virtual coffee*.

[1]: /img/typolayout_vectorized.png "Polish Typographic Keyboard Layout"

## Typo, Typo, Über Alles!
