# Effect of contacts on spin lifetime measurements in graphene

**Preprint / Draft**

## Requirements

- `xelatex`, [`latexmk`](http://www.ctan.org/pkg/latexmk/),
  and [`latexpand`](http://www.ctan.org/pkg/latexpand/)
  packaged with a modern LaTeX distribution,
  e.g., [TeX Live](http://www.tug.org/texlive/).
- [Bower](http://bower.io/) available via
  [Node Packaged Modules](https://npmjs.org/)
- [Ruby 2](https://www.ruby-lang.org/)
  with [Bundler](http://bundler.io/) (optional).

To fetch and install dependencies, e.g. the bib files containing the references, run

````bash
$ bower install
````

## Building

### With Ruby

If you have Ruby with Bundler, install the needed gems with

````bash
$ bundle
````

To build all targets,

````bash
$ rake
````

Output files will be saved in the `build` directory.

To see other rake tasks,

````bash
$ rake -D
````

You can run

````bash
$ guard
````

which will automatically rebuild on changes.

### Without Ruby

To build the tex source,

````bash
$ cd tex
$ latexmk -xelatex aps-spin-lifetime.tex
````

## License

This work has been submitted to Physical Review B and is Copyright © 2014 by the American Physical Society.

## Warranty

This software is provided "as is" and without any express or
implied warranties, including, without limitation, the implied
warranties of merchantibility and fitness for a particular
purpose.
