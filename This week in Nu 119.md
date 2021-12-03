# This week in Nushell #119

## Nushell

- jt created [Clippy 1.57 fixes](https://github.com/nushell/nushell/pull/4176), and [removed 'arboard'](https://github.com/nushell/nushell/pull/4174) 
- ahouts [added -l/--login flags for compatibility with other shells](https://github.com/nushell/nushell/pull/4175) 
- fdncred removed [upx](https://github.com/nushell/nushell/pull/4173), and [bye bye upx, let's try stripping alone](https://github.com/nushell/nushell/pull/4172) 
- BraulioVM [sanitized arguments to external commands a bit better](https://github.com/nushell/nushell/pull/4157) 
- vmiheer fixed [docs talking about accessing $it outside each](https://github.com/nushell/nushell/pull/4000) 

## Documentation

- rashil2000 [added winget as installation method](https://github.com/nushell/nushell.github.io/pull/208) 

## Nu_Scripts

- kubouch [fixed typo in directory name](https://github.com/nushell/nu_scripts/pull/109), and [Add example engine-q config script with a module](https://github.com/nushell/nu_scripts/pull/108) 
- skelly37 [documented + minor enchancement](https://github.com/nushell/nu_scripts/pull/107) 
- fdncred [added storm to maintainers](https://github.com/nushell/nu_scripts/pull/106) 

## engine-q

- fdncred created [this fixes garbage ansi when externals turn off vt processing](https://github.com/nushell/engine-q/pull/422), and [add back debug --raw switch](https://github.com/nushell/engine-q/pull/401), and [add optional footer to table](https://github.com/nushell/engine-q/pull/392), and [added row_index coloring](https://github.com/nushell/engine-q/pull/391), and [allow icons to be used in `grid -c`](https://github.com/nushell/engine-q/pull/378), and [enable env setting for prompt animation](https://github.com/nushell/engine-q/pull/376) 
- kubouch created [Add canonicalization to parser paths; Improve FileNotFound error](https://github.com/nushell/engine-q/pull/421), and [Fix 'help commands'; Add 'is_custom' column](https://github.com/nushell/engine-q/pull/420), and [Rename add_decls() to use_decls()](https://github.com/nushell/engine-q/pull/395), and [Hiding of environment variables](https://github.com/nushell/engine-q/pull/362) 
- elferherrera created [Plugin repeated](https://github.com/nushell/engine-q/pull/417), and [Plugin path for $nu](https://github.com/nushell/engine-q/pull/398), and [Plugin with evaluated call](https://github.com/nushell/engine-q/pull/393), and [Testing suite for dataframes](https://github.com/nushell/engine-q/pull/379), and [Option to replace command same name](https://github.com/nushell/engine-q/pull/374) 
- jt created [Try some fixes for external paths](https://github.com/nushell/engine-q/pull/415), and [Add table streaming](https://github.com/nushell/engine-q/pull/413), and [Just a few cleanups around error messages](https://github.com/nushell/engine-q/pull/411), and [Fix plurals in abbrevations](https://github.com/nushell/engine-q/pull/409), and [Add value abbreviations](https://github.com/nushell/engine-q/pull/407), and [Update external spawn](https://github.com/nushell/engine-q/pull/406), and [Default prompt animations to off](https://github.com/nushell/engine-q/pull/403), and [Move prompt animation setting to config](https://github.com/nushell/engine-q/pull/400), and [Fix parse error metadata](https://github.com/nushell/engine-q/pull/399), and [Introduce metadata into the pipeline](https://github.com/nushell/engine-q/pull/397), and [A few help cleanups](https://github.com/nushell/engine-q/pull/372) 
- luccasmmg created [`to csv` and `to tsv` ](https://github.com/nushell/engine-q/pull/412), and [`to url` and `to toml`](https://github.com/nushell/engine-q/pull/396), and [From ssv from xml](https://github.com/nushell/engine-q/pull/383) 
- onthebridgetonowhere created [Port str to-decimal to into decimal command.](https://github.com/nushell/engine-q/pull/408), and [[str-trim] Remove Arc from Arguments](https://github.com/nushell/engine-q/pull/405), and [Port str upcase](https://github.com/nushell/engine-q/pull/404), and [Port str trim](https://github.com/nushell/engine-q/pull/394), and [Add the support of str to-int to the into int command](https://github.com/nushell/engine-q/pull/389), and [Port str substring command](https://github.com/nushell/engine-q/pull/388) 
- jaeheonji created [feat(random): add random-decimal](https://github.com/nushell/engine-q/pull/402), and [feat(random): add random-chars](https://github.com/nushell/engine-q/pull/390), and [add random commands](https://github.com/nushell/engine-q/pull/366) 
- sholderbach [fixed busy poll with reedline](https://github.com/nushell/engine-q/pull/387) 
- Scorpil [ported over the kill command from nushell](https://github.com/nushell/engine-q/pull/381), and [Ported over the clear command from nushell](https://github.com/nushell/engine-q/pull/373), and [Ported over the sleep command from nushell](https://github.com/nushell/engine-q/pull/371) 
- arthur-targaryen [ported `skip`, `skip while` and `skip until` commands](https://github.com/nushell/engine-q/pull/380), and [Ported `any?` command](https://github.com/nushell/engine-q/pull/375), and [Ported `all?` command](https://github.com/nushell/engine-q/pull/365) 

## reedline

- sholderbach [fixed clippy style and remove unecessary stuff](https://github.com/nushell/reedline/pull/192), and [Improved undo of EditCommands](https://github.com/nushell/reedline/pull/191), and [Fixed busy polling when animation is disabled](https://github.com/nushell/reedline/pull/188), and [Fixed cursor flickering for full repaint](https://github.com/nushell/reedline/pull/187) 
- aslynatilla created [Forwarding Prompt's multiline indicator](https://github.com/nushell/reedline/pull/185) 
