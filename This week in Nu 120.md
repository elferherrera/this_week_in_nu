# This week in Nushell #120

## Nushell

- 0323pin [fixed build on NetBSD](https://github.com/nushell/nushell/pull/4192)
- hustcer [fixed `into column_path` to `into column-path` (breaking change) (#4185)](https://github.com/nushell/nushell/pull/4189)
- jt [release 0.41](https://github.com/nushell/nushell/pull/4187)
- waldyrious [fixed Configuration section in bug report template](https://github.com/nushell/nushell/pull/4181)
- ahouts [fixed unnecessary allocation](https://github.com/nushell/nushell/pull/4178)
- closetool [fixed implicit coercion of boolean false and empty value #4094](https://github.com/nushell/nushell/pull/4120)

## Nu_Scripts

- fdncred [added timed_weather_run to run get_weather at interval](https://github.com/nushell/nu_scripts/pull/114), and [fixed weather script so it's outputting structured data appropriately.](https://github.com/nushell/nu_scripts/pull/113), and [removed a debug comment](https://github.com/nushell/nu_scripts/pull/112), and add [kind of a radar looking thing that draws stars](https://github.com/nushell/nu_scripts/pull/111)
- Yethal [added docker scripts](https://github.com/nushell/nu_scripts/pull/110)

## engine-q

- luccasmmg [added zip-support to extra](https://github.com/nushell/engine-q/pull/462), and [`To html` and `to md`](https://github.com/nushell/engine-q/pull/453)
- fdncred [fixed 1 off table wrapping for help commands](https://github.com/nushell/engine-q/pull/460), and [updated to latest reedline, change config point name, enable output without ansi](https://github.com/nushell/engine-q/pull/458), and added [filesize formatting](https://github.com/nushell/engine-q/pull/456), and added ability to  [optionally remove table output color](https://github.com/nushell/engine-q/pull/455), and [added default-run so cargo r works](https://github.com/nushell/engine-q/pull/451), and [allowed decimals/floats to be formatted with precision](https://github.com/nushell/engine-q/pull/449), and [enabled `cargo build --features=extra` to build plugins](https://github.com/nushell/engine-q/pull/448), and [introduced `gstat`, a new command to get the git status](https://github.com/nushell/engine-q/pull/443)
- elferherrera created [dataframe commands name](https://github.com/nushell/engine-q/pull/457), and added a [batch of dataframe commands](https://github.com/nushell/engine-q/pull/442), and [corrected missing shellerror type](https://github.com/nushell/engine-q/pull/439), and [improved labeled error from plugins](https://github.com/nushell/engine-q/pull/437), and [removed unwraps with clippy check](https://github.com/nushell/engine-q/pull/430)
- stormasm [ported over the nth command from nushell](https://github.com/nushell/engine-q/pull/454), and [ported over the prepend command from nushell](https://github.com/nushell/engine-q/pull/446), and [ported over the reject command from nushell](https://github.com/nushell/engine-q/pull/419)
- jaeheonji [ported `network/url` command](https://github.com/nushell/engine-q/pull/452), and [added random-integer and random-uuid](https://github.com/nushell/engine-q/pull/440), and [added random-dice](https://github.com/nushell/engine-q/pull/428)
- onthebridgetonowhere [ported uniq](https://github.com/nushell/engine-q/pull/447), and added [cal command](https://github.com/nushell/engine-q/pull/429), and [ported str datetime to into datetime](https://github.com/nushell/engine-q/pull/424)
- jt [update clippy to check all features](https://github.com/nushell/engine-q/pull/441), and [improved running main](https://github.com/nushell/engine-q/pull/431), and [added simple commandline args for scripts](https://github.com/nushell/engine-q/pull/427), and [fixed the failure if the prompt breaks](https://github.com/nushell/engine-q/pull/426), and [reset ansi mode more often when showing errors](https://github.com/nushell/engine-q/pull/425)
- kubouch [added signature to $scope.commands](https://github.com/nushell/engine-q/pull/434)

## reedline

- fdncred [added the ability to optionally turn off ansi coloring](https://github.com/nushell/reedline/pull/197)
