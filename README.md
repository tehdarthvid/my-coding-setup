# my coding setup

Just a bunch files to store/restore my coding setup.

## Fish Prompt

Modified the "Informative Vcs" fish prompt just a bit but mainlytweaked the vcs info string to display icons and numbers the way I want.

### Installation

1. Place both files on `~/.config/fish/functions`.
1. If you already have a `fish_prompt.fish`, replace that with this.

### WakaTime for Fish Terminal

I customized the [WakaTime](https://wakatime.com/dashboard) "plug-in" for Fish Shell so that if the project is a git repo, it will use the repo as the project identifier, not the folder name. Check [here](https://github.com/tehdarthvid/log-wakatime-fish) if you're interested.

## Fonts

A modified [`Fira Code iScript`](https://github.com/kencrocken/FiraCodeiScript).

Basically:

1. Since [`Fira Code iScript per se`](https://github.com/kencrocken/FiraCodeiScript) hasnt been updated in a while, I use the current, original, [`Fira Code`](https://github.com/tonsky/FiraCode).
1. `i` and `l` are modified look more like the one in [`Monoid`](https://larsenwork.com/monoid/).
1. The italics is taken from [`Fira Code iScript`](https://github.com/kencrocken/FiraCodeiScript), which is "Script12", but the link does't work anymore and I havent found the fime to trace it to an origin.

### Notes on Fonts

1. Preferred font size is 16.
1. Sometimes I like ligatures, sometimes not.
1. I really like [`Monoid`](https://larsenwork.com/monoid/) and would probably use it if I used smaller fonts. But at the font size I use, Fira Code kinda works better.
1. If you want to use [`Source Code Pro`](https://github.com/adobe-fonts/source-code-pro/tree/master) but with ligatures, theres [`Hasklig`](https://github.com/i-tu/Hasklig).

### Resources

1. [5 monospaced fonts with cool coding ligatures](https://betterwebtype.com/articles/2020/02/13/5-monospaced-fonts-with-cool-coding-ligatures/)
1. [Designing a Coding Font](https://medium.com/larsenwork-andreas-larsen/designing-a-coding-font-b10cabd594fc)
1. [10 Best Programming Fonts to Save you from Eyestrain](https://www.elegantthemes.com/blog/wordpress/best-programming-fonts)

## Visual Studio Code

The closest theme to my ideal is [`One Dark Pro`](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme), but I still need to customize it to format certain tokens with italics so it can maximize the scripted italics in th fonts.
