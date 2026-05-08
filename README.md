# Ahmed Taha

## Research Publications

- **SpineFairBench: A Counterfactual Benchmark for Auditing Demographic Sensitivity in Spinal Radiology VLM Reports** — Taha, A., Taeha, A., & Ahmadzada, M. (2026). [[Preprint on ResearchGate]](https://www.researchgate.net/publication/404620116_SpineFairBench_A_Counterfactual_Benchmark_for_Auditing_Demographic_Sensitivity_in_Spinal_Radiology_VLM_Reports) [[Code]](https://github.com/ahmedtaha100/SpineFairBench) [[Dataset]](https://huggingface.co/datasets/ahmedtaha100/spinefairbench-artifacts)
- **MedInsider** — *Coming soon.*

---

## Open Source Contributions

- **[jax-ml/jax #36521](https://github.com/jax-ml/jax/pull/36521)** — Added complex-input support to `jax.scipy.special.gamma` using the Lanczos approximation and reflection formula in Google JAX.
- **[Azure/azure-sdk-for-python #46137](https://github.com/Azure/azure-sdk-for-python/pull/46137)** — Fixed an `azure-data-tables` bug ([#46014](https://github.com/Azure/azure-sdk-for-python/issues/46014)) where unsupported `TableClient.list_entities(...)` kwargs leaked into the async transport and surfaced as an `aiohttp` `TypeError`; added early SDK-level validation for `query_filter`/`parameters` with clear guidance to use `query_entities`, plus sync/async regression tests.
- **[Azure/azure-sdk-for-python #46546](https://github.com/Azure/azure-sdk-for-python/pull/46546)** — Submitted a follow-up fix for the broader transport-layer kwargs leak tracked in [#46365](https://github.com/Azure/azure-sdk-for-python/issues/46365), adding built-in transport validation across `azure-core` and `corehttp` so unsupported pipeline kwargs fail clearly before reaching `aiohttp`, `requests`, or `httpx`, while preserving custom transport passthrough.
