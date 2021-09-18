# This week in Nushell #108

Big news this week - [virtualenv added Nushell support](https://virtualenv.pypa.io/en/latest/changelog.html#v20-8-0-2021-09-16)!

## Nushell

- aminya [fixed enabling SIMD](https://github.com/nushell/nushell/pull/4021) 
- jt created [bump 0.37.1](https://github.com/nushell/nushell/pull/4019), and [temporarily remove the circular dep](https://github.com/nushell/nushell/pull/4009), and [Update main.wxs](https://github.com/nushell/nushell/pull/4007), and [released to 0.37](https://github.com/nushell/nushell/pull/4006) 
- kubouch [moved nu-path tests to integration tests](https://github.com/nushell/nushell/pull/4015), and updated [path commands: Put column path args behid flag; Allow `path join` appending without flag](https://github.com/nushell/nushell/pull/4008), and added [Small fixes and refactors to paths & source command](https://github.com/nushell/nushell/pull/3998) 
- tw4452852 [added command `g` to switch shell quickly](https://github.com/nushell/nushell/pull/4014) 
- elferherrera [updated to polars 0.16](https://github.com/nushell/nushell/pull/4013), and [changed name to PROMPT_COMMAND](https://github.com/nushell/nushell/pull/4003) 
- fdncred [added table selector for downloading web tables](https://github.com/nushell/nushell/pull/4004) 

## engine-q

- jt added [very early proof-of-concept git branch completion](https://github.com/nushell/engine-q/pull/49), and added [block param types](https://github.com/nushell/engine-q/pull/46) 
- elferherrera improved [error check on def and alias](https://github.com/nushell/engine-q/pull/48), and improved [parse errors for def, let and alias](https://github.com/nushell/engine-q/pull/40) 
- stormasm created [more block param and build string tests in concert with lists](https://github.com/nushell/engine-q/pull/47) 
- kubouch [allowed parsing left-unbounded range (..10)](https://github.com/nushell/engine-q/pull/45), [floating point ranges](https://github.com/nushell/engine-q/pull/44), and [added stepping support & reversing to ranges](https://github.com/nushell/engine-q/pull/43) 
