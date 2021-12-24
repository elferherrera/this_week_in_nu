# This week in Nushell #122

## Nushell

- nibon7 fixed [bat: use regex-onig instead of regex-fancy](https://github.com/nushell/nushell/pull/4226), and [allow insecure server connections when using SSL](https://github.com/nushell/nushell/pull/4219) 
- BraulioVM fixed [Don't panic if the other end of std{out,err} is closed](https://github.com/nushell/nushell/pull/4179) 

## Extension

- fdncred [updated release.yml](https://github.com/nushell/vscode-nushell-lang/pull/42) 

## engine-q

- jt [added support for 'open'](https://github.com/nushell/engine-q/pull/573), and [Wire hex viewing into a few more places](https://github.com/nushell/engine-q/pull/572), and [Add string stream and binary stream, add text decoding](https://github.com/nushell/engine-q/pull/570), and [Add metadata command](https://github.com/nushell/engine-q/pull/569), and [Add missing flags to existing commands](https://github.com/nushell/engine-q/pull/565), and [Some multiline fixes](https://github.com/nushell/engine-q/pull/557), and [Improve multiline history](https://github.com/nushell/engine-q/pull/556), and [Add history command](https://github.com/nushell/engine-q/pull/553), and [Use latest history hint](https://github.com/nushell/engine-q/pull/552), and [Improve history hint](https://github.com/nushell/engine-q/pull/551), and [Signature improvements, sorted completions](https://github.com/nushell/engine-q/pull/545), and [Fix list printing](https://github.com/nushell/engine-q/pull/540), and [switch substring to bytes](https://github.com/nushell/engine-q/pull/538), and [Merged heterogeneous tables](https://github.com/nushell/engine-q/pull/536), and [Flatten should flatten embedded table](https://github.com/nushell/engine-q/pull/534), and [Finish adding support for optional params](https://github.com/nushell/engine-q/pull/530), and [Allow empty span slice for now](https://github.com/nushell/engine-q/pull/529), and [Remove Span::unknown](https://github.com/nushell/engine-q/pull/525), and [Fix completion crash](https://github.com/nushell/engine-q/pull/521) 
- fdncred [added configuration point for hint coloring](https://github.com/nushell/engine-q/pull/564), and [add configuration of maximum history size](https://github.com/nushell/engine-q/pull/563), and [update to latest reedline](https://github.com/nushell/engine-q/pull/562), and [add lp and rp](https://github.com/nushell/engine-q/pull/518) 
- elferherrera created [vi mode](https://github.com/nushell/engine-q/pull/561), and [missing df command](https://github.com/nushell/engine-q/pull/549), and [sort env vars](https://github.com/nushell/engine-q/pull/544), and [Dataframe commands](https://github.com/nushell/engine-q/pull/542), and [nothing variable](https://github.com/nushell/engine-q/pull/527), and [command name change](https://github.com/nushell/engine-q/pull/526), and [Plugin signature](https://github.com/nushell/engine-q/pull/520), and [Plugin option for shell](https://github.com/nushell/engine-q/pull/517), and [Calling plugin without shell](https://github.com/nushell/engine-q/pull/516), and [Migration of series commands](https://github.com/nushell/engine-q/pull/515) 
- matthewauld [ported compact command to engine-q](https://github.com/nushell/engine-q/pull/558) 
- stormasm [added in a raw flag in the command to json](https://github.com/nushell/engine-q/pull/555), and [add in a new command called columns](https://github.com/nushell/engine-q/pull/519) 
- kubouch [added environment variables doc page](https://github.com/nushell/engine-q/pull/554), and [Interpret lists as series of args for externals](https://github.com/nushell/engine-q/pull/550), and [Do not require both `from_string` and `to_string` in `env_conversions`](https://github.com/nushell/engine-q/pull/548), and [Wrap captured env var names into quotes as well](https://github.com/nushell/engine-q/pull/546), and [Fix capturing environment variables with " or '](https://github.com/nushell/engine-q/pull/537) 
- onthebridgetonowhere [added skip-empty flag to lines command](https://github.com/nushell/engine-q/pull/543), and [port empty command](https://github.com/nushell/engine-q/pull/528) 
- jaeheonji created [feat(into): add into-bool command](https://github.com/nushell/engine-q/pull/499) 

## reedline

- jt fixed [Minor history issue](https://github.com/nushell/reedline/pull/210), and added [Another multiline decode](https://github.com/nushell/reedline/pull/209), and [Multiline fixes](https://github.com/nushell/reedline/pull/208), and [Simple multiline history](https://github.com/nushell/reedline/pull/207), and [Adjust prompt position after paste](https://github.com/nushell/reedline/pull/206), and [Complete to the latest history](https://github.com/nushell/reedline/pull/204), and [Add a history-specific completer](https://github.com/nushell/reedline/pull/203), and [Apply history on tab](https://github.com/nushell/reedline/pull/202) 
- elferherrera created [defining paste event](https://github.com/nushell/reedline/pull/205) 
- sholderbach [disabled raw mode with `Drop` for panics](https://github.com/nushell/reedline/pull/201), and [Remove additional line on line clear via Ctrl-C](https://github.com/nushell/reedline/pull/200), and [Attempt at consolidating offset calculations and streamlining the painting](https://github.com/nushell/reedline/pull/164) 

