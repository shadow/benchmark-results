# 2023-01-24-T00-39-39

| Key | Value |
|-----|-------|
| benchmark-sha | 632f5e9fecd8cd49b315529576df554e8844f1e7 |
| comment | Rust packet relay with new tgen (with graceful shutdown) |
| compare-to | 2022-11-24-T00-54-29, weekly, nightly |
| compare-to-resolved | 2022-11-24-T00-54-29, 2023-01-21-T03-04-51, 2023-01-20-T03-13-13 |
| container | debian:bullseye-20220527-slim |
| dry-run | false |
| repeat | 1 |
| results-dir | tgen |
| runtime-args | --parallelism 24 |
| rust-version |  |
| shadow-label | PR 2632 |
| shadow-ref | pull/2632/head |
| shadow-sha | fab91c16b035c5f5020e338835f227b36d0ff04e |
| sim-id | 2023-01-24-T00-39-39 |
| sim-to-run | tgennet-1000 |
| tgen-ref | fa98ebdcd309e1e5a3d9596e58dda05efd99c5e7 |
| timestamp | 1674520779 |
| trigger | workflow_dispatch |
| update-symlink |  |
| workflow-name | Manual TGen Benchmark |

[plots/shadow.results.pdf](plots/shadow.results.pdf)

[plots/tgen.viz.pdf](plots/tgen.viz.pdf)

![plots/bytes_read_count_timeseries.png](plots/bytes_read_count_timeseries.png)

![plots/bytes_written_count_timeseries.png](plots/bytes_written_count_timeseries.png)

![plots/flows_created_count_timeseries.png](plots/flows_created_count_timeseries.png)

![plots/flows_succeeded_count_timeseries.png](plots/flows_succeeded_count_timeseries.png)

![plots/streams_created_count_timeseries.png](plots/streams_created_count_timeseries.png)

![plots/streams_succeeded_count_timeseries.png](plots/streams_succeeded_count_timeseries.png)

![plots/time_to_first_byte_recv_cdf.png](plots/time_to_first_byte_recv_cdf.png)

![plots/time_to_first_byte_recv_timeseries.png](plots/time_to_first_byte_recv_timeseries.png)

![plots/time_to_last_byte_recv_1048576_cdf.png](plots/time_to_last_byte_recv_1048576_cdf.png)

![plots/time_to_last_byte_recv_1048576_count_cdf.png](plots/time_to_last_byte_recv_1048576_count_cdf.png)

![plots/time_to_last_byte_recv_1048576_count_timeseries.png](plots/time_to_last_byte_recv_1048576_count_timeseries.png)

![plots/time_to_last_byte_recv_1048576_timeseries.png](plots/time_to_last_byte_recv_1048576_timeseries.png)

![plots/time_to_last_byte_recv_count_cdf.png](plots/time_to_last_byte_recv_count_cdf.png)

![plots/time_to_last_byte_recv_count_timeseries.png](plots/time_to_last_byte_recv_count_timeseries.png)

![plots/total_flows_pending_count_timeseries.png](plots/total_flows_pending_count_timeseries.png)

![plots/total_streams_pending_count_timeseries.png](plots/total_streams_pending_count_timeseries.png)
