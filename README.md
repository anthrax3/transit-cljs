# transit-cljs

## Dependencies

Install dependencies with

```
lein deps
```

## Running the tests & benchmarks

Running the tests:

```
lein cljsbuild once test
open index.html
```

In order to run the `bin/verify` tests you must first build the
roundtrip file:

```
lein cljsbuild once roundtrip
```

Running the benchmarks:

```
lein cljsbuild once bench
node target/transit.bench.js
```

## Copyright and License

Copyright © 2014 Cognitect

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
