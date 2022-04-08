# This week in Nushell #137

## Nushell

- jt [let 'each' also send input to block](https://github.com/nushell/nushell/pull/5136), and [Soften the block arity checking](https://github.com/nushell/nushell/pull/5135), and [Revert "nu-cli/completions: added a cache layer for fetching completions"](https://github.com/nushell/nushell/pull/5132), and [Move 'keep' to 'take'](https://github.com/nushell/nushell/pull/5123), and [Add datetime to math-like](https://github.com/nushell/nushell/pull/5118), and [Improve describe to be more accurate](https://github.com/nushell/nushell/pull/5116), and [Remove external name exceptions](https://github.com/nushell/nushell/pull/5115), and [Add unary not](https://github.com/nushell/nushell/pull/5111), and [Load plugins for scripts and commands, too](https://github.com/nushell/nushell/pull/5105), and [Add raw strings, use raw strings for env](https://github.com/nushell/nushell/pull/5090)
- stormasm created [doc change from engine-q to nushell](https://github.com/nushell/nushell/pull/5134)
- fdncred [added ability to opt in to normal string replacement in `replace` cmd](https://github.com/nushell/nushell/pull/5133), and [add keep deprecated commands](https://github.com/nushell/nushell/pull/5124), and [update `str find-replace` to `str replace`](https://github.com/nushell/nushell/pull/5120), and [enables find to search records with regex](https://github.com/nushell/nushell/pull/5100), and [new `glob` command](https://github.com/nushell/nushell/pull/5087), and [update shadow-rs, update git2, remove indexmap from `version`](https://github.com/nushell/nushell/pull/5086)
- elferherrera added [short descriptions](https://github.com/nushell/nushell/pull/5130), and [use arc to avoid cloning entire engine for menus](https://github.com/nushell/nushell/pull/5104), and [allow record as text style](https://github.com/nushell/nushell/pull/5092), and [Generic menus](https://github.com/nushell/nushell/pull/5085)
- rgwood [fixed command descriptions+examples](https://github.com/nushell/nushell/pull/5129), and [Change string contains operators to regex](https://github.com/nushell/nushell/pull/5117), and [Trim newline from `input` result](https://github.com/nushell/nushell/pull/5097), and [Add some command search terms](https://github.com/nushell/nushell/pull/5096), and [Fix Format for non-basic data types](https://github.com/nushell/nushell/pull/5095), and [Set LAST_EXIT_CODE on parse error](https://github.com/nushell/nushell/pull/5084), and [Fix Python plugin (missing search terms)](https://github.com/nushell/nushell/pull/5083), and [Fix for search terms in `help --find`](https://github.com/nushell/nushell/pull/5081), and [Tweak append+prepend help](https://github.com/nushell/nushell/pull/5080)
- herlon214 created [nu-cli/completions: removed default filter for command](https://github.com/nushell/nushell/pull/5126), and [nu-cli/completions: fix file completions filtering, clippy fixes](https://github.com/nushell/nushell/pull/5122), and [nu-cli/completions: added a cache layer for fetching completions](https://github.com/nushell/nushell/pull/5114), and [nu-cli/completions: prioritize non hidden folders](https://github.com/nushell/nushell/pull/5108), and [nu-cli: refactor completions](https://github.com/nushell/nushell/pull/5102), and [feature: Add some context to completions](https://github.com/nushell/nushell/pull/5078)
- rybertm [implemented rest of `touch` flags](https://github.com/nushell/nushell/pull/5119)
- kubouch [added env.nu file for environment config](https://github.com/nushell/nushell/pull/5099)
- michel-slm [included license text in all crates](https://github.com/nushell/nushell/pull/5094)
- Hofer-Julian [removed enqine-q from issue template](https://github.com/nushell/nushell/pull/5075)
- EliKor [added quiet and feedback to mv command](https://github.com/nushell/nushell/pull/5073)

## Documentation


- fdncred [tweaked words/type-os](https://github.com/nushell/nushell.github.io/pull/381)
- hustcer [translated working with lists and strings to zh-CN from commit: 13129315c](https://github.com/nushell/nushell.github.io/pull/380), and [Translate types_of_data and loading_data to zh-cn from commit: c13a71d11](https://github.com/nushell/nushell.github.io/pull/378), and [Translate thinking_in_nushell and moving_around to zh-cn ](https://github.com/nushell/nushell.github.io/pull/375), and [Translate installation to zh-cn from commit: c13a71d11](https://github.com/nushell/nushell.github.io/pull/374), and [Translate table of contents and README from commit: c13a71d11](https://github.com/nushell/nushell.github.io/pull/373)
- elferherrera created [Reedline menus](https://github.com/nushell/nushell.github.io/pull/379)
- rgwood [documented regex operator changes](https://github.com/nushell/nushell.github.io/pull/377)
- jt [refreshed commands](https://github.com/nushell/nushell.github.io/pull/376)
- BatmanAoD [indicated that `which` works like Bash's `type`](https://github.com/nushell/nushell.github.io/pull/372)
- AadamZ5 [added record to table example](https://github.com/nushell/nushell.github.io/pull/370)
- chtenb [used tip blocks (Fixes #365)](https://github.com/nushell/nushell.github.io/pull/369), and [Add migration instruction for git bash users](https://github.com/nushell/nushell.github.io/pull/367), and [Update environment.md](https://github.com/nushell/nushell.github.io/pull/366), and [Update line_editor.md](https://github.com/nushell/nushell.github.io/pull/364)
- mvolkmann [added link to an alternate way to enable Starship](https://github.com/nushell/nushell.github.io/pull/368)
- AaronC81 [described interpolated string escape workarounds](https://github.com/nushell/nushell.github.io/pull/345)

## Nu_Scripts

- efx [fixed git gone](https://github.com/nushell/nu_scripts/pull/201)
- fdncred [updated scripts to support `str replace`](https://github.com/nushell/nu_scripts/pull/200)
- Euphrasiologist added [Up function](https://github.com/nushell/nu_scripts/pull/199)

## reedline

- elferherrera added [Short description](https://github.com/nushell/reedline/pull/390), and [short descriptions](https://github.com/nushell/reedline/pull/389), and [generic reedline menus](https://github.com/nushell/reedline/pull/378)
- fdncred [changed up prompt with traditional nushell colors](https://github.com/nushell/reedline/pull/388), and [clean up query output so that it's closer to matching what key bindings want](https://github.com/nushell/reedline/pull/381)
- stormasm [fixed example in readme](https://github.com/nushell/reedline/pull/387)
- sholderbach [Added Ctrl-Delete/Backspace as default keybindings](https://github.com/nushell/reedline/pull/386), and [Escape Ctrl-R history search with `ESC`](https://github.com/nushell/reedline/pull/385), and [[API] Allow the `Completer` impl to be stateful](https://github.com/nushell/reedline/pull/379)

