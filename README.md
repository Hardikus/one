# ClojureScript One

The [ClojureScript][] landscape has changed over the past two
years. There are now many great tools and libraries available for
building ClojureScript applications. This project is being updated to
show how to pull some of these tools together to create a well
designed and maintainable ClojureScript application.

The purpose of this project is to help new ClojureScript adopters find
good libraries and show them how to use them effectively.

This is not an attempt to endorse specific libraries or steer you away
from others. There may be better alternatives than what is used
here. This project simply shows how to get started with ClojureScript
using designs, tools and technology which have worked well for us in
the past.

Contributions are welcome.


## Useful ClojureScript libraries

While this work is being done, you may want to check out the following
libraries:


### Tooling

* https://github.com/technomancy/leiningen
* https://github.com/emezeske/lein-cljsbuild
* https://github.com/plexus/chestnut
* https://github.com/bhauman/lein-figwheel


### Client architecture

* https://facebook.github.io/flux/ - not a library
* https://github.com/vitalreactor/derive
* https://github.com/tonsky/datascript
* ??????


### Rendering (React)

* https://github.com/swannodette/om
* https://github.com/levand/quiescent
* https://github.com/reagent-project/reagent


### UI components

* https://github.com/racehub/om-bootstrap


### Async

* https://github.com/clojure/core.async


### Data formats

* https://github.com/cognitect/transit-cljs


### Templates

* https://github.com/ckirkendall/kioo
* https://github.com/teropa/hiccups


## Running

```
lein cljsbuild clean && lein cljsbuild auto
```

and then open the `resources/public/index.html` page in your browser

Or, if you would like to have live reloading

```
lein cljsbuild clean && lein figwheel
```

and then open `http://localhost:3449` in your browser.


## Generating docs

```
lein marg -d doc -f one.html
```

or run

```
bin/docs
```

to generate documentation page for the web site


# License

Copyright © 2012,2014 Brenton Ashworth and Cognitect, Inc

Distributed under the Eclipse Public License, the same as Clojure uses. See the file COPYING.

[ClojureScript]: https://github.com/clojure/clojurescript
[lein]: https://github.com/technomancy/leiningen
[wiki]: https://github.com/brentonashworth/one/wiki
[website]: http://clojurescriptone.com
[issues]: https://github.com/brentonashworth/one/issues
