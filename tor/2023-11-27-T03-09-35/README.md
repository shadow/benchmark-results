# 2023-11-27-T03-09-35

| Key | Value |
|-----|-------|
| benchmark-sha | [0affa2fbd5b850d2c4aa1866eb57e35fadd87c77](https://github.com/shadow/benchmark/commit/0affa2fbd5b850d2c4aa1866eb57e35fadd87c77) |
| comment | "Clean up network interface and avoid a hashmap linear search" |
| compare-to | nightly, weekly |
| compare-to-resolved | [2023-11-24-T04-10-08](/tor/2023-11-24-T04-10-08/README.md), [2023-11-25-T04-21-00](/tor/2023-11-25-T04-21-00/README.md) |
| container | debian:bullseye-20230502-slim |
| dry-run | false |
| oniontrace-ref | 3696db43288c8a116e8a1cff42a9c698d1d4ab33 |
| repeat | 1 |
| results-dir | tor |
| runner-label | cora |
| runtime-args | --parallelism 32 |
| rust-version | rustc 1.74.0 (79e9716c9 2023-11-13) |
| shadow-label | PR #3239 |
| shadow-ref | pull/3239/head |
| shadow-sha | [b18b9ef9c6b65974f381d0811b48c35e8cddb1fa](https://github.com/shadow/shadow/commit/b18b9ef9c6b65974f381d0811b48c35e8cddb1fa) |
| sim-id | 2023-11-27-T03-09-35 |
| sim-to-run | tornet-0.15 |
| tgen-ref | 30c95bbe723ebe5e4d068adfd975b094e00dbe10 |
| timestamp | 1701054575 |
| tor-ref | tor-0.4.7.13 |
| tornettools-ref | c240e72bf1dfbe76bb1cfbcca5ecb7d9e2fdfbf9 |
| trigger | workflow_dispatch |
| update-symlink |  |
| workflow-name | Manual Tor Benchmark |

[plots/oniontrace.viz.pdf](plots/oniontrace.viz.pdf)

[plots/shadow.results.pdf](plots/shadow.results.pdf)

[plots/tgen.viz.pdf](plots/tgen.viz.pdf)

[plots/tornet.plot.pages.pdf](plots/tornet.plot.pages.pdf)

![plots/bytes_read_count_timeseries.png](plots/bytes_read_count_timeseries.png)

![plots/bytes_written_count_timeseries.png](plots/bytes_written_count_timeseries.png)

![plots/circuit_build_time.exit.png](plots/circuit_build_time.exit.png)

![plots/client_goodput.exit.png](plots/client_goodput.exit.png)

![plots/client_goodput_5MiB.exit.png](plots/client_goodput_5MiB.exit.png)

![plots/flows_created_count_timeseries.png](plots/flows_created_count_timeseries.png)

![plots/flows_succeeded_count_timeseries.png](plots/flows_succeeded_count_timeseries.png)

![plots/ram_realtime.png](plots/ram_realtime.png)

![plots/ram_simtime.png](plots/ram_simtime.png)

![plots/relay_goodput.png](plots/relay_goodput.png)

![plots/round_trip_time.exit.png](plots/round_trip_time.exit.png)

![plots/run_time.png](plots/run_time.png)

![plots/streams_created_count_timeseries.png](plots/streams_created_count_timeseries.png)

![plots/streams_succeeded_count_timeseries.png](plots/streams_succeeded_count_timeseries.png)

![plots/time_to_first_byte_recv_cdf.png](plots/time_to_first_byte_recv_cdf.png)

![plots/time_to_first_byte_recv_timeseries.png](plots/time_to_first_byte_recv_timeseries.png)

![plots/time_to_last_byte_recv_count_cdf.png](plots/time_to_last_byte_recv_count_cdf.png)

![plots/time_to_last_byte_recv_count_timeseries.png](plots/time_to_last_byte_recv_count_timeseries.png)

![plots/total_flows_pending_count_timeseries.png](plots/total_flows_pending_count_timeseries.png)

![plots/total_streams_pending_count_timeseries.png](plots/total_streams_pending_count_timeseries.png)

![plots/transfer_error_rates_ALL.exit.png](plots/transfer_error_rates_ALL.exit.png)

![plots/transfer_time_1048576.exit.png](plots/transfer_time_1048576.exit.png)

![plots/transfer_time_51200.exit.png](plots/transfer_time_51200.exit.png)

![plots/transfer_time_5242880.exit.png](plots/transfer_time_5242880.exit.png)
