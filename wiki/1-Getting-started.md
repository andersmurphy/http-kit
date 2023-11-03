# Setup

Add the [relevant dependency](../#latest-releases) to your project:

```clojure
Leiningen: [http-kit/http-kit               "x-y-z"] ; or
deps.edn:   http-kit/http-kit {:mvn/version "x-y-z"}
```

# Usage

See the [client](./2-Client) or [server](./3-Server) sections for more!

# Tests and benchmarks

http-kit is hacker friendly: it has zero dependencies, and is only ~3.5k lines of code.

```sh
lein repl        # Run a local REPL
lein test        # Run the unit tests
lein test :bench # Run the benchmark suite with default opts
```

See the [benchmarking](./4-Benchmarking) section for lots more info on http-kit's **benchmark suite**.