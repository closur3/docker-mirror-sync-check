## Docker Registry Mirror Sync Results
### Latest Results - 2024-06-08
| Registry | Image | Sync Status | Digest Docker.io | Digest Mirror | Error |
|----------|-------|-------------|------------------|---------------|-------|
| dockerproxy.com | library/node | ✖ Failed | a8ba58f5... | | Error response from daemon: received unexpected HTTP status: 502 Bad Gateway |
| docker.m.daocloud.io | library/node | ✔ In Sync | a8ba58f5... | a8ba58f5... | |
| cr.yandex/mirror | library/node | ✖ Outdated | a8ba58f5... | 0a653503... | |
| registry.redhat.io | library/node | ✖ Failed | a8ba58f5... | | Error response from daemon: Head "https://registry.redhat.io/v2/library/node/manifests/latest": unauthorized: Please login to the Red Hat Registry using your Customer Portal credentials. Further instructions can be found here: https://access.redhat.com/RegistryAuthentication |
| public.ecr.aws | library/node | ✖ Failed | a8ba58f5... | | Error response from daemon: repository public.ecr.aws/library/node not found: name unknown: The repository with name 'node' does not exist in the registry with id 'library' |
| dockerproxy.com | library/redis | ✖ Failed | 01afb31d... | | Error response from daemon: received unexpected HTTP status: 502 Bad Gateway |
| docker.m.daocloud.io | library/redis | ✔ In Sync | 01afb31d... | 01afb31d... | |
| cr.yandex/mirror | library/redis | ✖ Outdated | 01afb31d... | 276dd576... | |
| registry.redhat.io | library/redis | ✖ Failed | 01afb31d... | | Error response from daemon: Head "https://registry.redhat.io/v2/library/redis/manifests/latest": unauthorized: Please login to the Red Hat Registry using your Customer Portal credentials. Further instructions can be found here: https://access.redhat.com/RegistryAuthentication |
| public.ecr.aws | library/redis | ✖ Failed | 01afb31d... | | Error response from daemon: repository public.ecr.aws/library/redis not found: name unknown: The repository with name 'redis' does not exist in the registry with id 'library' |
| dockerproxy.com | library/nginx | ✖ Failed | 0f04e4f6... | | Error response from daemon: received unexpected HTTP status: 502 Bad Gateway |
| docker.m.daocloud.io | library/nginx | ✔ In Sync | 0f04e4f6... | 0f04e4f6... | |
| cr.yandex/mirror | library/nginx | ✖ Outdated | 0f04e4f6... | ac996bb3... | |
| registry.redhat.io | library/nginx | ✖ Failed | 0f04e4f6... | | Error response from daemon: Head "https://registry.redhat.io/v2/library/nginx/manifests/latest": unauthorized: Please login to the Red Hat Registry using your Customer Portal credentials. Further instructions can be found here: https://access.redhat.com/RegistryAuthentication |
| public.ecr.aws | library/nginx | ✖ Failed | 0f04e4f6... | | Error response from daemon: repository public.ecr.aws/library/nginx not found: name unknown: The repository with name 'nginx' does not exist in the registry with id 'library' |
| dockerproxy.com | adguard/adguardhome | ✖ Failed | 3a143e6c... | | Error response from daemon: received unexpected HTTP status: 502 Bad Gateway |
| docker.m.daocloud.io | adguard/adguardhome | ✔ In Sync | 3a143e6c... | 3a143e6c... | |
| cr.yandex/mirror | adguard/adguardhome | ✖ Failed | 3a143e6c... | | Error response from daemon: repository cr.yandex/mirror/adguard/adguardhome not found: name unknown: Repository mirror/adguard/adguardhome not found ; requestId = 132a8ce5-70ce-446a-b2fd-2d99b4a3c7be |
| registry.redhat.io | adguard/adguardhome | ✖ Failed | 3a143e6c... | | Error response from daemon: Head "https://registry.redhat.io/v2/adguard/adguardhome/manifests/latest": unauthorized: Please login to the Red Hat Registry using your Customer Portal credentials. Further instructions can be found here: https://access.redhat.com/RegistryAuthentication |
| public.ecr.aws | adguard/adguardhome | ✖ Failed | 3a143e6c... | | Error response from daemon: repository public.ecr.aws/adguard/adguardhome not found: name unknown: The repository with name 'adguardhome' does not exist in the registry with id 'adguard' |


### History
* [sync_results_2024-06-08.md](history/sync_results_2024-06-08.md)
* [sync_results_2024-06-07.md](history/sync_results_2024-06-07.md)
* [sync_results_2024-06-06.md](history/sync_results_2024-06-06.md)
* [sync_results_2024-06-05.md](history/sync_results_2024-06-05.md)
* [sync_results_2024-06-04.md](history/sync_results_2024-06-04.md)
* [sync_results_2024-06-03.md](history/sync_results_2024-06-03.md)
* [sync_results_2024-05-31.md](history/sync_results_2024-05-31.md)
* [more results](https://github.com/closur3/docker-mirror-sync-check/tree/main/history)

### Link
* [Docker Registry Mirrors](https://gist.github.com/y0ngb1n/7e8f16af3242c7815e7ca2f0833d3ea6)

_This file was updated on 2024-06-08._
