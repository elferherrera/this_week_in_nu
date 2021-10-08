# This week in Nushell #111

## Nushell

- fdncred [removed history file after clearing it](https://github.com/nushell/nushell/pull/4069) 
- jt [updated LICENSE](https://github.com/nushell/nushell/pull/4067), [released 0.38](https://github.com/nushell/nushell/pull/4064), [remove the broken scrolling support](https://github.com/nushell/nushell/pull/4063), and [updated wasm deps](https://github.com/nushell/nushell/pull/4061) 
- waldyrious created [stale.yml: mention time to close in stale message](https://github.com/nushell/nushell/pull/4066) 
- JoshCheek [added `-c` flag to `select` command](https://github.com/nushell/nushell/pull/4062) 
- hedonihilist added [expand tilde when reading plugin_dirs](https://github.com/nushell/nushell/pull/4052) 
- hojjatabdollahi [fixeded two typos in the tutor.](https://github.com/nushell/nushell/pull/4051) 

## Documentation

- thomasaarholt [fixed typo in "config set" instructions](https://github.com/nushell/nushell.github.io/pull/202) 
- raboof created [Coming from bash: `echo $FOO` = `echo $nu.env.FOO`](https://github.com/nushell/nushell.github.io/pull/200) 

## engine-q

- jt [improved the alias expansion](https://github.com/nushell/engine-q/pull/104), [created LICENSE](https://github.com/nushell/engine-q/pull/100), added [Source command](https://github.com/nushell/engine-q/pull/99), added [Variable completions and better ls](https://github.com/nushell/engine-q/pull/95), [added unit parsing and eval support](https://github.com/nushell/engine-q/pull/93), added [better completions for external args](https://github.com/nushell/engine-q/pull/92), changed to [use list completions and better expansion](https://github.com/nushell/engine-q/pull/91), [added path completions](https://github.com/nushell/engine-q/pull/90), fixed so [lines shouldn't trim](https://github.com/nushell/engine-q/pull/87), [added simple cd](https://github.com/nushell/engine-q/pull/86), fixed to [let strings be cell paths](https://github.com/nushell/engine-q/pull/83), [added select](https://github.com/nushell/engine-q/pull/82), and [added wrap and get and cell_path parsing](https://github.com/nushell/engine-q/pull/81) 
- fdncred created [allow one to specify a custom separator for the grid](https://github.com/nushell/engine-q/pull/103), and [respect lscolors env var; measure width minus ansi](https://github.com/nushell/engine-q/pull/102), and [output `ls` as a grid vs table](https://github.com/nushell/engine-q/pull/96) 
- xiuxiu62 [added touch command](https://github.com/nushell/engine-q/pull/101), [ported `cp` to fs commands](https://github.com/nushell/engine-q/pull/98), and [ported the mv command](https://github.com/nushell/engine-q/pull/88) 
- stormasm created [The signature of the get command was mistakenly named wrap](https://github.com/nushell/engine-q/pull/97), and [added serde derive to Cargo.toml so nu-protocol compiles standalone](https://github.com/nushell/engine-q/pull/85) 
- kubouch [added import patterns to 'hide'](https://github.com/nushell/engine-q/pull/89), and [Modules: export & hide](https://github.com/nushell/engine-q/pull/74) 
- elferherrera created [prompt with env variable](https://github.com/nushell/engine-q/pull/84) 

## reedline

- jntrnr [updated LICENSE](https://github.com/nushell/reedline/pull/163), and [added list style completions](https://github.com/nushell/reedline/pull/162) 
- sholderbach created [Fix README badges](https://github.com/nushell/reedline/pull/161), and [Clarify method names for undo-interface](https://github.com/nushell/reedline/pull/160), and [Simplify and document history trait](https://github.com/nushell/reedline/pull/159), and [fixed CtrlD/CtrlC and reverse-history-search + stuff](https://github.com/nushell/reedline/pull/155) 
- mzanrosso created [[BugFix] undo function](https://github.com/nushell/reedline/pull/143) 

