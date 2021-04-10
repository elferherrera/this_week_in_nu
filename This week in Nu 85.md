# This Week in Nu #85

## VSCode plugin

* fdncred added [autocompletion to the VSCode plugin](https://github.com/nushell/vscode-nushell-lang/pull/30)

## Nu Scripts

* efx and fdncred added [more scripts to the scripts repo](https://github.com/nushell/nu_scripts/pulls?q=is%3Apr+is%3Aclosed)

## Book

* mvolkmann added a [page in the book covering the operators](https://github.com/nushell/nushell.github.io/pull/118)

## Nushell

* ilius added [autocompletions for aliases and custom commands](https://github.com/nushell/nushell/pull/3249), added [TiB and PiB filesizes](https://github.com/nushell/nushell/pull/3257)
* andrasio added the [`any?` and `all?` commands](https://github.com/nushell/nushell/pull/3252), removed the [help shell](https://github.com/nushell/nushell/pull/3258), added [better support for startup commands to the scope](https://github.com/nushell/nushell/pull/3261), started to [simplify runnable contexts](https://github.com/nushell/nushell/pull/3283), moved [config loading to load from memory](https://github.com/nushell/nushell/pull/3287), removed [arg serialiation from `str` subcommands](https://github.com/nushell/nushell/pull/3294)
* mhmdanas removed [the broken `yr` and `mon` duration units](https://github.com/nushell/nushell/pull/3262)
* LhKipp refactored [the config commands](https://github.com/nushell/nushell/pull/3265)
* fdncred bumped [sysinfo](https://github.com/nushell/nushell/pull/3267), updated [the default prompt](https://github.com/nushell/nushell/pull/3291), fixed [ansi rgb fb](https://github.com/nushell/nushell/pull/3293)
* jonathandturner [switched commands to sync iterator style](https://github.com/nushell/nushell/pull/3270), fixed a [busy-wait for externals](https://github.com/nushell/nushell/pull/3280), began [migrating away from arg serialization](https://github.com/nushell/nushell/pull/3281), prevented [loading of config in autoview when not needed](https://github.com/nushell/nushell/pull/3285), simplified the [default features list](https://github.com/nushell/nushell/pull/3288), moved from [representing codeblocks to Arc of Block instead of Block](https://github.com/nushell/nushell/pull/3289), simplified [how `length` calculated the length of a table](https://github.com/nushell/nushell/pull/3292)
* DonnotPanic fixed [a crash with out-of-range timestamps](https://github.com/nushell/nushell/pull/3271)
* ammkrn prevented [using trash-based `rm` if the feature wasn't enabled](https://github.com/nushell/nushell/pull/3278)
* schrieveslaach prevented [whitespace entries from being added to history](https://github.com/nushell/nushell/pull/3286)
