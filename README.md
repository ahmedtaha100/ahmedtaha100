# Ahmed Taha

## Research Publications

- **SpineFairBench** — *Coming soon.*
- **MedInsider** — *Coming soon.*

---

## Open Source Contributions

- **[jax-ml/jax #36521](https://github.com/jax-ml/jax/pull/36521)** — Added complex-input support to `jax.scipy.special.gamma` using the Lanczos approximation and reflection formula in Google JAX.
- **[Azure/azure-sdk-for-python #46137](https://github.com/Azure/azure-sdk-for-python/pull/46137)** — Contributed a fix to `azure-data-tables` so `TableClient.list_entities(...)` rejects unsupported `query_filter`/`parameters` usage with a clear SDK-level error instead of leaking kwargs to the transport layer.
- **[Azure/azure-sdk-for-python #46137](https://github.com/Azure/azure-sdk-for-python/pull/46137)** — Fixed an `azure-data-tables` bug ([#46014](https://github.com/Azure/azure-sdk-for-python/issues/46014)) where unsupported `TableClient.list_entities(...)` kwargs leaked into the async transport and surfaced as an `aiohttp` `TypeError`; added early SDK-level validation for `query_filter`/`parameters` with clear guidance to use `query_entities`, plus sync/async regression tests.




