# This week in Nushell #138


## Nushell


- herlon214 added [Completion for variables of type Record](https://github.com/nushell/nushell/pull/5204), and [nu-cli/completions: add completion for $env.](https://github.com/nushell/nushell/pull/5199)
- fdncred [updated cargo.lock with cargo update](https://github.com/nushell/nushell/pull/5201), and [tweak ci building badge](https://github.com/nushell/nushell/pull/5187), and [allow default color shortcut names](https://github.com/nushell/nushell/pull/5177)
- dantswain [avoided duplicating post headers](https://github.com/nushell/nushell/pull/5200)
- ZetaNumbers [fixed reduce command have not redirected block's evaluation output](https://github.com/nushell/nushell/pull/5193)
- nibon7 [fixed timestamp parsing on 32-bit platforms](https://github.com/nushell/nushell/pull/5192)
- hustcer [fixed completions for `git push` and `git checkout` close: #5021 and #4599](https://github.com/nushell/nushell/pull/5188), and [Add a dockerfile example based on debian bullseye-slim](https://github.com/nushell/nushell/pull/5176)
- stormasm [updated crate chrono-tz to its latest version](https://github.com/nushell/nushell/pull/5184)
- tiffany352 [added `char -i` for chars from integers](https://github.com/nushell/nushell/pull/5183), and [Allow passing an integer to `char -u`](https://github.com/nushell/nushell/pull/5174)
- rgwood added [Initial SQLite functionality](https://github.com/nushell/nushell/pull/5182), and [Update Nu crate descriptions](https://github.com/nushell/nushell/pull/5159)
- strega-nil fixed [don't join paths to cwd ever in calls to external functions](https://github.com/nushell/nushell/pull/5180)
- zkat [documented ShellError errors.](https://github.com/nushell/nushell/pull/5172), and [bump miette to 4.4.0](https://github.com/nushell/nushell/pull/5167)
- sholderbach added [[no ci] Fix typo in link](https://github.com/nushell/nushell/pull/5168), and [Pin reedline version for 0.61 release](https://github.com/nushell/nushell/pull/5164), and [Clean REPL code, hide Hints without ANSI coloring](https://github.com/nushell/nushell/pull/5157), and [Support unbinding a particular key event](https://github.com/nushell/nushell/pull/5152), and [Allow overriding of menu keybindings](https://github.com/nushell/nushell/pull/5148)
- jt released [Bump 0.61](https://github.com/nushell/nushell/pull/5166), and [Remove the im crate dependency](https://github.com/nushell/nushell/pull/5161), and [Allows aliases in use lists](https://github.com/nushell/nushell/pull/5150)
- strega-nil-ms [fixed #5131](https://github.com/nushell/nushell/pull/5153)
- merkrafter added [Support binary literals with binary format](https://github.com/nushell/nushell/pull/5149)
- boyvanduuren [fixed failing unit tests on Windows (#5142)](https://github.com/nushell/nushell/pull/5143)


## Documentation


- hustcer [fixed some typo and Translate configuration & environment to zh-CN from commit: f5987a82d](https://github.com/nushell/nushell.github.io/pull/400), and [Translate lots of small docs  to zh-CN from commit: ae23eeba3](https://github.com/nushell/nushell.github.io/pull/396), and [Translate scripts and modules to zh-CN from commit: 115b193d2](https://github.com/nushell/nushell.github.io/pull/392), and [Translate operators and variables_and_subexpressions to zh-CN](https://github.com/nushell/nushell.github.io/pull/391), and [update i18n related script and meta data](https://github.com/nushell/nushell.github.io/pull/386)
- Cyborus04 [fixed command-less `cd` example](https://github.com/nushell/nushell.github.io/pull/399)
- Szune added [Typo fix in 2022-04-12-nushell_0_61.md](https://github.com/nushell/nushell.github.io/pull/398)
- fennewald [updated coming_from_bash.md](https://github.com/nushell/nushell.github.io/pull/397)
- fdncred [removed old_book](https://github.com/nushell/nushell.github.io/pull/395)
- jt [added blog for 0.61 release](https://github.com/nushell/nushell.github.io/pull/394)
- kubouch [added env.nu to Configuration](https://github.com/nushell/nushell.github.io/pull/393)
- merkrafter added [nushell#4924 Update data types with binary literal syntax](https://github.com/nushell/nushell.github.io/pull/390)
- sholderbach [documented unbinding a keybinding](https://github.com/nushell/nushell.github.io/pull/389), and [Fix intradoc links for German locale](https://github.com/nushell/nushell.github.io/pull/388), and [Fix several parts in the German edtion](https://github.com/nushell/nushell.github.io/pull/387)


## Nu_Scripts


- Yethal [updated nuschiit.nu](https://github.com/nushell/nu_scripts/pull/208), and [Add webscraping and gitlab scanning scripts](https://github.com/nushell/nu_scripts/pull/206)
- kubouch [changed conda activation scripts to be a module](https://github.com/nushell/nu_scripts/pull/205)
- hustcer [fixed completions for `git push` and `git checkout`](https://github.com/nushell/nu_scripts/pull/204)
- ZetaNumbers [fixed make complitions referred to undefinded "nu-complete files"](https://github.com/nushell/nu_scripts/pull/203)

## reedline

- sholderbach added [Use better word definition](https://github.com/nushell/reedline/pull/396), and [Cleanup some stuff found by pedantic clippy](https://github.com/nushell/reedline/pull/394), and [Remove `Hinter` and `Validator` from the default](https://github.com/nushell/reedline/pull/393), and [Allow the removal of keybindings](https://github.com/nushell/reedline/pull/391)
- fdncred [changed dark orange in prompt to purple](https://github.com/nushell/reedline/pull/395)
