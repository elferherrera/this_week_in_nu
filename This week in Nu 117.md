# This week in Nushell #117

## Nushell

- jt [released 0.40](https://github.com/nushell/nushell/pull/4129), and [added 'detect columns' command](https://github.com/nushell/nushell/pull/4127) 
- fdncred [missed from_mp4, added back](https://github.com/nushell/nushell/pull/4128), and [added upx and strip to mac and windows](https://github.com/nushell/nushell/pull/4126), [added upx and strip](https://github.com/nushell/nushell/pull/4125), and [tweaked strip ci](https://github.com/nushell/nushell/pull/4124), and [updated release to allow running manually](https://github.com/nushell/nushell/pull/4123) 
- nmandery [upgraded polars to 0.17](https://github.com/nushell/nushell/pull/4122) 
- leodutra [updated README](https://github.com/nushell/nushell/pull/4118) 
- ahkrr [upgraded dependencies](https://github.com/nushell/nushell/pull/4116) 

## engine-q

- luccasmmg added [`from xlsx` `from ods` and `from toml`](https://github.com/nushell/engine-q/pull/352) 
- jt [added `debug` and `describe`](https://github.com/nushell/engine-q/pull/351), [better record types](https://github.com/nushell/engine-q/pull/350), [expanded globs and filepaths](https://github.com/nushell/engine-q/pull/348), [fixed term width for the table](https://github.com/nushell/engine-q/pull/346), [added support for crlf for line continuations](https://github.com/nushell/engine-q/pull/341), [fixed multiword imports/exports](https://github.com/nushell/engine-q/pull/336), added ['update' command](https://github.com/nushell/engine-q/pull/333), [added a config variable with engine support](https://github.com/nushell/engine-q/pull/332), and [fixed some nightly clippy warnings](https://github.com/nushell/engine-q/pull/329) 
- elferherrera created [plugins signature load](https://github.com/nushell/engine-q/pull/349), and [Category option for signature](https://github.com/nushell/engine-q/pull/343) 
- stormasm [ported over the `append` command from nushell](https://github.com/nushell/engine-q/pull/345), and [deleted row.rs in nu-protocol/value which has references to RowStream](https://github.com/nushell/engine-q/pull/339) 
- kubouch [separated Overlay into its own thing](https://github.com/nushell/engine-q/pull/344), and [added environment variable support for modules](https://github.com/nushell/engine-q/pull/331) 
- onthebridgetonowhere [port `str startswith`](https://github.com/nushell/engine-q/pull/342), and [ported `str reverse`](https://github.com/nushell/engine-q/pull/337), and [ported `str lpad` and `str rpad`](https://github.com/nushell/engine-q/pull/334), and [ported `str length` command](https://github.com/nushell/engine-q/pull/330) 
- fdncred [enabled ls_colors for the `ls` command](https://github.com/nushell/engine-q/pull/340) 
- CBenoit [ported `parse` command](https://github.com/nushell/engine-q/pull/338) 
