# write

> Write a message on the terminal of a specified logged in user (`<Ctrl c>` to stop writing messages).
> Use the `who` command to find out all terminal_ids of all active users active on the system.
> See also: `mesg`.
> More information: <https://manned.org/write.1p>.

- Send a message to a given user on a given terminal ID:

`write {{username}} {{terminal_id}}`

- Send message to "testuser" on terminal `/dev/tty/5`:

`write {{testuser}} {{tty/5}}`

- Send message to "johndoe" on pseudo terminal `/dev/pts/5`:

`write {{johndoe}} {{pts/5}}`
