## Prereqs
1. Download cljs.jar and put in `./`

## Build Locally
1. Build the `/out` dir: `java -cp cljs.jar:src clojure.main build.clj`
1a. Or auto-build: `java -cp cljs.jar:src clojure.main watch.clj`

## Build Repl

1. `brew install rlwrap`
2. `rlwrap java -cp cljs.jar:src clojure.main repl.clj`

## Build for Release

1. `java -cp cljs.jar:src clojure.main release.clj`

## Build for Node

1. `npm install`
2. `java -cp cljs.jar:src clojure.main node.clj`
3. `node main.js`
4. For watch mode, `rlwrap java -cp cljs.jar:src clojure.main node_repl.clj`
