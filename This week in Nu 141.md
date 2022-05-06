# This week in Nushell #141


## Nushell


- WindSoilder [made cd recornize symblic link](https://github.com/nushell/nushell/pull/5454), and [implement seq char command to generate single character sequence](https://github.com/nushell/nushell/pull/5453)
- fdncred [enabled cd to work with directory abbreviations](https://github.com/nushell/nushell/pull/5452), and [fix bug in shell_integration](https://github.com/nushell/nushell/pull/5450), and [add a `to text` command because sometimes you just need text](https://github.com/nushell/nushell/pull/5441), and [a little database cleanup](https://github.com/nushell/nushell/pull/5394)
- merelymyself [Added flags and optional arguments to view-source](https://github.com/nushell/nushell/pull/5446), and [Allowed for view-source to include entire custom command definition](https://github.com/nushell/nushell/pull/5435)
- gipsyh [added split number flag in `split row`](https://github.com/nushell/nushell/pull/5434), and [Fixed ctrl-c in recursion loop bug #5362](https://github.com/nushell/nushell/pull/5409), and [Fixed interrupting a for-loop over a list bug #5378](https://github.com/nushell/nushell/pull/5408), and [Don't resuggest accepted completions](https://github.com/nushell/nushell/pull/5369)
- hustcer [updated rust version](https://github.com/nushell/nushell/pull/5432)
- Caedan [used correct ParseError](https://github.com/nushell/nushell/pull/5431)
- sholderbach [pinned reedline to v0.5.0 for the next release](https://github.com/nushell/nushell/pull/5427), and [Fix CI to run doctests again](https://github.com/nushell/nushell/pull/5410), and [Bump reedline](https://github.com/nushell/nushell/pull/5404)
- elferherrera [added open editor event in config parsing](https://github.com/nushell/nushell/pull/5426), and [Database commands](https://github.com/nushell/nushell/pull/5417), and [Line buffer keybinding](https://github.com/nushell/nushell/pull/5390)
- zhiburt [fixed coloring when string has spaces](https://github.com/nushell/nushell/pull/5425)
- jt [released 0.62](https://github.com/nushell/nushell/pull/5422), and [Update path completions to handle spaces](https://github.com/nushell/nushell/pull/5419), and [Rename =^ to 'starts-with'](https://github.com/nushell/nushell/pull/5407), and [More escaping/unescaping fixes](https://github.com/nushell/nushell/pull/5403), and [Adds error printing back in a couple places](https://github.com/nushell/nushell/pull/5400), and [Add unescaping to external command parsing](https://github.com/nushell/nushell/pull/5399), and [Move uses of trim_quotes to unescape for filenames](https://github.com/nushell/nushell/pull/5398)
- Tropid [fixed erroneous removal of "./" folder prefix](https://github.com/nushell/nushell/pull/5416), and [Update reedline to use partial completion changes](https://github.com/nushell/nushell/pull/5401)
- stormasm [removed ctrl-l from config.nu as a way to clear scrollback](https://github.com/nushell/nushell/pull/5415), and [event ClearScrollback is working in reedline / update config.nu](https://github.com/nushell/nushell/pull/5405)
- rgwood [added job to build plugins](https://github.com/nushell/nushell/pull/5406), and [Add Miette "fancy" feature to fix plugin builds](https://github.com/nushell/nushell/pull/5402), and [CI: build virtualenv tests in dev profile for speed](https://github.com/nushell/nushell/pull/5396), and [Error printing changes for `watch`](https://github.com/nushell/nushell/pull/5389)
- panicbit [added ends-with operator and fix dataframe operator behavior](https://github.com/nushell/nushell/pull/5395)
- kubouch [fixed PATH update example](https://github.com/nushell/nushell/pull/5393)
- andrasio [removed 'empty' block support reminders, for now.](https://github.com/nushell/nushell/pull/5214)

## Documentation

- sholderbach [mentioned default values for command parameters.](https://github.com/nushell/nushell.github.io/pull/434)
- hustcer [refreshed docs for all commands](https://github.com/nushell/nushell.github.io/pull/430), and [Update zh-CN docs](https://github.com/nushell/nushell.github.io/pull/427), and [feat: Add github action related stuff](https://github.com/nushell/nushell.github.io/pull/425)
- rgwood [updated SQLite bits in 0.62 blog post](https://github.com/nushell/nushell.github.io/pull/429)
- jt [added 0.62 release](https://github.com/nushell/nushell.github.io/pull/428)
- reillysiemens [fixed broken nu_scripts repo link](https://github.com/nushell/nushell.github.io/pull/426)

## Nu_Scripts

- fdncred [removed title because it breaks kitty](https://github.com/nushell/nu_scripts/pull/215), and [update get_os_icon for wsl](https://github.com/nushell/nu_scripts/pull/214)

## reedline

- sholderbach created [Change keybinding for external editor](https://github.com/nushell/reedline/pull/422), and [Prepare the 0.5.0 release](https://github.com/nushell/reedline/pull/421), and [Fix README and lib.rs code examples](https://github.com/nushell/reedline/pull/419), and [Add doctests back to the CI](https://github.com/nushell/reedline/pull/418), and [Vi additions and fixes by @zim0369](https://github.com/nushell/reedline/pull/417), and [Attempt fix of `ClearScrollback`](https://github.com/nushell/reedline/pull/416), and [Fix the CI badge](https://github.com/nushell/reedline/pull/415), and [Change the CI to use caching](https://github.com/nushell/reedline/pull/414)
- elferherrera created [Buffer editor keybinding](https://github.com/nushell/reedline/pull/413)
- Tropid created [Only partial complete suggestions when input is a prefix](https://github.com/nushell/reedline/pull/412)
- gipsyh created [Append whitespace after selecting menu](https://github.com/nushell/reedline/pull/410)
