Vim Clojure Conceal
===================

This is a fork of [Filip Wolanski's vim-clojure-conceal](https://github.com/fwolanski/vim-clojure-conceal)
that pendantically asserts the difference between anonymous functions (lambdas) and named functions.

The plugin conceals anonymous function keywords (`#` and `fn`) with `λ`, instantly imparting an impressive
amount of sci-fi awesomeness to your code.

For example:

```clojure
  (fn [x]
    (* x x))
```

becomes:

```clojure
  (λ [x]
    (* x x))
```

It requires at least Vim 7.3 and a unicode font.

Installation
============

Drop clojure.vim to `~/.vim/after/syntax` (Linux/Mac OS X/BSD) or
`~/vimfiles/after/syntax` folder (Windows). Or install with pathogen or vundle
in the usual way.

License
=======

Copyright (c) Filip Wolanski. Distributed under the same terms as Vim itself.
See `:help license`.
