# Frontend Systems Checklist

## Requirements

- Define latency, throughput, memory and frame budgets before implementation.
- Identify burst, reconnect, stale-data, stale-tab and offline behavior.
- Keep state ownership explicit between server state, event state and UI state.
- Bound untrusted event volume and apply backpressure.
- Use virtualization only with stable row identities and predictable heights.
- Preserve keyboard operation and accessible announcements under rapid updates.

## Proof

Include a benchmark, architecture diagram, failure tests, accessibility report and browser matrix. Separate synthetic stress data from production claims.