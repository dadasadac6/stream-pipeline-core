# Stream Pipeline Core

High-throughput telemetry event streaming pipeline and latency diagnostics.

## Overview

Runs scheduled headless telemetry benchmarks across distributed edge nodes to assess network reachability, response headers, and availability anomalies.

## Usage

```bash
npm start
```

## Telemetry Metrics

Metrics are output to `metrics/telemetry-metrics.json` containing:
- Latency benchmarks (ms)
- Status code validations
- Synthetic suggestion payload size & response distributions

## License

MIT
