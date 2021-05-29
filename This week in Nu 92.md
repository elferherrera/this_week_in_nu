# This week in Nushell #92

## Nushell

- fdncred [updated keybindings to support new rustyline functionality](https://github.com/nushell/nushell/pull/3511), [removed expect so that loading invalid config doesn't fail](https://github.com/nushell/nushell/pull/3510), [fixed polars compile warnings](https://github.com/nushell/nushell/pull/3501), [removed str from](https://github.com/nushell/nushell/pull/3500), [removed into int references from into binary](https://github.com/nushell/nushell/pull/3499), [added locale for ls size](https://github.com/nushell/nushell/pull/3497), [correctly escape pipe in windows/cmd.exe](https://github.com/nushell/nushell/pull/3489), and [error message cleanup for into string](https://github.com/nushell/nushell/pull/3488) 
- jonathandturner [cleaned up let varname and rhs](https://github.com/nushell/nushell/pull/3507), [fixed for in](https://github.com/nushell/nushell/pull/3506), [added for..in command](https://github.com/nushell/nushell/pull/3504), [allowed aliases to expand and ignore painting outside of lines](https://github.com/nushell/nushell/pull/3492), [fixed bad operator](https://github.com/nushell/nushell/pull/3479), and [let date commands pull default date](https://github.com/nushell/nushell/pull/3463) 
- kubouch [converted "do" command to engine-p & fixed its flag name](https://github.com/nushell/nushell/pull/3503), [fixed path dots expansion](https://github.com/nushell/nushell/pull/3491), [added path separator to `char`; Update char to engine-p; List all names of all possible chars](https://github.com/nushell/nushell/pull/3470), [implemented `path relative-to` subcommand](https://github.com/nushell/nushell/pull/3461) 
- elferherrera created [Dataframe commands](https://github.com/nushell/nushell/pull/3498), and [Groupby operations on dataframes](https://github.com/nushell/nushell/pull/3473), and [Commands to engine](https://github.com/nushell/nushell/pull/3448) 
- lily-mara [added the load-env command](https://github.com/nushell/nushell/pull/3484) 
- andrasio created [Pass command's span correctly when reporting unexpected flags.](https://github.com/nushell/nushell/pull/3478) 
- stepnivlk [added params to `do`](https://github.com/nushell/nushell/pull/3477) 
- LhKipp switched to [use enginep style in enter command](https://github.com/nushell/nushell/pull/3469) 
- henriiik [deleted crates/nu-command/src/commands/date/utc.rs](https://github.com/nushell/nushell/pull/3464), and [updated minimum required rust version](https://github.com/nushell/nushell/pull/3462) 
- efx [ported group-by to engine-p](https://github.com/nushell/nushell/pull/3458) 

## Documentation

- aborruso [added the way to have help on a command subcommand](https://github.com/nushell/nushell.github.io/pull/132) 
- henriiik [updated `sys_get_` examples](https://github.com/nushell/nushell.github.io/pull/131), and [replaced `date utc` with `date now` in introduction](https://github.com/nushell/nushell.github.io/pull/130) 

## Nu_Scripts

- fdncred [updated for 0.32.0 release](https://github.com/nushell/nu_scripts/pull/53) 

