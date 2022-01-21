# This week in Nushell #126

Note: this is the first "This week in Nu" created with engine-q!

## Nushell

- jt created [released 0.43](https://github.com/nushell/nushell/pull/4264), and added [Tutor eq](https://github.com/nushell/nushell/pull/4263), and [fixed clippy lints](https://github.com/nushell/nushell/pull/4262) 
- GuillaumeGomez [update sysinfo version](https://github.com/nushell/nushell/pull/4261) 
- dependabot [bumped follow-redirects from 1.14.4 to 1.14.7 in /samples/wasm](https://github.com/nushell/nushell/pull/4258) 

## Documentation

- CKingX [updated nushell_map_imperative.md](https://github.com/nushell/nushell.github.io/pull/214) 

## Nu_Scripts

- fdncred [ported spark](https://github.com/nushell/nu_scripts/pull/131), and [add 7 day forecast](https://github.com/nushell/nu_scripts/pull/130) 

## engine-q

- sholderbach created [Upgrade reedline for partial hint completion](https://github.com/nushell/engine-q/pull/802), and [Fix unicode word wrapping with ansi-cut](https://github.com/nushell/engine-q/pull/767) 
- fdncred created [allow `use` to parse quoted paths](https://github.com/nushell/engine-q/pull/800), and [add `term size` command](https://github.com/nushell/engine-q/pull/792), and [`PATH` for completions for each os](https://github.com/nushell/engine-q/pull/784), and [keybinding completeness, make case-insensitive](https://github.com/nushell/engine-q/pull/780), and [allow `size` and other to count bytes from binary with `as_string()`](https://github.com/nushell/engine-q/pull/769), and [remove dialoguer completions in favor of reedline's](https://github.com/nushell/engine-q/pull/766), and [fix signature](https://github.com/nushell/engine-q/pull/765), and [fix list formatting](https://github.com/nushell/engine-q/pull/762) 
- jt added [Support recursive functions in capture](https://github.com/nushell/engine-q/pull/797), and [Add CMD_DURATION_MS](https://github.com/nushell/engine-q/pull/794), and [let prompt env vars take strings](https://github.com/nushell/engine-q/pull/790), and [Better help search](https://github.com/nushell/engine-q/pull/789), and [bump reedline](https://github.com/nushell/engine-q/pull/788), and [add `cd -` support](https://github.com/nushell/engine-q/pull/787), and [Bump reedline](https://github.com/nushell/engine-q/pull/785), and [add some more division for units](https://github.com/nushell/engine-q/pull/783), and [Add `which` command, add external completions, and builtin var completions](https://github.com/nushell/engine-q/pull/782), and [Show error on bad config, but keep going](https://github.com/nushell/engine-q/pull/778), and [Improve env shorthand parse](https://github.com/nushell/engine-q/pull/777), and [Let 'to toml' output block source](https://github.com/nushell/engine-q/pull/763), and [Enter now requires a directory](https://github.com/nushell/engine-q/pull/761), and [Add rest to get, bump reedline](https://github.com/nushell/engine-q/pull/760), and [Add simple stdin input command](https://github.com/nushell/engine-q/pull/754), and [Add support for load-env](https://github.com/nushell/engine-q/pull/752), and [Save](https://github.com/nushell/engine-q/pull/750), and [Hide Windows ps status, bump reedline](https://github.com/nushell/engine-q/pull/749), and [Improve keyword parsing, including for](https://github.com/nushell/engine-q/pull/747) 
- elferherrera created [menu performance](https://github.com/nushell/engine-q/pull/793), and [general keybindings](https://github.com/nushell/engine-q/pull/775), and [simple event keybinding](https://github.com/nushell/engine-q/pull/773), and [Keybindings config](https://github.com/nushell/engine-q/pull/768), and [menu options](https://github.com/nushell/engine-q/pull/748) 
- stormasm created [update all cargo crates to edition 2021](https://github.com/nushell/engine-q/pull/781) 
- kubouch created [Fix empty entry in ls](https://github.com/nushell/engine-q/pull/759), and [Fix ls relative path & command argument path expansion](https://github.com/nushell/engine-q/pull/757), and [Revert "Fix ls relative path and erroring on fake dir"](https://github.com/nushell/engine-q/pull/744) 
- nibon7 created [Port `seq` command](https://github.com/nushell/engine-q/pull/755) 
- onsah created [Fix not equal returning error when same things are compared in some cases](https://github.com/nushell/engine-q/pull/709) 
- onthebridgetonowhere created [Fix ls relative path and erroring on fake dir](https://github.com/nushell/engine-q/pull/697) 

## reedline

- sholderbach added [Support "token by token" hint completion](https://github.com/nushell/reedline/pull/269), and [Ensure easy mapping of (key)events to different context dependent event handlers](https://github.com/nushell/reedline/pull/267), and [Distill `DefaultHinter` down to history suggestions](https://github.com/nushell/reedline/pull/265), and [Remove `Reedline::print_line` from the API](https://github.com/nushell/reedline/pull/263), and [Remove superfluous insertion of carriage return](https://github.com/nushell/reedline/pull/262) 
- elferherrera added [menu performance](https://github.com/nushell/reedline/pull/268), and [action and complete events](https://github.com/nushell/reedline/pull/260), and [Parsing keybindings](https://github.com/nushell/reedline/pull/257), and [Tab backwards](https://github.com/nushell/reedline/pull/255), and [Tab correction](https://github.com/nushell/reedline/pull/254), and [Menu config](https://github.com/nushell/reedline/pull/253) 
