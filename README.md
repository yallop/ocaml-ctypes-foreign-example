An example ocaml-ctypes project that uses the [Foreign][foreign] backend to bind libncurses dynamically.

This is broadly similar to the [example in the OCaml manual][ocaml-manual-curses-example], which binds to libncurses using hand-written stubs.  See [Chapter 19 of Real World OCaml][rwo-chapter-19] for details about the ctypes code in this repository.

[foreign]: http://ocamllabs.github.io/ocaml-ctypes/Foreign.html
[ocaml-manual-curses-example]: http://caml.inria.fr/pub/docs/manual-ocaml-4.00/manual033.html#toc147
[rwo-chapter-19]: https://realworldocaml.org/v1/en/html/foreign-function-interface.html#example-a-terminal-interface