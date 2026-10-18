# Circuit Breaker

Thread-safe circuit breaker with threshold, cooldown and recovery trial.

Python 3.11+; standard library only.

## Run unit tests

```sh
python -m unittest discover -s . -p 'test_core.py' -v
```

`core.py` contains the circuit-breaker implementation with failure threshold, cooldown and recovery trial. `test_core.py` provides an example and unit test. GitHub Actions tests against Python 3.11–3.13.

**Scope:** Educational/reference implementation. Production systems need robust concurrency handling, metrics, configurable recovery strategy and service-specific retry policies.
