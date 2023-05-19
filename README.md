# y7 stty

Terminal initialization for
[y7](https://codeberg.org/datatravelandexperiments/y7).

Looks for a `stty` configuration file, typically under `$XDG_CONFIG_HOME`.
This should contain key value pairs, one per line.

Keys where the value is a character:

- `erase`
- `kill`
- `intr`
- `quit`
- `eof`
- `susp`
- `lnext`
- `reprint`
- `werase`
- `status`
- `discard`

Keys where the value is 0 or 1:

- `altwerase`
- `kerninfo`
