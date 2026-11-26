# Test Suite

* `src/Unit.gren`: unit tests, using [gren-lang/test](https://packages.gren-lang.org/package/gren-lang/test/version/latest/overview).
* `src/E2E.gren`: browser tests, using [blaix/gren-effectful-tests](https://packages.gren-lang.org/package/blaix/gren-effectful-tests/version/latest/overview).
* `src/Suite.gren`: runs both.

## Running

```
gren run Suite   # everything
gren run Unit    # unit tests only
gren run E2E     # browser tests only
```
