# This week in Nushell #101

## Nushell

- fdncred [fixed interpolated strings when using unicode](https://github.com/nushell/nushell/pull/3866), [added performance metrics for measuring startup time](https://github.com/nushell/nushell/pull/3854), and [added the ability to compare time units like 1hr < 2hr](https://github.com/nushell/nushell/pull/3845), and [change describe so it doesn't output colored strings](https://github.com/nushell/nushell/pull/3832) 
- jt [fixed clippy lint and disable broken lint](https://github.com/nushell/nushell/pull/3865), [added named positionals to all](https://github.com/nushell/nushell/pull/3863), and [bumped to 0.34.1](https://github.com/nushell/nushell/pull/3835) 
- elferherrera improved [the existing dataframe support to handle more data types](https://github.com/nushell/nushell/pull/3864), [removed dependencies](https://github.com/nushell/nushell/pull/3853), added [append dataframes](https://github.com/nushell/nushell/pull/3839), and further [extended dataframe support](https://github.com/nushell/nushell/pull/3812) 
- efx [documented no openssl building](https://github.com/nushell/nushell/pull/3862) 
- realcundo [fixed select to insert nulls in sparse tables instead of ignoring absent values](https://github.com/nushell/nushell/pull/3857), [improved md5 and sha256 code](https://github.com/nushell/nushell/pull/3841), and [added sha256 to the hash command](https://github.com/nushell/nushell/pull/3836) 
- therealprof [unified use of the `surf` crate](https://github.com/nushell/nushell/pull/3855) 
- margguo [updated implementing_a_command.md](https://github.com/nushell/nushell/pull/3848) 
- zkat [switched to using chrono_humanize for datetime formatting](https://github.com/nushell/nushell/pull/3834), and [added `date humanize` command](https://github.com/nushell/nushell/pull/3833) 
- nathom [fixed wrong path separator](https://github.com/nushell/nushell/pull/3829) 
- kubouch added [support for other variables than PATH in pathvar (2nd attempt)](https://github.com/nushell/nushell/pull/3828) 
- jafriyie1 [added parse fix for power operator error on negative integers and de…](https://github.com/nushell/nushell/pull/3821) 
- soumil-07 added the [ability to read from standard input in `rm`](https://github.com/nushell/nushell/pull/3763) 

## Documentation

- prrao87 [fixed typos + minor style changes](https://github.com/nushell/nushell.github.io/pull/176) 
- yaahc [updated book mentions of edit_mode to use proper path](https://github.com/nushell/nushell.github.io/pull/175) 

## Wasm

- jt updated the wasm demo to the latest

## Nu_Scripts

- naefl [updated script for Windows compat](https://github.com/nushell/nu_scripts/pull/80), and [added fuzzy commands](https://github.com/nushell/nu_scripts/pull/79) 
- zkat created [readme for with_externals](https://github.com/nushell/nu_scripts/pull/78), [added parse dates into datetimes](https://github.com/nushell/nu_scripts/pull/77), and [added loc.nu](https://github.com/nushell/nu_scripts/pull/76) 

