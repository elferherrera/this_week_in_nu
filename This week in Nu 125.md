# This week in Nushell #125

## Nushell

- michel-slm [updated descriptions for crates split out from nu-cli](https://github.com/nushell/nushell/pull/4247) 

## Extension

- smurawski [cached the install to cargo/bin on Windows](https://github.com/nushell/vscode-nushell-lang/pull/44) 

## Nu_Scripts

- kubouch [updated e-q example config](https://github.com/nushell/nu_scripts/pull/129), and [restored fehbg.nu](https://github.com/nushell/nu_scripts/pull/125), and [added base16 integration](https://github.com/nushell/nu_scripts/pull/123) 
- fdncred [updated based on jt's capture fix](https://github.com/nushell/nu_scripts/pull/128), and [ported of get_weather.nu script to engine-q](https://github.com/nushell/nu_scripts/pull/127), and [tweaked some icons](https://github.com/nushell/nu_scripts/pull/126), and [added the ability to have a right hand prompt](https://github.com/nushell/nu_scripts/pull/122) 

## engine-q

- stormasm [updated Readme to final merge checklist](https://github.com/nushell/engine-q/pull/741), and [cleanup of the select command and add in a new test](https://github.com/nushell/engine-q/pull/718) 
- jt [added nu-system and rewrote ps command](https://github.com/nushell/engine-q/pull/734), and added [Clippy fixes for Rust 1.58](https://github.com/nushell/engine-q/pull/733), [bumped reedline again](https://github.com/nushell/engine-q/pull/732), [added support for var/string interp for external names](https://github.com/nushell/engine-q/pull/729), [fixed captures](https://github.com/nushell/engine-q/pull/723), and fixed [panic on alias errors](https://github.com/nushell/engine-q/pull/713), and [bumped reedline](https://github.com/nushell/engine-q/pull/712), and added [silly keymap addition for quick shell changing](https://github.com/nushell/engine-q/pull/710) 
- sholderbach [added instructions to run engine-q](https://github.com/nushell/engine-q/pull/731) 
- fdncred [exposed a few more types to custom commands (`def`)](https://github.com/nushell/engine-q/pull/725), and added [a little better table alignment](https://github.com/nushell/engine-q/pull/720), and [reverted "added a better default for ls_colors"](https://github.com/nushell/engine-q/pull/711), and [new command `fmt` to format numbers](https://github.com/nushell/engine-q/pull/707), and [added a better default for ls_colors](https://github.com/nushell/engine-q/pull/703), and [add more chars](https://github.com/nushell/engine-q/pull/701) 
- elferherrera created [menu with tab](https://github.com/nushell/engine-q/pull/724), and [context menu with nucompleter](https://github.com/nushell/engine-q/pull/722), and [reedline bump](https://github.com/nushell/engine-q/pull/717) 
- kubouch [cleaned up use and hide parsing](https://github.com/nushell/engine-q/pull/705), and [add reduce command](https://github.com/nushell/engine-q/pull/700), and [add repository name and current tag to gstat](https://github.com/nushell/engine-q/pull/692) 

## reedline

- sholderbach [moved running of EditCommands to the editor](https://github.com/nushell/reedline/pull/251), and [hid hint when finishing line entry](https://github.com/nushell/reedline/pull/250) 
- elferherrera created [menu improvements](https://github.com/nushell/reedline/pull/249), and [menu with tab](https://github.com/nushell/reedline/pull/248), and [Context menu with completer](https://github.com/nushell/reedline/pull/247), and [menu filler builder](https://github.com/nushell/reedline/pull/246), and [Context menu](https://github.com/nushell/reedline/pull/243), and [remove position function](https://github.com/nushell/reedline/pull/242) 
- jt created [Right arrow is full hint completion](https://github.com/nushell/reedline/pull/244) 

