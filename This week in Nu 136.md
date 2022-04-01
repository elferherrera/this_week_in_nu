# This week in Nushell #136


## Nushell


- elferherrera [updated reedline](https://github.com/nushell/nushell/pull/5062), and [evaluate indicators as commands](https://github.com/nushell/nushell/pull/5026), and [corrects menu selection](https://github.com/nushell/nushell/pull/5004), and [Help menu](https://github.com/nushell/nushell/pull/4992)
- fdncred [added starts with operator](https://github.com/nushell/nushell/pull/5061), and [finish hooking up completion descriptions](https://github.com/nushell/nushell/pull/5047), and [Nu ansi term update](https://github.com/nushell/nushell/pull/4988), and [fix ls when file is a socket on mac](https://github.com/nushell/nushell/pull/4983)
- jt [let a simple last be a single value](https://github.com/nushell/nushell/pull/5060), and [Add 'date to-record'](https://github.com/nushell/nushell/pull/5058), and [Fix sort signature](https://github.com/nushell/nushell/pull/5055), and [Sort command](https://github.com/nushell/nushell/pull/5054), and [Allow strings for prompt env vars](https://github.com/nushell/nushell/pull/5052), and [Use real stack during custom completion](https://github.com/nushell/nushell/pull/5010), and [Fix for loop ctrlc not terminating](https://github.com/nushell/nushell/pull/5003), and [See if levenshtein sorting feels good for completions](https://github.com/nushell/nushell/pull/5001), and [Help menu improvements](https://github.com/nushell/nushell/pull/4997), and [Bump nushell to 0.60.1](https://github.com/nushell/nushell/pull/4987)
- sholderbach [updated reedline to new constructor API](https://github.com/nushell/nushell/pull/5051), and [Lift line editor construction out of loop](https://github.com/nushell/nushell/pull/5041)
- neosam [allowed open to work with 'from ...' block commands](https://github.com/nushell/nushell/pull/5049)
- kubouch [added record, list, and table to signature types](https://github.com/nushell/nushell/pull/5040), and [Add a README about changing capnp schema](https://github.com/nushell/nushell/pull/4998), and [Add search terms to Command and Signature](https://github.com/nushell/nushell/pull/4980)
- rgwood [fixed load-env unsupported input error message](https://github.com/nushell/nushell/pull/5039), and [Fix which command](https://github.com/nushell/nushell/pull/5038), and [Fix env var shorthand when value contains `=`](https://github.com/nushell/nushell/pull/5022), and [Clean up which/which-support Cargo feature](https://github.com/nushell/nushell/pull/5019), and [Improve did_you_mean, add tests](https://github.com/nushell/nushell/pull/4999), and [Case-insensitive search in did_you_mean](https://github.com/nushell/nushell/pull/4991)
- stormasm [updated nu-glob README](https://github.com/nushell/nushell/pull/5037)
- dev-msp created [feat: add --suppress-output (-s) to input command](https://github.com/nushell/nushell/pull/5017)
- naufraghi [striped '+ ' decoration in git branch list](https://github.com/nushell/nushell/pull/5016)
- rrcwang [fixed: pass metadata to more filter commands for `ls_colors`](https://github.com/nushell/nushell/pull/5009)
- futile [updated README.md for Rust 1.59](https://github.com/nushell/nushell/pull/4995)
- b333z [limited mem usage + back-pressure via bounded channels](https://github.com/nushell/nushell/pull/4986), and [Add streaming support to save for ExternalStream data](https://github.com/nushell/nushell/pull/4985), and [Support binary data to stdin of run-external](https://github.com/nushell/nushell/pull/4984)

## Extension

- fdncred created [updates](https://github.com/nushell/vscode-nushell-lang/pull/52)

## Documentation

- filaretov [updated instructions on aliasing open](https://github.com/nushell/nushell.github.io/pull/360)
- chtenb [updated coloring_and_theming.md](https://github.com/nushell/nushell.github.io/pull/359)
- herlon214 created [book/coming-form-bash: fix type == dir](https://github.com/nushell/nushell.github.io/pull/358)
- hustcer added [some small fix](https://github.com/nushell/nushell.github.io/pull/356), and [chore: Ignore formatting the docs for commands](https://github.com/nushell/nushell.github.io/pull/355), and [Add husky and prettier to format code automatically while committing code](https://github.com/nushell/nushell.github.io/pull/347)
- jt [consolidated prompt config to the 3rd party prompt chapter](https://github.com/nushell/nushell.github.io/pull/353)
- kubouch [moved the "main" word outside of code block](https://github.com/nushell/nushell.github.io/pull/351)

## Nu_Scripts

- fdncred created [fixes after #5060](https://github.com/nushell/nu_scripts/pull/197), and [update completions](https://github.com/nushell/nu_scripts/pull/193)
- Hofer-Julian [moved completions to module format](https://github.com/nushell/nu_scripts/pull/195)
- Eschryn created [[completions-cargo] complete targets from cargo metadata](https://github.com/nushell/nu_scripts/pull/194)
- skelly37 switched to [CD-path implemented in 0.60](https://github.com/nushell/nu_scripts/pull/192)
- ZetaNumbers [made "nu-complete cargo packages" offline for speed](https://github.com/nushell/nu_scripts/pull/191)
- dazfuller [added git switch completion](https://github.com/nushell/nu_scripts/pull/190)

## reedline

- elferherrera updated [format descriptions to the left](https://github.com/nushell/reedline/pull/375), and [bashisms feature for reedline](https://github.com/nushell/reedline/pull/374), and [corrects menu selection](https://github.com/nushell/reedline/pull/369), and [Vim normal keybingings](https://github.com/nushell/reedline/pull/365), and [update history menu](https://github.com/nushell/reedline/pull/362), and [Descriptions for completion suggestions](https://github.com/nushell/reedline/pull/358)
- sholderbach [exposed the history as syncable and readable](https://github.com/nushell/reedline/pull/373), and [API break: remove unnecessary fallibility](https://github.com/nushell/reedline/pull/367)
- wmstack [fixed the first example in the readme so it can be run](https://github.com/nushell/reedline/pull/371)
- sherubthakur [edited stack](https://github.com/nushell/reedline/pull/368)
- uasi [fixed `menu::menu_functions::string_difference`](https://github.com/nushell/reedline/pull/364), and [Fix `menu::menu_functions::find_common_string`](https://github.com/nushell/reedline/pull/363)
- fdncred [bumped to 0.3.1 and nu-ansi-term to 0.45.1](https://github.com/nushell/reedline/pull/361)
