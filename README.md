# org.clojars.victorinacio/little-trader-demo

FIXME: my new application.

## Installation

Download from https://github.com/clojars.victorinacio/little-trader-demo

## Usage

FIXME: explanation

Run the project directly, via `:exec-fn`:

    $ clojure -X:run-x
    Hello, Clojure!

Run the project, overriding the name to be greeted:

    $ clojure -X:run-x :name '"Someone"'
    Hello, Someone!

Run the project directly, via `:main-opts` (`-m org.clojars.victorinacio.little-trader-demo`):

    $ clojure -M:run-m
    Hello, World!

Run the project, overriding the name to be greeted:

    $ clojure -M:run-m Via-Main
    Hello, Via-Main!

Run the project's tests (they'll fail until you edit them):

    $ clojure -T:build test

Run the project's CI pipeline and build an uberjar (this will fail until you edit the tests to pass):

    $ clojure -T:build ci

This will produce an updated `pom.xml` file with synchronized dependencies inside the `META-INF`
directory inside `target/classes` and the uberjar in `target`. You can update the version (and SCM tag)
information in generated `pom.xml` by updating `build.clj`.

If you don't want the `pom.xml` file in your project, you can remove it. The `ci` task will
still generate a minimal `pom.xml` as part of the `uber` task, unless you remove `version`
from `build.clj`.

Run that uberjar:

    $ java -jar target/little-trader-demo-0.1.0-SNAPSHOT.jar

If you remove `version` from `build.clj`, the uberjar will become `target/little-trader-demo-standalone.jar`.


## Examples

...


## License

Copyright © 2024 Victorinacio
Distributed under the Eclipse Public License version 1.0.
