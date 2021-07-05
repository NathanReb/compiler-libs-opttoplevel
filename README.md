# compiler-libs-opttoplevel

This opam packages only install META files for OCaml's native toplevel, assuming
your ocaml installation does ship `ocamlopttoplevel.cmxa`. This will allow you
to use the native toplevel library in your dune projects.

To install in your current switch, simply run:
```
opam pin add compiler-libs-opttoplevel.dev git+https://github.com/NathanReb/compiler-libs-opttoplevel.git
```
