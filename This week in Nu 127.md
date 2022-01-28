# This week in Nushell #127

## Nushell

- jt created [Remove unused repo parts](https://github.com/nushell/nushell/pull/4271) 

## Nu_Scripts

- fdncred created [kubouch's benchmark script](https://github.com/nushell/nu_scripts/pull/139), and [port the gradient script](https://github.com/nushell/nu_scripts/pull/138), and [update output to records](https://github.com/nushell/nu_scripts/pull/137), and [port `timed_weather_run` to engine-q](https://github.com/nushell/nu_scripts/pull/136), and [update get_weather syntax](https://github.com/nushell/nu_scripts/pull/135) 

## engine-q

- jt created ["maybe text codec" version 2](https://github.com/nushell/engine-q/pull/871), and [Harden highlighter against alias spans](https://github.com/nushell/engine-q/pull/867), and [Move history search to ctrl-x](https://github.com/nushell/engine-q/pull/864), and [Allow equals to separate long flag and arg](https://github.com/nushell/engine-q/pull/858), and [Also set $in-variable with input](https://github.com/nushell/engine-q/pull/856), and [Allow let/let-env to see custom command input](https://github.com/nushell/engine-q/pull/854), and [Add -c flag and others to cmdline args](https://github.com/nushell/engine-q/pull/853), and [Start support for commandline args to nu itself](https://github.com/nushell/engine-q/pull/851), and [Port exec command](https://github.com/nushell/engine-q/pull/849), and [Port default command](https://github.com/nushell/engine-q/pull/848), and [Fix expanding external args](https://github.com/nushell/engine-q/pull/847), and [Fix bug in date comparison](https://github.com/nushell/engine-q/pull/842), and [Allow `open` to read its filename from input](https://github.com/nushell/engine-q/pull/841), and [Allow external args to expand globs](https://github.com/nushell/engine-q/pull/839), and [Highlight help tutor](https://github.com/nushell/engine-q/pull/838), and [Add var vals and alias expansions to scope var](https://github.com/nushell/engine-q/pull/837), and [Only escape backslash on windows](https://github.com/nushell/engine-q/pull/825), and [Add flag completions](https://github.com/nushell/engine-q/pull/817), and [Fix doc comments for custom commands](https://github.com/nushell/engine-q/pull/815), and [Make external app error uniform](https://github.com/nushell/engine-q/pull/812) 
- sholderbach [added F1-F12 key support](https://github.com/nushell/engine-q/pull/866), and [Accomodate reedline#270](https://github.com/nushell/engine-q/pull/863) 
- eggcaker [fixed into datetime example parameter type](https://github.com/nushell/engine-q/pull/862), and [allow fetch command to add custom headers](https://github.com/nushell/engine-q/pull/840), and [Add how to setup oh-my-posh with engine-q document](https://github.com/nushell/engine-q/pull/810) 
- elferherrera created [using menu trait](https://github.com/nushell/engine-q/pull/861), and [History menu](https://github.com/nushell/engine-q/pull/846) 
- stormasm [added support for Floats for sort-by](https://github.com/nushell/engine-q/pull/857), and [fix several cases where sort-by was crashing engine-q](https://github.com/nushell/engine-q/pull/836), and [port sort_by without float (yet)](https://github.com/nushell/engine-q/pull/814) 
- onthebridgetonowhere [added suport for Filesize and Date for sort-by command](https://github.com/nushell/engine-q/pull/855), and [Flatten records](https://github.com/nushell/engine-q/pull/845), and [Fix cd-ing into a file](https://github.com/nushell/engine-q/pull/831), and [Fix flatten's dropping column issue #756](https://github.com/nushell/engine-q/pull/805) 
- fdncred [allowed find to respect ls_colors](https://github.com/nushell/engine-q/pull/834), and [capture keyboard event](https://github.com/nushell/engine-q/pull/832), and [ansi cut 2.0 update to cargo.lock](https://github.com/nushell/engine-q/pull/827), and [fix to retain ls_colors coloring from ls](https://github.com/nushell/engine-q/pull/824), and [add `hash base64` subcommand](https://github.com/nushell/engine-q/pull/813), and [added 3rd party prompt docs](https://github.com/nushell/engine-q/pull/811) 
- kubouch [ported move](https://github.com/nushell/engine-q/pull/833) 
- zhiburt [drafted: Bump `ansi-cut` version to 0.2.0](https://github.com/nushell/engine-q/pull/822) 
- arthur-targaryen [ported `find` command](https://github.com/nushell/engine-q/pull/658) 

## reedline

- sholderbach created [coerce to CRLF lazily](https://github.com/nushell/reedline/pull/281), and [Fix after entry cursor positioning at the bottom](https://github.com/nushell/reedline/pull/279), and [Small Painting changes to improve readability and correctness](https://github.com/nushell/reedline/pull/278), and [Remove outdated CompletionActionHandler(s)](https://github.com/nushell/reedline/pull/270) 
- elferherrera created [chronological order search](https://github.com/nushell/reedline/pull/280), and [add return for multiline](https://github.com/nushell/reedline/pull/277), and [Generic menus](https://github.com/nushell/reedline/pull/276), and [History menu](https://github.com/nushell/reedline/pull/275), and [Long menu](https://github.com/nushell/reedline/pull/273)
