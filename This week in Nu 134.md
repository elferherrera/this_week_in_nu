# This week in Nushell #134


## Nushell

- jt [added an alias denylist for expansions](https://github.com/nushell/nushell/pull/4871), and [Fix single quote external interpolation](https://github.com/nushell/nushell/pull/4867), and [Add `insert` and `update` back](https://github.com/nushell/nushell/pull/4864), and [Allow expanding aliases before keywords, improve hiding](https://github.com/nushell/nushell/pull/4858), and [Fix string interpolation escaping](https://github.com/nushell/nushell/pull/4854), and [Revert "Alias to keywords (eg `source`)"](https://github.com/nushell/nushell/pull/4841), and [Alias to keywords (eg `source`)](https://github.com/nushell/nushell/pull/4835), and [Nu glob](https://github.com/nushell/nushell/pull/4818)
- fdncred [fixed a couple more tests](https://github.com/nushell/nushell/pull/4870), and [add a display of what the colors look like in `ansi --list`](https://github.com/nushell/nushell/pull/4866), and [some tweaks to main for testing](https://github.com/nushell/nushell/pull/4862), and [rename `update` to `upsert` to mirror what it really does](https://github.com/nushell/nushell/pull/4859), and [added `nu-utils` crate, fixed issue where externals turn off vt processing](https://github.com/nushell/nushell/pull/4857), and [update so that `--log-level` will work properly](https://github.com/nushell/nushell/pull/4856)
- stormasm created [now that docs/commands is gone delete make_docs.nu too](https://github.com/nushell/nushell/pull/4853), and [delete docs/commands now that make_docs.nu is running on website](https://github.com/nushell/nushell/pull/4851)
- sholderbach [detached `nu-ansi-term` crate from main tree, switch to `reedline` from crates.io](https://github.com/nushell/nushell/pull/4850)
- rgwood [changed update help+examples for creating new columns](https://github.com/nushell/nushell/pull/4849)
- chvck [moved repl loop and command/script execution to nu_cli](https://github.com/nushell/nushell/pull/4846)
- hustcer created [feat: fix and update some examples](https://github.com/nushell/nushell/pull/4844)
- elferherrera [removed cmd from edit](https://github.com/nushell/nushell/pull/4840), and [str to datetime dfr](https://github.com/nushell/nushell/pull/4833)
- kubouch [fixed reporting of `which` and `$nu.scope`](https://github.com/nushell/nushell/pull/4836)
- b333z created [Streaming support for lines with raw streams](https://github.com/nushell/nushell/pull/4832)

## Extension


- fdncred [fixed typo](https://github.com/nushell/vscode-nushell-lang/pull/49), and [fixed some bugs](https://github.com/nushell/vscode-nushell-lang/pull/48)

## Documentation

- rgwood [organized book pages by section](https://github.com/nushell/nushell.github.io/pull/302), and [Book: mention `help commands`](https://github.com/nushell/nushell.github.io/pull/300), and [Update insert/update/upsert docs](https://github.com/nushell/nushell.github.io/pull/298), and [Update front page](https://github.com/nushell/nushell.github.io/pull/297), and [Search and package.json cleanup](https://github.com/nushell/nushell.github.io/pull/293), and [Add links to RSS+Atom feeds](https://github.com/nushell/nushell.github.io/pull/292), and [Make command reference more compact](https://github.com/nushell/nushell.github.io/pull/291), and [Add command links to book](https://github.com/nushell/nushell.github.io/pull/285), and [Update env var docs for latest Nu](https://github.com/nushell/nushell.github.io/pull/283), and [Remove link to demo until it's updated](https://github.com/nushell/nushell.github.io/pull/282)
- fdncred created [temporarily remove the contributor book until we can get it updated](https://github.com/nushell/nushell.github.io/pull/301), and [rename update to upsert](https://github.com/nushell/nushell.github.io/pull/296)
- jt created [rounded hero images](https://github.com/nushell/nushell.github.io/pull/299)
- PDQDakota [added Pwsh 7 && and || to operator map page](https://github.com/nushell/nushell.github.io/pull/290)
- stormasm [moved make_docs.nu from nushell to the book](https://github.com/nushell/nushell.github.io/pull/289)
- elferherrera created [Line editor page](https://github.com/nushell/nushell.github.io/pull/287)
- hustcer created [Update docs for commands](https://github.com/nushell/nushell.github.io/pull/286)

## Nu_Scripts

- fdncred [added ability to detect wsl](https://github.com/nushell/nu_scripts/pull/179), and [rename uses of `update` to `upsert`](https://github.com/nushell/nu_scripts/pull/178)
- jt added a [simple website builder script](https://github.com/nushell/nu_scripts/blob/main/fun/website_builder.nu)

## reedline

- sholderbach created [Prepare for new release](https://github.com/nushell/reedline/pull/352), and [Update developer focussed documentation](https://github.com/nushell/reedline/pull/351), and [Road to release: cleanup work](https://github.com/nushell/reedline/pull/345)
