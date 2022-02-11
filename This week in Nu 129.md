# This week in Nushell #129

## Nushell

- wingertge [removed stringification for binary values in `save` command](https://github.com/nushell/nushell/pull/4428), and [Fix in-shell docs for kill command in engine-q](https://github.com/nushell/nushell/pull/4393) 
- jt created [added support for defining known externals with their own custom completions ](https://github.com/nushell/nushell/pull/4425), and [improved quote path completions with drill-down](https://github.com/nushell/nushell/pull/4422), and [Fix captures](https://github.com/nushell/nushell/pull/4421), and [improved external command completions with spaces](https://github.com/nushell/nushell/pull/4420), and [fixed multi-command variable captures](https://github.com/nushell/nushell/pull/4413), and [Fix string interpolation paren cases](https://github.com/nushell/nushell/pull/4410), and [Fix help flag](https://github.com/nushell/nushell/pull/4398), and [Make `let-env` work like `let`](https://github.com/nushell/nushell/pull/4389), and [Bump reedline](https://github.com/nushell/nushell/pull/4388), and [Re-port filesystem commands](https://github.com/nushell/nushell/pull/4387), and [Move nth to select](https://github.com/nushell/nushell/pull/4385), and [Use 'table' on scripts and -c commands](https://github.com/nushell/nushell/pull/4377), and [Fix 'enter' to expand path before checking for it](https://github.com/nushell/nushell/pull/4370), and [Bump to 0.44](https://github.com/nushell/nushell/pull/4365), and [Merge engine-q into Nushell (second try)](https://github.com/nushell/nushell/pull/4364) 
- fdncred [added parameter to set thread count for parallel commands](https://github.com/nushell/nushell/pull/4424), and [tweak wording](https://github.com/nushell/nushell/pull/4415), and [turn down the perf volume a bit](https://github.com/nushell/nushell/pull/4412), and [fix broken `-w` param for `grid`](https://github.com/nushell/nushell/pull/4397), and [add `--perf` cli param](https://github.com/nushell/nushell/pull/4391), and [update starship docs](https://github.com/nushell/nushell/pull/4375), and [update ls_colors defaults](https://github.com/nushell/nushell/pull/4371) 
- elferherrera [deprecated commands](https://github.com/nushell/nushell/pull/4405) 
- sholderbach [fixed `trash-support` feature flag](https://github.com/nushell/nushell/pull/4394), and [made ANSI stripping lazy in more places](https://github.com/nushell/nushell/pull/4380), and [reduced table allocs: only strip ANSI if necessary](https://github.com/nushell/nushell/pull/4378) 
- henryrt [fixed "Index out of bounds" when input to the group-by filter is empty. #4369](https://github.com/nushell/nushell/pull/4382) 
- panicbit added [Support for records in reject command](https://github.com/nushell/nushell/pull/4373) 
- onsah added [Drop with iter range](https://github.com/nushell/nushell/pull/4242) 

## Documentation

- jaeheonji created [fix: delete duplicate header text](https://github.com/nushell/nushell.github.io/pull/219) 
- sakimyto [added regex documents](https://github.com/nushell/nushell.github.io/pull/218) 

## Nu_Scripts

- stormasm [updated file_cat to remove json files that are created](https://github.com/nushell/nu_scripts/pull/143), and [port dict.nu over to engine-q/cool_oneliners](https://github.com/nushell/nu_scripts/pull/142), and [port over to engine-q the script file_cat.nu](https://github.com/nushell/nu_scripts/pull/141) 
- skelly37 added [WolframAlpha API wrappers](https://github.com/nushell/nu_scripts/pull/140) 
- 
## engine-q


- jt created [bump reedline](https://github.com/nushell/engine-q/pull/970), and [Make PipelineData helpers collect rawstreams](https://github.com/nushell/engine-q/pull/969), and [Oops, match semantics of each group/window](https://github.com/nushell/engine-q/pull/967), and [Add each window](https://github.com/nushell/engine-q/pull/966), and [Add par-each group](https://github.com/nushell/engine-q/pull/965), and [Fix completion duplicates](https://github.com/nushell/engine-q/pull/964), and [Switch more commands to redirecting blocks](https://github.com/nushell/engine-q/pull/956), and [Port each group](https://github.com/nushell/engine-q/pull/953), and [Remove broken error make examples](https://github.com/nushell/engine-q/pull/951), and [Error make](https://github.com/nushell/engine-q/pull/948) 
- elferherrera created [Reedline bump](https://github.com/nushell/engine-q/pull/962) 
- sholderbach [updated reedline to race-condition-free history](https://github.com/nushell/engine-q/pull/955) 
- fdncred [renamed some files](https://github.com/nushell/engine-q/pull/952) 
- stormasm [fixed test math/avg.rs can_average_bytes](https://github.com/nushell/engine-q/pull/946) 

## reedline

- jntrnr fixed [Make up/down be one press per history entry](https://github.com/nushell/reedline/pull/306), and [Fix one item completions](https://github.com/nushell/reedline/pull/304) 
- elferherrera [revised quick completions](https://github.com/nushell/reedline/pull/305), and [Vi menus](https://github.com/nushell/reedline/pull/303), and [Menu events](https://github.com/nushell/reedline/pull/302) 
- sholderbach [made appending and truncating history file thread safe](https://github.com/nushell/reedline/pull/299) 
