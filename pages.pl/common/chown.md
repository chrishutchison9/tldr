# chown

> Zmienia właściciela i grupę właścicieli dla plików i katalogów.
> Więcej informacji: <https://www.gnu.org/software/coreutils/manual/html_node/chown-invocation.html>.

- Zmień właściciela pliku/katalogu:

`chown {{użytkownik}} {{ścieżka/do/pliku_lub_katalogu}}`

- Zmień właściciela i grupę właścicieli pliku/katalogu:

`chown {{użytkownik}}:{{grupa}} {{ścieżka/do/pliku_lub_katalogu}}`

- Rekursywnie zmień właściciela katalogu i jego zawartości:

`chown {{[-R|--recursive]}} {{użytkownik}} {{ścieżka/do/katalogu}}`

- Zmień właściciela dowiązania symbolicznego:

`chown {{[-h|--no-dereference]}} {{użytkownik}} {{ścieżka/do/dowiązania_symbolicznego}}`

- Zmień właściciela pliku/katalogu by był taki sam jak w pliku referencyjnym:

`chown --reference {{ścieżka/do/pliku_referencyjnego}} {{ścieżka/do/pliku_lub_katalogu}}`
