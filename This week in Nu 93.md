# This week in Nushell #93

## Nushell

- jonathandturner [added more fixes for bigint duration](https://github.com/nushell/nushell/pull/3557), [switched duration back to bigint](https://github.com/nushell/nushell/pull/3554), [bumped to 0.32.1](https://github.com/nushell/nushell/pull/3553), [finished removing arg deserialization](https://github.com/nushell/nushell/pull/3552), [retained tag when accessing a var](https://github.com/nushell/nushell/pull/3535), [updateed Cargo.lock](https://github.com/nushell/nushell/pull/3527), [update Cargo.toml for nu-pretty-hex](https://github.com/nushell/nushell/pull/3526), [released to 0.32](https://github.com/nushell/nushell/pull/3521), and [autogenerate missing docs](https://github.com/nushell/nushell/pull/3514) 
- efx [ported group-by date to engine-p](https://github.com/nushell/nushell/pull/3556) 
- inet56 created [README: output from -> output to](https://github.com/nushell/nushell/pull/3550) 
- fdncred [added list of installed plugins to version command](https://github.com/nushell/nushell/pull/3548), [accommodated decimals when converting gjson numbers](https://github.com/nushell/nushell/pull/3544), and [fixed the prompt](https://github.com/nushell/nushell/pull/3539) 
- stepnivlk [fixed VCS markers not showing up in textview](https://github.com/nushell/nushell/pull/3530) 
- Garfield96 created [from sqlite: Add parameter --tables](https://github.com/nushell/nushell/pull/3529), [bumped rusqlite from 0.24.2 to 0.25.3](https://github.com/nushell/nushell/pull/3523), and [to sqlite: Fix panic caused by empty input tables](https://github.com/nushell/nushell/pull/3522) 
- ahkrr created [fix: filename quoting #  and update and unify surf dependency](https://github.com/nushell/nushell/pull/3524), and [feat: add attribute selection to nu_plugion_selector](https://github.com/nushell/nushell/pull/3519) 
- andrasio [ensured correct partial key=value flag.](https://github.com/nushell/nushell/pull/3518), and [added support for key=value named flag support.](https://github.com/nushell/nushell/pull/3515) 
- lily-mara [resolved issues with `rm *` globbing](https://github.com/nushell/nushell/pull/3516) 
- elferherrera [added dataframe commands](https://github.com/nushell/nushell/pull/3502) 

## Extension

- fdncred [updated for nushell 0.32.0](https://github.com/nushell/vscode-nushell-lang/pull/33) 

## Documentation

- jonathandturner [updated starship info](https://github.com/nushell/nushell.github.io/pull/143), [added 0.32 blog](https://github.com/nushell/nushell.github.io/pull/140), [updated config.js](https://github.com/nushell/nushell.github.io/pull/136), [updated ToC](https://github.com/nushell/nushell.github.io/pull/135),  [updated text and examples for 0.32](https://github.com/nushell/nushell.github.io/pull/134), and [Add/update command docs](https://github.com/nushell/nushell.github.io/pull/133) 
- LovecraftianHorror fixed [a minor nit fixes](https://github.com/nushell/nushell.github.io/pull/141) 
- andrasio created [variables_y_subexpresiones.md](https://github.com/nushell/nushell.github.io/pull/138), and [actualización: matemáticas.md](https://github.com/nushell/nushell.github.io/pull/137) 

## Nu_Scripts

- fdncred created [several attempts at making a test script faster](https://github.com/nushell/nu_scripts/pull/59), [updated gradient for better nushell comparisons](https://github.com/nushell/nu_scripts/pull/58), [added script to partially generate tmLanguage settings for extension](https://github.com/nushell/nu_scripts/pull/57), and [added for to some scripts](https://github.com/nushell/nu_scripts/pull/56) 

