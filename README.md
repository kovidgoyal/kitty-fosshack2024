# kitty-fosshack2024

Projects for the FOSSHack 2024 hackathon based on the [kitty terminal
emulator](https://github.com/kovidgoyal/kitty). kitty is written primarily in
three languages -- Python, C and Go, so most of these projects require
proficiency in one or more of these languages. Additionally kitty is documented
using reStructuredText so the documentation projects require using that.

If you are interested in hacking on one of these projects, the first step is to get kityt building and running from source on your computer.
Doing that is as simple as running:

```sh
    git clone https://github.com/kovidgoyal/kitty.git && cd kitty
    ./dev.sh build
    kitty/launcher/kitty
```

See [the documentation](https://sw.kovidgoyal.net/kitty/build/) for more details.
