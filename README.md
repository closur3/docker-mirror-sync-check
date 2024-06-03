## Docker Registry Mirror Sync Results
### Latest Results - 2024-06-03
| Registry | Image | Sync Status | Digest Docker.io | Digest Mirror | Error |
|----------|-------|-------------|------------------|---------------|-------|
| docker.nju.edu.cn | library/node | ✔ In Sync | sha256:a8ba58... | sha256:a8ba58... | |
| docker.m.daocloud.io | library/node | ✔ In Sync | sha256:a8ba58... | sha256:a8ba58... | |
| docker.mirrors.sjtug.sjtu.edu.cn | library/node | ✖ Failed | sha256:a8ba58... | | Error response from daemon: Get "https://docker.mirrors.sjtug.sjtu.edu.cn/v2/": net/http: request canceled while waiting for connection (Client.Timeout exceeded while awaiting headers) |
| docker.nju.edu.cn | library/redis | ✔ In Sync | sha256:01afb3... | sha256:01afb3... | |
| docker.m.daocloud.io | library/redis | ✔ In Sync | sha256:01afb3... | sha256:01afb3... | |
| docker.mirrors.sjtug.sjtu.edu.cn | library/redis | ✖ Failed | sha256:01afb3... | | Error response from daemon: Get "https://docker.mirrors.sjtug.sjtu.edu.cn/v2/": dial tcp 202.120.58.155:443: i/o timeout (Client.Timeout exceeded while awaiting headers) |
| docker.nju.edu.cn | library/nginx | ✔ In Sync | sha256:0f04e4... | sha256:0f04e4... | |
| docker.m.daocloud.io | library/nginx | ✔ In Sync | sha256:0f04e4... | sha256:0f04e4... | |
| docker.mirrors.sjtug.sjtu.edu.cn | library/nginx | ✖ Failed | sha256:0f04e4... | | Error response from daemon: Get "https://docker.mirrors.sjtug.sjtu.edu.cn/v2/": net/http: request canceled while waiting for connection (Client.Timeout exceeded while awaiting headers) |
| docker.nju.edu.cn | adguard/adguardhome | ✔ In Sync | sha256:f890b7... | sha256:f890b7... | |
| docker.m.daocloud.io | adguard/adguardhome | ✔ In Sync | sha256:f890b7... | sha256:f890b7... | |
| docker.mirrors.sjtug.sjtu.edu.cn | adguard/adguardhome | ✖ Failed | sha256:f890b7... | | Error response from daemon: Get "https://docker.mirrors.sjtug.sjtu.edu.cn/v2/": net/http: request canceled while waiting for connection (Client.Timeout exceeded while awaiting headers) |


### History
* [sync_results_2024-06-03.md](history/sync_results_2024-06-03.md)
* [sync_results_2024-05-31.md](history/sync_results_2024-05-31.md)
* [sync_results_2024-05-30.md](history/sync_results_2024-05-30.md)
* [sync_results_2024-05-29.md](history/sync_results_2024-05-29.md)
* [sync_results_2024-05-28.md](history/sync_results_2024-05-28.md)
* [sync_results_2024-05-27.md](history/sync_results_2024-05-27.md)
* [sync_results_2024-05-26.md](history/sync_results_2024-05-26.md)
* [more results](https://github.com/closur3/docker-mirror-sync-check/tree/main/history)

### Link
* [Docker Registry Mirrors](https://gist.github.com/y0ngb1n/7e8f16af3242c7815e7ca2f0833d3ea6)

_This file was updated on 2024-06-03._
