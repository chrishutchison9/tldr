# base32

> Encode or decode file or `stdin` to/from Base32, to `stdout`.
> More information: <https://manned.org/base32>.

- Encode a file:

`base32 {{path/to/file}}`

- Wrap encoded output at a specific width (`0` disables wrapping):

`base32 {{[-w|--wrap]}} {{0|76|...}} {{path/to/file}}`

- Decode a file:

`base32 {{[-d|--decode]}} {{path/to/file}}`

- Encode from `stdin`:

`{{command}} | base32`

- Decode from `stdin`:

`{{command}} | base32 {{[-d|--decode]}}`
