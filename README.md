## Docker Registry Mirror Sync Results
### Latest Results - 2024-06-22
| Registry | Image | Sync Status | Digest Docker.io | Digest Mirror | Error |
|----------|-------|-------------|------------------|---------------|-------|
| dockerproxy.com | library/node | ✔ In Sync | b98ec1c9... | b98ec1c9... | |
| docker.m.daocloud.io | library/node | ✔ In Sync | b98ec1c9... | b98ec1c9... | |
| dockerproxy.com | library/redis | ✔ In Sync | e422889e... | e422889e... | |
| docker.m.daocloud.io | library/redis | ✔ In Sync | e422889e... | e422889e... | |
| dockerproxy.com | library/nginx | ✔ In Sync | 9c367186... | 9c367186... | |
| docker.m.daocloud.io | library/nginx | ✔ In Sync | 9c367186... | 9c367186... | |
| dockerproxy.com | adguard/adguardhome | ✔ In Sync | 3a143e6c... | 3a143e6c... | |
| docker.m.daocloud.io | adguard/adguardhome | ✖ Failed | 3a143e6c... | | Error response from daemon: pull access denied for docker.m.daocloud.io/adguard/adguardhome, repository does not exist or may require 'docker login': denied: 这个镜像不在白名单, 请将其加入. this image is not on the allowlist, please add it. https://github.com/DaoCloud/public-image-mirror/issues/2328 |


### History
* [sync_results_2024-06-22.md](history/sync_results_2024-06-22.md)
* [sync_results_2024-06-21.md](history/sync_results_2024-06-21.md)
* [sync_results_2024-06-20.md](history/sync_results_2024-06-20.md)
* [sync_results_2024-06-19.md](history/sync_results_2024-06-19.md)
* [sync_results_2024-06-18.md](history/sync_results_2024-06-18.md)
* [sync_results_2024-06-17.md](history/sync_results_2024-06-17.md)
* [sync_results_2024-06-16.md](history/sync_results_2024-06-16.md)
* [more results](https://github.com/closur3/docker-mirror-sync-check/tree/main/history)

### Link
* [Docker Registry Mirrors](https://gist.github.com/y0ngb1n/7e8f16af3242c7815e7ca2f0833d3ea6)

_This file was updated on 2024-06-22._
