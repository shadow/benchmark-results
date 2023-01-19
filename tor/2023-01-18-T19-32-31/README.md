# 2023-01-18-T19-32-31

| Key | Value |
|-----|-------|
| benchmark-sha | 9aea9e28f776f51fb7a478c322efb42711e43ea8 |
| comment | "InetSocket: support in the tracker, and use in the network interface" |
| compare-to | 2022-06-06-T23-09-40, weekly, nightly |
| compare-to-resolved | 2022-06-06-T23-09-40, 2023-01-14-T05-44-29, 2023-01-17-T05-49-51 |
| container | debian:bullseye-20220527-slim |
| dry-run | false |
| oniontrace-ref | f271ead90526b29b3dd7218ce6e56813e3b4dce3 |
| repeat | 1 |
| results-dir | tor |
| runtime-args | --parallelism 24 --use-preload-openssl-crypto true |
| rust-version |  |
| shadow-label | PR #2671 |
| shadow-ref | pull/2671/head |
| shadow-sha | aea735e93704a802f53c9705d29bc21205bbf40e |
| sim-id | 2023-01-18-T19-32-31 |
| sim-to-run | tornet-0.05 |
| tgen-ref | c979b74b031fe92ecea70600c8296c00576fcda7 |
| timestamp | 1674070351 |
| tor-ref | tor-0.4.7.7 |
| tornettools-ref | 5ee84cef2690143f6adf2667d1db9fd5f7d7d3a4 |
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

![plots/circuit_build_time.onionservice.png](plots/circuit_build_time.onionservice.png)

![plots/client_goodput.exit.png](plots/client_goodput.exit.png)

![plots/client_goodput.onionservice.png](plots/client_goodput.onionservice.png)

![plots/client_goodput_5MiB.exit.png](plots/client_goodput_5MiB.exit.png)

![plots/client_goodput_5MiB.onionservice.png](plots/client_goodput_5MiB.onionservice.png)

![plots/errors_TIMEOUT_bytes_cdf.png](plots/errors_TIMEOUT_bytes_cdf.png)

![plots/errors_TIMEOUT_cdf.png](plots/errors_TIMEOUT_cdf.png)

![plots/errors_TIMEOUT_timeseries.png](plots/errors_TIMEOUT_timeseries.png)

![plots/flows_created_count_timeseries.png](plots/flows_created_count_timeseries.png)

![plots/flows_succeeded_count_timeseries.png](plots/flows_succeeded_count_timeseries.png)

![plots/ram_realtime.png](plots/ram_realtime.png)

![plots/ram_simtime.png](plots/ram_simtime.png)

![plots/relay_goodput.png](plots/relay_goodput.png)

![plots/round_trip_time.exit.png](plots/round_trip_time.exit.png)

![plots/round_trip_time.onionservice.png](plots/round_trip_time.onionservice.png)

![plots/run_time.png](plots/run_time.png)

![plots/streams_created_count_timeseries.png](plots/streams_created_count_timeseries.png)

![plots/streams_failed_count_timeseries.png](plots/streams_failed_count_timeseries.png)

![plots/streams_succeeded_count_timeseries.png](plots/streams_succeeded_count_timeseries.png)

![plots/time_to_first_byte_recv_cdf.png](plots/time_to_first_byte_recv_cdf.png)

![plots/time_to_first_byte_recv_timeseries.png](plots/time_to_first_byte_recv_timeseries.png)

![plots/time_to_last_byte_recv_count_cdf.png](plots/time_to_last_byte_recv_count_cdf.png)

![plots/time_to_last_byte_recv_count_timeseries.png](plots/time_to_last_byte_recv_count_timeseries.png)

![plots/total_flows_pending_count_timeseries.png](plots/total_flows_pending_count_timeseries.png)

![plots/total_streams_pending_count_timeseries.png](plots/total_streams_pending_count_timeseries.png)

![plots/transfer_error_rates_ALL.exit.png](plots/transfer_error_rates_ALL.exit.png)

![plots/transfer_error_rates_ALL.onionservice.png](plots/transfer_error_rates_ALL.onionservice.png)

![plots/transfer_time_1048576.exit.png](plots/transfer_time_1048576.exit.png)

![plots/transfer_time_1048576.onionservice.png](plots/transfer_time_1048576.onionservice.png)

![plots/transfer_time_51200.exit.png](plots/transfer_time_51200.exit.png)

![plots/transfer_time_51200.onionservice.png](plots/transfer_time_51200.onionservice.png)

![plots/transfer_time_5242880.exit.png](plots/transfer_time_5242880.exit.png)

![plots/transfer_time_5242880.onionservice.png](plots/transfer_time_5242880.onionservice.png)
