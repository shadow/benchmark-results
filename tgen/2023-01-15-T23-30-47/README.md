# 2023-01-15-T23-30-47

| Key | Value |
|-----|-------|
| benchmark-sha | 9aea9e28f776f51fb7a478c322efb42711e43ea8 |
| comment | Fix for slow TCP connections that become stuck |
| compare-to | 2022-11-24-T00-54-29, weekly, nightly |
| compare-to-resolved | 2022-11-24-T00-54-29, 2023-01-14-T03-05-46, 2023-01-13-T03-12-14 |
| container | debian:bullseye-20220527-slim |
| dry-run | false |
| repeat | 1 |
| results-dir | tgen |
| runtime-args | --parallelism 24 |
| rust-version |  |
| shadow-label | PR #2667 |
| shadow-ref | pull/2667/head |
| shadow-sha | 252f633590041e8ccce9d78ab10c3909222b52d7 |
| sim-id | 2023-01-15-T23-30-47 |
| sim-to-run | tgennet-1000 |
| tgen-ref | c979b74b031fe92ecea70600c8296c00576fcda7 |
| timestamp | 1673825447 |
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
