# calc

A Template for new Clojure Projects

Dependencies include:

  - [incanter](https://github.com/incanter/incanter)
  - [conjure](https://github.com/Olical/conjure)


## Usage

This is a template project for use with [deps-new](https://github.com/seancorfield/deps-new).
As originally generated, it will produce a new library project when run:

    $ clojure -Sdeps '{:deps {net.clojars.calc/calc {:local/root "."}}}' -Tnew create :template calc/calc :name myusername/mycoollib

Assuming you have installed `deps-new` as your `new` "tool" via:

```bash
clojure -Ttools install io.github.seancorfield/deps-new '{:git/tag "v0.4.12"}' :as new
```

> Note: once the template has been published (to a public git repo), the invocation will be the same, except the `:local/root` dependency will be replaced by a git or Maven-like coordinate.

Run this template project's tests (by default, this just validates your template's `template.edn`
file -- that it is valid EDN and it satisfies the `deps-new` Spec for template files):

    $ clojure -T:build test

## License: MIT

Copyright © 2022 Kolja
