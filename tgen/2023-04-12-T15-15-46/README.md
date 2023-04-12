# 2023-04-12-T15-15-46

| Key | Value |
|-----|-------|
| benchmark-sha | b9ea842b299312f8cbf7daf0995f57c3c010bbf6 |
| comment | Debugging perf change ("Move more env variables to shared memory"). Lowered stop_time. |
| compare-to | 2022-11-24-T00-54-29, weekly, nightly |
| compare-to-resolved | 2022-11-24-T00-54-29, 2023-04-08-T03-02-58, 2023-04-12-T03-09-37 |
| container | debian:bullseye-20220527-slim |
| dry-run | false |
| repeat | 1 |
| results-dir | tgen |
| runtime-args | --parallelism 24 --stop-time 200s |
| rust-version |  |
| shadow-label | commit 4053e9 |
| shadow-ref | 4053e9f1f4737a4831274ce33bd7cd8ff3514fb3 |
| shadow-sha | 4053e9f1f4737a4831274ce33bd7cd8ff3514fb3 |
| sim-id | 2023-04-12-T15-15-46 |
| sim-to-run | tgennet-1000 |
| tgen-ref | 3d7788bad362b4487d1145da93ab2fdb73c9b639 |
| timestamp | 1681312546 |
| trigger | workflow_dispatch |
| update-symlink |  |
| workflow-name | Manual TGen Benchmark |

[plots/shadow.results.pdf](plots/shadow.results.pdf)

[plots/tgen.viz.pdf](plots/tgen.viz.pdf)

![plots/bytes_read_count_timeseries.png](plots/bytes_read_count_timeseries.png)

![plots/bytes_written_count_timeseries.png](plots/bytes_written_count_timeseries.png)

![plots/errors_TIMEOUT_bytes_cdf.png](plots/errors_TIMEOUT_bytes_cdf.png)

![plots/errors_TIMEOUT_cdf.png](plots/errors_TIMEOUT_cdf.png)

![plots/errors_TIMEOUT_timeseries.png](plots/errors_TIMEOUT_timeseries.png)

![plots/flows_created_count_timeseries.png](plots/flows_created_count_timeseries.png)

![plots/flows_succeeded_count_timeseries.png](plots/flows_succeeded_count_timeseries.png)

![plots/streams_created_count_timeseries.png](plots/streams_created_count_timeseries.png)

![plots/streams_failed_count_timeseries.png](plots/streams_failed_count_timeseries.png)

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
