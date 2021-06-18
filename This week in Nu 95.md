# This week in Nushell #95

## Package news

- You can now install Nushell directly from the [official winget packages](https://github.com/microsoft/winget-pkgs/tree/master/manifests/n/Nushell/Nushell/0.32.0) using `winget install nu`.

## Nushell

- andrasio [cleaned up nu-completion dependencies.](https://github.com/nushell/nushell/pull/3645), [supported version option in Nu bin.](https://github.com/nushell/nushell/pull/3632), [extracted completions into subcrate.](https://github.com/nushell/nushell/pull/3631), connected [Nu's rest arguments are source(s) files scripts to run.](https://github.com/nushell/nushell/pull/3624), [removeed 'help' Nu bin positional support.](https://github.com/nushell/nushell/pull/3621), and updated [Nu to bootstrap itself from main.](https://github.com/nushell/nushell/pull/3619) 
- jonathandturner [fixed the ignore example](https://github.com/nushell/nushell/pull/3644), [relaxed groups and blocks to output at pipeline level](https://github.com/nushell/nushell/pull/3643), [fixed issue in external subexpression paths](https://github.com/nushell/nushell/pull/3642), [added back disks and net to sys](https://github.com/nushell/nushell/pull/3639), [added file not found error for nu cmd args](https://github.com/nushell/nushell/pull/3627), and [refactored rarely changing engine state into its own struct](https://github.com/nushell/nushell/pull/3612) 
- chrisfinazzo fixed a [Shellcheck issue](https://github.com/nushell/nushell/pull/3635) 
- fdncred [fixed FlatShape::Garbage's default foreground color](https://github.com/nushell/nushell/pull/3634) 
- vladdoster added [(docs) update README.md](https://github.com/nushell/nushell/pull/3630) 
- NiklasJonsson fixed the parser to [only discard command comment if prev token was comment](https://github.com/nushell/nushell/pull/3628) 
- reaganmcf added [Plugin: from_mp4 and UntaggedValue::duration fix](https://github.com/nushell/nushell/pull/3618) 
- itsme-alan [added winget installation instructions ](https://github.com/nushell/nushell/pull/3615) 
- voanhduy1512 [fixed syntax hightlight when using Circumflex-Operator](https://github.com/nushell/nushell/pull/3613), and [added support to run external command with string evaluation](https://github.com/nushell/nushell/pull/3611) 
- elferherrera added [dataframe commands](https://github.com/nushell/nushell/pull/3608) 
- sambordo1 [ported mkdir to engine-p](https://github.com/nushell/nushell/pull/3607) 

## Documentation

- sholderbach [fixed missed mention of duration literal](https://github.com/nushell/nushell.github.io/pull/147) 

## Nu_Scripts

- andrasio [added nu-completion subcrate to the release script](https://github.com/nushell/nu_scripts/pull/65) 
