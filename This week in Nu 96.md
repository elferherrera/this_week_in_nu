# This week in Nushell #96

## Nushell

- jt [added support for arbitrarily nested subcommands](https://github.com/nushell/nushell/pull/3688), [made lexing configurable wrt newlines](https://github.com/nushell/nushell/pull/3682), [improved def parse errors](https://github.com/nushell/nushell/pull/3681), [fixed textview to always read input from stream](https://github.com/nushell/nushell/pull/3680), [enabled dataframe command by default](https://github.com/nushell/nushell/pull/3672), and [released 0.33](https://github.com/nushell/nushell/pull/3667), [added built-in var to refer to pipeline values](https://github.com/nushell/nushell/pull/3661), and [began directory contrib docs and split commands](https://github.com/nushell/nushell/pull/3650) 
- voanhduy1512 [fixed string interpolation is not working with external command](https://github.com/nushell/nushell/pull/3686) 
- efx created [documentation: consistent abbreviation for URL](https://github.com/nushell/nushell/pull/3684), and [port str case conversions to engine-p](https://github.com/nushell/nushell/pull/3649) 
- elferherrera [removed infer schema](https://github.com/nushell/nushell/pull/3683), [cleaned column names](https://github.com/nushell/nushell/pull/3678), and [Series commands](https://github.com/nushell/nushell/pull/3652) 
- fdncred [created stale.yml](https://github.com/nushell/nushell/pull/3677), [updated filesize -> filesize math to fix coercion errors](https://github.com/nushell/nushell/pull/3675), [sped up windows completions](https://github.com/nushell/nushell/pull/3665), [updated `main` in table so that it outputs again](https://github.com/nushell/nushell/pull/3662), and [updated/added path separators and environment separators to char](https://github.com/nushell/nushell/pull/3660) 
- stormasm [made nu-cli mod app public](https://github.com/nushell/nushell/pull/3673) 
- nathom [added `pathvar` command](https://github.com/nushell/nushell/pull/3670), and [added `unlet_env` command](https://github.com/nushell/nushell/pull/3629) 
- luccasmmg [fixed panic on math with large durations](https://github.com/nushell/nushell/pull/3669) 
- andrasio [added variable completions](https://github.com/nushell/nushell/pull/3666) 
- NiklasJonsson [moved path handling to nu-path](https://github.com/nushell/nushell/pull/3653) 

## Documentation

- eduardocanellas created [docs(configuration): show `completion_match_method` under `line_editor`](https://github.com/nushell/nushell.github.io/pull/152) 
- autophagy [fixed missing value types for completion_prompt_limit and true_color](https://github.com/nushell/nushell.github.io/pull/151) 
- elferherrera [improved the book layout](https://github.com/nushell/nushell.github.io/pull/150), and [removed config load since it doesnt exist](https://github.com/nushell/nushell.github.io/pull/148) 

## Nu_Scripts

- kubouch [fixed unexpected token error](https://github.com/nushell/nu_scripts/pull/67) 
- fdncred [changed per page count from 30 to 100](https://github.com/nushell/nu_scripts/pull/66) 

