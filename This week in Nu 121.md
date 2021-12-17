# This week in Nushell #121

## Nushell

- efx fixed [ci: update macOS agent](https://github.com/nushell/nushell/pull/4207), and [ci: fix macOS agent](https://github.com/nushell/nushell/pull/4203), and [use heck for string casing](https://github.com/nushell/nushell/pull/4081) 
- fdncred [updated feature template](https://github.com/nushell/nushell/pull/4201) 

## Nu_Scripts

- fdncred created [a fun script to create sparklines](https://github.com/nushell/nu_scripts/pull/116) 
- Yethal [updated docker.nu](https://github.com/nushell/nu_scripts/pull/115) 

## engine-q

- matthewauld [ported  'ansi gradient' command from nushell to engine-q](https://github.com/nushell/engine-q/pull/509), and [added a 'list' option to the ansi command](https://github.com/nushell/engine-q/pull/504), and [ported  'char' command from nushell to engine-q](https://github.com/nushell/engine-q/pull/500), and [ported 'ansi' command from nushell to engine-q](https://github.com/nushell/engine-q/pull/494) 
- sholderbach [fixed `Ctrl-D` exit in cli](https://github.com/nushell/engine-q/pull/508), and [made dialoguer completion abortable](https://github.com/nushell/engine-q/pull/507) 
- jt [bumped some deps](https://github.com/nushell/engine-q/pull/503), and [fixed comment issue and shadowing issue](https://github.com/nushell/engine-q/pull/501), and [fixed a couple crlf issues](https://github.com/nushell/engine-q/pull/496), and [fixed bug in chained boolean typecheck](https://github.com/nushell/engine-q/pull/490), and [bumped to use latest git reedline](https://github.com/nushell/engine-q/pull/488), and [added better filepath completions](https://github.com/nushell/engine-q/pull/485), and added [ps still needs a delay to be accurate](https://github.com/nushell/engine-q/pull/484), and [made config default if broken](https://github.com/nushell/engine-q/pull/482), and [added in variable and sub-command completions](https://github.com/nushell/engine-q/pull/480), and [added in auto-cd if you pass just a directory](https://github.com/nushell/engine-q/pull/479) 
- fdncred [allowed flatshape (command line syntax) theming](https://github.com/nushell/engine-q/pull/502), and [allowed fg, bg, attributes to be set for all colors in color_config](https://github.com/nushell/engine-q/pull/489), and [allowed user to use hex colors in config](https://github.com/nushell/engine-q/pull/486), and [tweaked `version` output as a list vs table](https://github.com/nushell/engine-q/pull/472), and [added `temp-path` to `$nu`](https://github.com/nushell/engine-q/pull/471), and [added `keybinding-path` to `$nu`](https://github.com/nushell/engine-q/pull/470), and [added `cwd` to `$nu`](https://github.com/nushell/engine-q/pull/469), and [added `home-path` to `$nu`](https://github.com/nushell/engine-q/pull/468), and [updated to 2021 edition](https://github.com/nushell/engine-q/pull/466) 
- stormasm [ported drop nth](https://github.com/nushell/engine-q/pull/498), and [ported drop column](https://github.com/nushell/engine-q/pull/495) 
- kubouch created [Treating environment variables as Values](https://github.com/nushell/engine-q/pull/497), and [fixed hiding of import patterns with globs](https://github.com/nushell/engine-q/pull/487), and [added docs page about modules and overlays](https://github.com/nushell/engine-q/pull/478) 
- CBenoit [fixed error propagation across `hash` commands](https://github.com/nushell/engine-q/pull/493), and [sorted default context items categorically](https://github.com/nushell/engine-q/pull/465) 
- jaeheonji [fixed missing bind commands](https://github.com/nushell/engine-q/pull/477) 
- elferherrera created [Plugin json](https://github.com/nushell/engine-q/pull/475), and [Plugin json](https://github.com/nushell/engine-q/pull/474) 
- onthebridgetonowhere [ported version](https://github.com/nushell/engine-q/pull/467) 
- arthur-targaryen [ported `keep`, `keep while` and `keep until` commands](https://github.com/nushell/engine-q/pull/384) 
- LiHRaM [added Path commands](https://github.com/nushell/engine-q/pull/280) 

## reedline

- jt created [Crlf fixes](https://github.com/nushell/reedline/pull/199), and [added some wrapping estimate when adjusting prompt](https://github.com/nushell/reedline/pull/198) 

