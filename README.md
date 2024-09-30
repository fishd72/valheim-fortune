# valheim-fortune
Valheim quotes for fortune-mod, works in macOS and Linux

These are the quotes sometimes given when your character goes to sleep during the game.

## Installation

### macOS
For the particular version of fortune-mod I've installed, it required files to be found in `/usr/local/share/games/fortunes/` ... so copy the `valheim` and `valheim.dat` files in there.

If you've installed the Homebrew version of fortune-mod, then you'll likely need to copy them into `/opt/homebrew/usr/local/share/games/fortunes/` ... or perhaps somewhere else under the `/opt/homebrew/usr/` tree... 

### Linux
As per the initial Mac instructions above, copy the `valheim` and `valheim.dat` files to `/usr/local/share/games/fortunes/`

## Usage
In your terminal session (assuming you have an alias configured or `fortune` is in your path) you can type `fortune valheim` to get a random dream-sequence quote.

You can, of couse, add `valheim fortune` to your shells profile configuration to get a random quote on each startup. Please see the documentation for your particular shell for guidance on this.

As a hint, for *bash* users, it will likely go into `~/.bashrc`, for *zsh* users it will likely be `~/.zshrc` but this will depend on your shell and possible platform. Bon chance!

## license, copyright and trademarks

This is free and unencumbered software released into the public
domain. For license information, see "LICENSE".

> [!IMPORTANT]
> The software license does not include the quotes themselves. Valheim
> is a registered trademark of Iron Gate AB. They obviously retain their
> copyright to all quotes in the code, and this project is in no way
> endorsed by, or affiliated with, Iron Gate AB.
