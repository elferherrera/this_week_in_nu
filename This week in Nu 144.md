# This week in Nushell #144

## Nushell

- EjPlatzer [added search terms for `all?`, `any?`, `length`, and `keybindings`](https://github.com/nushell/nushell/pull/5665)
- merelymyself [added search terms to error make](https://github.com/nushell/nushell/pull/5657), and [Makes a more helpful error for `let` in pipeline](https://github.com/nushell/nushell/pull/5632), and [Allow for test_iteration_errors to work when run as root](https://github.com/nushell/nushell/pull/5609)
- sholderbach [updated reedline: Support more bindings in vi mode](https://github.com/nushell/nushell/pull/5654), and [Improve test coverage of command examples](https://github.com/nushell/nushell/pull/5650), and [Add search terms for `describe`](https://github.com/nushell/nushell/pull/5644), and [Unpin reedline for regular development](https://github.com/nushell/nushell/pull/5634), and [Pin reedline v0.6.0 for the nushell v0.63.0 release](https://github.com/nushell/nushell/pull/5620), and [Add meta command for the config subcommands](https://github.com/nushell/nushell/pull/5616), and [Fallback for `config.buffer_editor` from `EDITOR`](https://github.com/nushell/nushell/pull/5614)
- herlon214 created [nu-cli/completions: add filtering tests for variables completions](https://github.com/nushell/nushell/pull/5653), and [nu-cli/completions: fix filter for variable completions](https://github.com/nushell/nushell/pull/5641)
- tenshik [added search terms to random & typo fix](https://github.com/nushell/nushell/pull/5652)
- rgwood fixed [Don't build OpenSSL on Windows](https://github.com/nushell/nushell/pull/5651), and [Run `cargo update`](https://github.com/nushell/nushell/pull/5639), and [Change `embed-resource` dependency to slimmer `winres`](https://github.com/nushell/nushell/pull/5630)
- kubouch [shortened the links of parser keywords help msgs](https://github.com/nushell/nushell/pull/5648), and [Add 'overlay new' command](https://github.com/nushell/nushell/pull/5647), and [Overlay keep](https://github.com/nushell/nushell/pull/5629)
- fdncred [added case_sensitive_completions config option](https://github.com/nushell/nushell/pull/5646)
- WindSoilder [made cp can copy folders contains dangling symbolic link](https://github.com/nushell/nushell/pull/5645), and [make sure no duplicate column exists during eval and merge](https://github.com/nushell/nushell/pull/5633), and [fix date format](https://github.com/nushell/nushell/pull/5619), and [load config when requried](https://github.com/nushell/nushell/pull/5618), and [Make flatten works better and predictable](https://github.com/nushell/nushell/pull/5611)
- VergeDX [allowed specific table width with `-w`, like command `grid`.](https://github.com/nushell/nushell/pull/5643)
- jt [bumped to dev version](https://github.com/nushell/nushell/pull/5635), and [Bump to 0.63](https://github.com/nushell/nushell/pull/5627)
- hustcer [fixed  typo for `version` command](https://github.com/nushell/nushell/pull/5610)
- Kangaxx-0 [added config command](https://github.com/nushell/nushell/pull/5607)
- toffaletti [added octal binary literals](https://github.com/nushell/nushell/pull/5604)

## Documentation

- kubouch created [Fix config variable name](https://github.com/nushell/nushell.github.io/pull/459), and [Add 'overlay new' tip](https://github.com/nushell/nushell.github.io/pull/457), and [Add overlays chapter](https://github.com/nushell/nushell.github.io/pull/456), and [Create overlays.md stub](https://github.com/nushell/nushell.github.io/pull/447)
- schuelermine created [book/operators.md: add `not` operator](https://github.com/nushell/nushell.github.io/pull/458), and [book/nushell_map_functional.md: add mapM as Haskell equiv. of each](https://github.com/nushell/nushell.github.io/pull/452), and [Fix inverted “shebang” in book/scripts.md](https://github.com/nushell/nushell.github.io/pull/451)
- jgollenz created [Rename 'pivot' to 'transpose' in parsing_git_log.md](https://github.com/nushell/nushell.github.io/pull/455), and [Remove dangling backtick](https://github.com/nushell/nushell.github.io/pull/453)
- sholderbach created [Mention the `nu` flags in the release notes](https://github.com/nushell/nushell.github.io/pull/450), and [Remove outdated reference to `open` pager](https://github.com/nushell/nushell.github.io/pull/446), and [Document the octal binary literals](https://github.com/nushell/nushell.github.io/pull/445)
- hustcer created [refresh docs for nu v0.63](https://github.com/nushell/nushell.github.io/pull/449), and [Update zh-CN home page and keep the Chinese and English docs in sync](https://github.com/nushell/nushell.github.io/pull/443), and [Update some zh-CN translations from commit: 008c89fc26](https://github.com/nushell/nushell.github.io/pull/442)
- jt created [Add 0.63 post](https://github.com/nushell/nushell.github.io/pull/448)
- unional created [docs: add `pwd` to `coming_from_bash.md`](https://github.com/nushell/nushell.github.io/pull/444)
- rgwood created [Update front page](https://github.com/nushell/nushell.github.io/pull/441)
- mdmundo created [Update windows_terminal_default_shell.sh](https://github.com/nushell/nushell.github.io/pull/440)

## Nu_Scripts

- Yethal created [Update make-completions.nu](https://github.com/nushell/nu_scripts/pull/232)
- fdncred created [use default bg color for execution time](https://github.com/nushell/nu_scripts/pull/231)

## reedline

- sholderbach created [Organize the common keybindings](https://github.com/nushell/reedline/pull/433), and [Prepare the v0.6.0 release](https://github.com/nushell/reedline/pull/430), and [Start developer documentation](https://github.com/nushell/reedline/pull/424)
- Artturin created [Move some commonly used keybinds to common keybinds](https://github.com/nushell/reedline/pull/432)
- petrisch created [Typo](https://github.com/nushell/reedline/pull/429)
- ahkrr created [fix: list_menu not accounting for index + indicator](https://github.com/nushell/reedline/pull/428)
- DhruvDh created [Use a default terminal size if reported terminal size is 0, 0](https://github.com/nushell/reedline/pull/402)
