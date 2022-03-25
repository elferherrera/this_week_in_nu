# This week in Nushell #135


## Nushell


- jt [fixed path join on streams](https://github.com/nushell/nushell/pull/4959), and [fixed 4946](https://github.com/nushell/nushell/pull/4951), and [Fix operator precedence parser](https://github.com/nushell/nushell/pull/4947), and [Don't assume external `ls`](https://github.com/nushell/nushell/pull/4925), and [Add licenses](https://github.com/nushell/nushell/pull/4893), and [Bump to 0.60](https://github.com/nushell/nushell/pull/4892), and [Externals shouldn't expand aliases](https://github.com/nushell/nushell/pull/4889), and [Allow 'error make' to make simple errors](https://github.com/nushell/nushell/pull/4881)
- stormasm [bumped cargo crate sys-locale to the latest version](https://github.com/nushell/nushell/pull/4957), and [align all of the serde_json crates to the same version](https://github.com/nushell/nushell/pull/4949), and [bump csv crate to the latest version 1.1.6](https://github.com/nushell/nushell/pull/4939)
- hustcer [fixed #4942, and add a table sorting example for `sort-by` command](https://github.com/nushell/nushell/pull/4948), and [chore: Update default register examples](https://github.com/nushell/nushell/pull/4904)
- bowlofeggs [set the minimum Rust version to 1.59](https://github.com/nushell/nushell/pull/4940)
- uasi [fixed parse_string_strict() to detect unbalanced quotes properly](https://github.com/nushell/nushell/pull/4928)
- jmoore34 created [CantConvert improvements](https://github.com/nushell/nushell/pull/4926)
- fdncred [updated link](https://github.com/nushell/nushell/pull/4915), and [rename export def to export alias](https://github.com/nushell/nushell/pull/4912), and [add ability to execute on demand](https://github.com/nushell/nushell/pull/4896), and [update comments, add other targets](https://github.com/nushell/nushell/pull/4891), and [created an alternate way to determine line count](https://github.com/nushell/nushell/pull/4887), and [update `size` command to be more accurate](https://github.com/nushell/nushell/pull/4885)
- vishalsodani [added missing metadata for drop and uniq #4763](https://github.com/nushell/nushell/pull/4908)
- LebsterFace [passed `/D` flag to `cmd.exe` to disable AutoRun](https://github.com/nushell/nushell/pull/4903)
- unional [fixed typo in default config](https://github.com/nushell/nushell/pull/4882)

## Extension

- fdncred created [update keywords and indentation rules](https://github.com/nushell/vscode-nushell-lang/pull/51)
- jt [added a few more keywords](https://github.com/nushell/vscode-nushell-lang/pull/50)

## Documentation


- hustcer created [Update examples for sort-by, fix some examples](https://github.com/nushell/nushell.github.io/pull/340), and [Fix broken table rendering for epub book, close #199](https://github.com/nushell/nushell.github.io/pull/336), and [Update oh-my-posh setup guide for mac users](https://github.com/nushell/nushell.github.io/pull/334), and [Update plugin register examples and regenerate docs for all commands](https://github.com/nushell/nushell.github.io/pull/331), and [Update make_docs.nu, add directory check](https://github.com/nushell/nushell.github.io/pull/318)
- Coordinate-Cat created [Fix Typo Starship URL](https://github.com/nushell/nushell.github.io/pull/339)
- TyPR124 created [Fix starship config to handle negative exit codes](https://github.com/nushell/nushell.github.io/pull/338)
- jt [added larger starship example](https://github.com/nushell/nushell.github.io/pull/337), and [0.60 blog post](https://github.com/nushell/nushell.github.io/pull/330), and [fix up pipeline chapter](https://github.com/nushell/nushell.github.io/pull/325), and [Add externs and custom completions](https://github.com/nushell/nushell.github.io/pull/323), and [A couple wording fixes in intro](https://github.com/nushell/nushell.github.io/pull/320), and [Add simple error to make_docs.nu](https://github.com/nushell/nushell.github.io/pull/319)
- davidkna created [Starship: add session key instructions & correct typos](https://github.com/nushell/nushell.github.io/pull/335)
- vishalsodani created [Fixed a spelling mistake](https://github.com/nushell/nushell.github.io/pull/333)
- senden9 created [Fix Scoped `cd` example in 0.60 release blog post](https://github.com/nushell/nushell.github.io/pull/332)
- EjPlatzer created [Fix minor typos and clarify `Parsing and evaluation...` section](https://github.com/nushell/nushell.github.io/pull/329)
- rgwood created [Update Plugins page in book](https://github.com/nushell/nushell.github.io/pull/328), and [Mention source + shebangs on Scripts page](https://github.com/nushell/nushell.github.io/pull/327), and [Fix up Parameterizing Scripts](https://github.com/nushell/nushell.github.io/pull/326), and [Sort commands alphabetically](https://github.com/nushell/nushell.github.io/pull/324), and [Clean up commands](https://github.com/nushell/nushell.github.io/pull/309)
- fdncred created [updated default config link](https://github.com/nushell/nushell.github.io/pull/322)

## Nu_Scripts

- skelly37 [ported scripts to 0.60](https://github.com/nushell/nu_scripts/pull/189)
- Inky-developer [added cargo search script](https://github.com/nushell/nu_scripts/pull/188)
- Yethal [added completions for npm](https://github.com/nushell/nu_scripts/pull/187), and [initial make support](https://github.com/nushell/nu_scripts/pull/185)
- jt [updated nu release script](https://github.com/nushell/nu_scripts/pull/186)
- efx created [parse fish command history for git usage](https://github.com/nushell/nu_scripts/pull/184)

## reedline

- jmoore34 [fixed typo [skip ci]](https://github.com/nushell/reedline/pull/355)
- jbr created [end/control-e selects the current completion if there is one](https://github.com/nushell/reedline/pull/354), and [add missing alt-f for parity with the existing alt-b](https://github.com/nushell/reedline/pull/353)
