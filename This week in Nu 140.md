# This week in Nushell #140

## Nushell

- rgwood created [Faster CI](https://github.com/nushell/nushell/pull/5374), and [rust-cache fix](https://github.com/nushell/nushell/pull/5359), and [CI: remove rust-cache from virtualenv tests](https://github.com/nushell/nushell/pull/5358), and [CI: make Clippy reuse build artifacts, other cleanup](https://github.com/nushell/nushell/pull/5357), and [CI: enable rust-cache, remove minimal](https://github.com/nushell/nushell/pull/5354), and [Openssl feature](https://github.com/nushell/nushell/pull/5352), and [Statically link OpenSSL](https://github.com/nushell/nushell/pull/5349), and [`db info` tweaks](https://github.com/nushell/nushell/pull/5338), and [Add watch command](https://github.com/nushell/nushell/pull/5331), and [Move print_pipeline_data() to nu-protocol](https://github.com/nushell/nushell/pull/5328) 
- fdncred [fixed an issue with an empty selector panic](https://github.com/nushell/nushell/pull/5345), and [`db info` command](https://github.com/nushell/nushell/pull/5335), and [add database feature to extra](https://github.com/nushell/nushell/pull/5322), and [update build status badge](https://github.com/nushell/nushell/pull/5321), and [update contrib to max=500](https://github.com/nushell/nushell/pull/5317), and [consolidate shell integration behind config setting](https://github.com/nushell/nushell/pull/5302) 
- uasi [avoided using time conversion methods that may panic](https://github.com/nushell/nushell/pull/5365) 
- stormasm created [cleanup version command and add in database feature](https://github.com/nushell/nushell/pull/5356), and [mute false import warning for nu-command test where_](https://github.com/nushell/nushell/pull/5350) 
- jmoore34 [changed description of `sort`](https://github.com/nushell/nushell/pull/5355) 
- efx [improved inc plugin docs](https://github.com/nushell/nushell/pull/5346) 
- elferherrera added [Database commands](https://github.com/nushell/nushell/pull/5343), and [Database commands](https://github.com/nushell/nushell/pull/5307) 
- jt [fixed 'range' range exclusive](https://github.com/nushell/nushell/pull/5334), and [Allow bare words to interpolate](https://github.com/nushell/nushell/pull/5327), and [Warn if we see let config = ..](https://github.com/nushell/nushell/pull/5318) 
- gipsyh [fixed use of `export/alias --help` bug](https://github.com/nushell/nushell/pull/5332) 
- xgillard created [activates optional trim in 'from csv' and 'from tsv'](https://github.com/nushell/nushell/pull/5326) 
- merelymyself [allowed cd (and other commands that depend on current working directory) to use path of type '~user'](https://github.com/nushell/nushell/pull/5323), and [Adding ~user tilde recognition in file paths](https://github.com/nushell/nushell/pull/5251) 
- Tropid created [Fuzzy completion matching](https://github.com/nushell/nushell/pull/5320) 
- jokeyrhyme [fixed: remove `println!()` from `exec` builtin](https://github.com/nushell/nushell/pull/5311) 
- herlon214 created [nu-command/filesystem: remove newline from cd path](https://github.com/nushell/nushell/pull/5310)

## Documentation

- merelymyself [changed the confusing title of "Working With Strings"](https://github.com/nushell/nushell.github.io/pull/424) 
- hustcer created [More proofreading work for the zh-CN translations](https://github.com/nushell/nushell.github.io/pull/422), and [Fix some broken links](https://github.com/nushell/nushell.github.io/pull/421), and [Some proofreading work for zh-CN translations](https://github.com/nushell/nushell.github.io/pull/420), and [Update zh-CN translations to the latest english version of commit: b6c91cabfa](https://github.com/nushell/nushell.github.io/pull/419), and [Update some node modules](https://github.com/nushell/nushell.github.io/pull/417), and [Translate dataframes.md to zh-CN from commit: 92fb0ac2c](https://github.com/nushell/nushell.github.io/pull/415) 
- Yethal [updated working_with_tables.md](https://github.com/nushell/nushell.github.io/pull/418) 
- morzel85 [updated loading_data.md](https://github.com/nushell/nushell.github.io/pull/416) 

## Nu_Scripts

- fdncred created [update type-o for windows](https://github.com/nushell/nu_scripts/pull/213), and [use $nu.os-info vs (sys).host for speed](https://github.com/nushell/nu_scripts/pull/212) 
