# 2023-04-14-T19-51-46

| Key | Value |
|-----|-------|
| benchmark-sha | b9ea842b299312f8cbf7daf0995f57c3c010bbf6 |
| comment | "Add spinning to simple latch" - spin_count == usize::MAX, thread::yield_now() |
| compare-to | 2022-06-06-T23-09-40, 2023-04-12-T05-26-59, weekly, nightly |
| compare-to-resolved | 2022-06-06-T23-09-40, 2023-04-12-T05-26-59, 2023-04-01-T06-13-26, 2023-04-14-T07-53-12 |
| container | debian:bullseye-20220527-slim |
| dry-run | false |
| oniontrace-ref | 9e0e83ceb0765bc915a2888bcc02e68a5a9b848f |
| repeat | 1 |
| results-dir | tor |
| runtime-args | --parallelism 24 --use-preload-openssl-crypto true |
| rust-version |  |
| shadow-label | PR #2871 |
| shadow-ref | pull/2871/head |
| shadow-sha | 1cc31a0963483652c27663bacfa809b60b9a538a |
| sim-id | 2023-04-14-T19-51-46 |
| sim-to-run | tornet-0.05 |
| tgen-ref | 3d7788bad362b4487d1145da93ab2fdb73c9b639 |
| timestamp | 1681501906 |
| tor-ref | tor-0.4.7.7 |
| tornettools-ref | 2748d1245fdc5d5b20f9977c9a9d2394e64750bf |
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

![plots/flows_created_count_timeseries.png](plots/flows_created_count_timeseries.png)

![plots/flows_succeeded_count_timeseries.png](plots/flows_succeeded_count_timeseries.png)

![plots/ram_realtime.png](plots/ram_realtime.png)

![plots/ram_simtime.png](plots/ram_simtime.png)

![plots/relay_goodput.png](plots/relay_goodput.png)

![plots/round_trip_time.exit.png](plots/round_trip_time.exit.png)

![plots/round_trip_time.onionservice.png](plots/round_trip_time.onionservice.png)

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

![plots/transfer_error_rates_ALL.onionservice.png](plots/transfer_error_rates_ALL.onionservice.png)

![plots/transfer_time_1048576.exit.png](plots/transfer_time_1048576.exit.png)

![plots/transfer_time_1048576.onionservice.png](plots/transfer_time_1048576.onionservice.png)

![plots/transfer_time_51200.exit.png](plots/transfer_time_51200.exit.png)

![plots/transfer_time_51200.onionservice.png](plots/transfer_time_51200.onionservice.png)

![plots/transfer_time_5242880.exit.png](plots/transfer_time_5242880.exit.png)

![plots/transfer_time_5242880.onionservice.png](plots/transfer_time_5242880.onionservice.png)
