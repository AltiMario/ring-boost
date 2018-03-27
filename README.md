# ring-boost
[![Clojars Project](https://img.shields.io/clojars/v/com.brunobonacci/ring-boost.svg)](https://clojars.org/com.brunobonacci/ring-boost) ![CircleCi](https://img.shields.io/circleci/project/BrunoBonacci/ring-boost.svg) ![last-commit](https://img.shields.io/github/last-commit/BrunoBonacci/ring-boost.svg) [![Dependencies Status](https://jarkeeper.com/BrunoBonacci/safely/status.svg)](https://jarkeeper.com/BrunoBonacci/ring-boost)

I library to boost performances of Clojure web applications with off-heap serverside caching.

## Usage

In order to use the library add the dependency to your `project.clj`

``` clojure
[com.brunobonacci/ring-boost "0.1.0-SNAPSHOT"]
```

Current version: [![Clojars Project](https://img.shields.io/clojars/v/com.brunobonacci/ring-boost.svg)](https://clojars.org/com.brunobonacci/ring-boost)


Then require the namespace:

``` clojure
(ns foo.bar
  (:require [com.brunobonacci.ring-boost :as x]))
```

Then it's up to you...

## License

Copyright © 2018 Bruno Bonacci - Distributed under the Apache License v 2.0 (http://www.apache.org/licenses/LICENSE-2.0)
