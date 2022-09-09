# language-ocaml package

A quick and dirty fix to get basic syntax highlighting in OCaml, as I was out of luck with the existing packages.  

That said! I really didn't make any of this! I closely referenced https://github.com/atom/language-make/blob/master/grammars/makefile.cson
for the generic directory structure, and then I took the grammar def (.cson) from https://github.com/atom-ocaml/language-ocaml-fix
and magically, everything ended up working as much as I needed it to.  

The language-ocaml-fix package wasn't building successfully when I sought to install it on Atom normally, hence the creation
of this repo here. I figured starting from a skeleton baseline and working my way forward would yield better results
than attempting to fork and revise the existing repo.  
