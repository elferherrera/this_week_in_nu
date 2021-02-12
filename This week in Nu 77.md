# This week in Nu #77

## Documentation and samples
* More scripts were added to the [Nushell script collection](https://github.com/nushell/nu_scripts)
* fdncred landed updates to the [config documentation in the book](https://github.com/nushell/nushell.github.io/pull/92), commented [table_mode](https://github.com/nushell/nushell/pull/3036) and [more comments on config](https://github.com/nushell/nushell/pull/3040/files), and more [config updates](https://github.com/nushell/nushell/pull/3044)
* ibraheemdev improved the [website ci deployment](https://github.com/nushell/nushell.github.io/pull/96)
* LhKipp updated the [sample config](https://github.com/nushell/nushell/pull/3031)
* Andy-Python-Programmer fixed a [typo in the README](https://github.com/nushell/nushell/pull/3013)

## Nushell base
* jonathandturner updated [some dependencies](https://github.com/nushell/nushell/pull/3011), fixed the [Rust 1.50 clippy warnings](https://github.com/nushell/nushell/pull/3049)
* andrasio prevented [selecting the same column twice](https://github.com/nushell/nushell/pull/3012), improved [coercions for column-path](https://github.com/nushell/nushell/pull/3016)
* Qwanve fixed `ps` output [when the process doesn't have a parent](https://github.com/nushell/nushell/pull/3015)
* ilius extended `which` [to allow for multiple applications to be passed](https://github.com/nushell/nushell/pull/3024), added [reverse to `sort-by`](https://github.com/nushell/nushell/pull/3025), did some [formatting and clean-up of nu-parser](https://github.com/nushell/nushell/pull/3033), switched to [metric/standard filesizes](https://github.com/nushell/nushell/pull/3035), added a way [to switch to metric filesizes](https://github.com/nushell/nushell/pull/3045), improved the [serialization conversion for column-path](https://github.com/nushell/nushell/pull/3048)
* fdncred added a new [`term size` command](https://github.com/nushell/nushell/pull/3038)
* ammkrn changed [boolean to true/false instead of Yes/No](https://github.com/nushell/nushell/pull/3043)
* stormasm renamed [internal parsing functions](https://github.com/nushell/nushell/pull/3047)
