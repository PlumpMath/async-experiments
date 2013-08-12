# async-experiments

A series of ClojureScript experiments with core.async.

## Usage

Clone the [core.async](http://github.com/clojure/core.async) to a
convenient location. `cd` into the repo and run `lein install`.

Then clone this repo into a convenient location and `cd` into it.

You can build all of the examples from the project directory
with:

```
lein cljsbuild once NAME
```

Or if you want to modify the examples try the following for
faster builds:

```
lein cljsbuild auto NAME
```

You can see `project.clj` for the names of the different examples. All
of the examples can be run after building by opening
`NAME.html`.

## License

Copyright � 2013 Jan Herich

Distributed under the Eclipse Public License, the same as Clojure.
