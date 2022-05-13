# This week in Nushell #142

## Nushell


- WindSoilder [updated rename](https://github.com/nushell/nushell/pull/5534), and [Implement histogram command](https://github.com/nushell/nushell/pull/5518), and [keep metadata while format filesize](https://github.com/nushell/nushell/pull/5502), and [add format filesize](https://github.com/nushell/nushell/pull/5498), and [Document out positional argument type in help message](https://github.com/nushell/nushell/pull/5461)
- rgwood created [More CI work](https://github.com/nushell/nushell/pull/5527), and [Change history menu keybinding from ctrl+x to ctrl+r](https://github.com/nushell/nushell/pull/5507), and [Enable converting dates to ints](https://github.com/nushell/nushell/pull/5489), and [Parse timestamps as UTC by default](https://github.com/nushell/nushell/pull/5488), and [Display range values better](https://github.com/nushell/nushell/pull/5487), and [Handle int input in `into datetime`](https://github.com/nushell/nushell/pull/5484)
- herlon214 fixed [nu-command/filesystem: fix rm .sock file](https://github.com/nushell/nushell/pull/5524), and [nu-cli/completions: verify case for matching dir, .nu, file and command](https://github.com/nushell/nushell/pull/5506), and [nu-cli/completions: add variable completions test + refactor tests](https://github.com/nushell/nushell/pull/5504), and [nu-cli/completions: add tests for dotnu completions](https://github.com/nushell/nushell/pull/5460)
- fdncred [added the ability to change table mode when running script](https://github.com/nushell/nushell/pull/5520), and [add `--table_mode` `-m` parameter](https://github.com/nushell/nushell/pull/5513), and [refactor for legibility](https://github.com/nushell/nushell/pull/5503), and [adjust where prompt markers go](https://github.com/nushell/nushell/pull/5491)
- CozyPenguin [bumped umask crate to 2.0.0](https://github.com/nushell/nushell/pull/5514)
- Kangaxx-0 [added verbose](https://github.com/nushell/nushell/pull/5512), and [Add feedback to cp](https://github.com/nushell/nushell/pull/5482)
- hustcer [added `tutor list` support, remove tutor `engine-q`, fix: #4950](https://github.com/nushell/nushell/pull/5511), and [Fix #3899, make `mv` and `rm` to be quiet by default](https://github.com/nushell/nushell/pull/5501), and [opt: improve ls by call get_file_type only one time](https://github.com/nushell/nushell/pull/5500), and [Improve #4975 of filtering `ls` output by size issue](https://github.com/nushell/nushell/pull/5494), and [Fix #5469, making $nothing or null convert to filesize of 0B](https://github.com/nushell/nushell/pull/5485), and [Fix `to csv` and `to tsv` for simple list, close: #4780](https://github.com/nushell/nushell/pull/5483)
- jmoore34 [updated comment in default_config.nu [skip ci]](https://github.com/nushell/nushell/pull/5496)
- merelymyself [added fix for when multiple flags are in one line.](https://github.com/nushell/nushell/pull/5493), and [Fixing the flag issue](https://github.com/nushell/nushell/pull/5447)
- pejato [made $nothing | into string == ""](https://github.com/nushell/nushell/pull/5490)
- jt [allowed hooks to be lists of blocks](https://github.com/nushell/nushell/pull/5480), and [Add hooks to cli/repl](https://github.com/nushell/nushell/pull/5479)
- kubouch [added Nushell REPL simulator; Fix bug in overlay add](https://github.com/nushell/nushell/pull/5478)
- elferherrera [joined and from derived tables](https://github.com/nushell/nushell/pull/5477)
- PurityLake [made a change to completion resolution order](https://github.com/nushell/nushell/pull/5440)

## Documentation

- TaKO8Ki [translated `/ja/README.md` to Japanese](https://github.com/nushell/nushell.github.io/pull/436)

## Nu_Scripts

- drbrain [allowed relative entries in CDPATH](https://github.com/nushell/nu_scripts/pull/216)

## reedline

- sadmac7000 [fixed vi-mode word motions](https://github.com/nushell/reedline/pull/425)
