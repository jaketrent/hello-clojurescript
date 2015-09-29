## Build Locally

1. Downlaod cljs.jar and put in `./`
2. Build the `/out` dir: `java -cp cljs.jar:src clojure.main build.clj`
2a. Or auto build: `java -cp cljs.jar:src clojure.main watch.clj`

## Build Repl

1. `brew install rlwrap`
2. `rlwrap java -cp cljs.jar:src clojure.main repl.clj`