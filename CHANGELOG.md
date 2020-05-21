# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### 2.19.9 (2020-05-21)


### ⚠ BREAKING CHANGES

* **minecraft:** resources dependent on the minecraft chart must
reconfigure sources

### Features

* add vertical-pod-autoscaler ([c6dcceb](https://github.com/HRZNStudio/playhrzn-k8s/commit/c6dcceb3eaf906a6750fe434cab4d5e593f80576))
* deploy st minecraft ([b813cb5](https://github.com/HRZNStudio/playhrzn-k8s/commit/b813cb5ca4a78e808bf90d3506983e4d60be4c01))
* **grafana:** enable pomerium auth ([2a76e7f](https://github.com/HRZNStudio/playhrzn-k8s/commit/2a76e7f16376d3c015a46426ce523d5a64aac403))
* **metricbeat:** add prometheus module ([39eea4d](https://github.com/HRZNStudio/playhrzn-k8s/commit/39eea4d4bb97e5552101fbb39c63e96f2b16b411))
* add aws-ebs-csi-driver ([b71cdd5](https://github.com/HRZNStudio/playhrzn-k8s/commit/b71cdd52a79b6d6647d721041e0deb043ac87d4b))
* add elastic-stack ([ead2531](https://github.com/HRZNStudio/playhrzn-k8s/commit/ead253155029d052e4e9ade5dcc78b245d90a77e))
* add flux eks-quickstart-app-dev components ([05d8131](https://github.com/HRZNStudio/playhrzn-k8s/commit/05d8131954a13de839cd23e40bd6b33aded9ba12))
* add forecastle ([f8aadc6](https://github.com/HRZNStudio/playhrzn-k8s/commit/f8aadc6683f0c8aecde2f2db5957f3924007a6ca))
* add ingress-nginx ([857dac9](https://github.com/HRZNStudio/playhrzn-k8s/commit/857dac982b21ab17e806c1b2261735152e027542))
* add kube-ops-view ([7a80c5f](https://github.com/HRZNStudio/playhrzn-k8s/commit/7a80c5f1b043be1e940c029bf9ff1ed4de788c7f))
* add pomerium ([4b217cd](https://github.com/HRZNStudio/playhrzn-k8s/commit/4b217cdd865451c1876ba98834a4e82272c181c5))
* add sealed-secrets ([f9134f4](https://github.com/HRZNStudio/playhrzn-k8s/commit/f9134f453c1476df80a15f8551b6464e6e140d17))
* deploy jingle minecraft ([e35606b](https://github.com/HRZNStudio/playhrzn-k8s/commit/e35606bb178746f29382499a9f3e68b603cc94b6))
* **forecastle:** add ingress ([bc0b42a](https://github.com/HRZNStudio/playhrzn-k8s/commit/bc0b42ac4e5f062b329a26688c379f2bc33b746a))
* **grafana:** add ingress ([b7bf6da](https://github.com/HRZNStudio/playhrzn-k8s/commit/b7bf6dacc674664e469b5da2942213eaaef32ffa))
* deploy yogs minecraft ([0e0b514](https://github.com/HRZNStudio/playhrzn-k8s/commit/0e0b514bdbe93b8a55048fbfdd18a4084af31910))
* **minecraft:** add additional cloudcmd config ([2135224](https://github.com/HRZNStudio/playhrzn-k8s/commit/213522489a85e3fe214b0abfeb45136d444f6699))
* **minecraft:** add cloud commander ([41e456d](https://github.com/HRZNStudio/playhrzn-k8s/commit/41e456d76376a332e2a944fb7fc645f5c1629683))
* **minecraft:** add rcon-web-admin ([ff7aece](https://github.com/HRZNStudio/playhrzn-k8s/commit/ff7aece15807f6f4e3d944e694b1cc21686901d2))
* **minecraft:** add release name context to motd ([4d4e45f](https://github.com/HRZNStudio/playhrzn-k8s/commit/4d4e45fab2de3945e3aff5d4f8451748699b7d01))
* **minecraft:** clone from helm/charts ([c465965](https://github.com/HRZNStudio/playhrzn-k8s/commit/c46596525b6b73b84a00e8804855e8422c3dadba))
* **minecraft:** enable service annotation config ([7b1eb4e](https://github.com/HRZNStudio/playhrzn-k8s/commit/7b1eb4e3992d5d0233e4fc8cb37b56f4da661a92))
* **minecraft/cloudcmd:** add config toggles for terminal and console ([79289d6](https://github.com/HRZNStudio/playhrzn-k8s/commit/79289d6cc7c66b1e1320a8e8b1e577b0aa087576))
* **rr5:** add volume reclaim ([0f9e6f0](https://github.com/HRZNStudio/playhrzn-k8s/commit/0f9e6f0064a7ee3676940b2624cb080b5cc7e38b))
* **rr5:** cloudcmd deployment and ingress ([821eb02](https://github.com/HRZNStudio/playhrzn-k8s/commit/821eb02914db43b5bd9faef6d1a1ca47bb5c537f))
* **rr5:** http to https redirect for web apps ([5ad7998](https://github.com/HRZNStudio/playhrzn-k8s/commit/5ad79989227c2ef42f1ecf8d9e66a762589b074a))
* **rr5/rcon:** add external-dns annotation ([c47e82b](https://github.com/HRZNStudio/playhrzn-k8s/commit/c47e82be21b4a92d8c5a2bf50f1fb4a7d2107f4a))
* add external-dns ([23f2f29](https://github.com/HRZNStudio/playhrzn-k8s/commit/23f2f299007dd86d8f50d71e0700534da1311ba0))
* initial commit ([a79b517](https://github.com/HRZNStudio/playhrzn-k8s/commit/a79b517dc537a7f503e1cf81e86131720614cbac))
* replace demo with rr5 minecraft ([5d0fc21](https://github.com/HRZNStudio/playhrzn-k8s/commit/5d0fc212ff90260c264f049234a9d62daa0303ed))


### Bug Fixes

* **cluster-autoscaler:** update dependency clusterrole permissions ([4dd7289](https://github.com/HRZNStudio/playhrzn-k8s/commit/4dd7289dda7396b79e1af0c5c07a0df6e123a5d1))
* **ingress-nginx:** enable proxy-protocol for websocket compatibility ([5eeed8a](https://github.com/HRZNStudio/playhrzn-k8s/commit/5eeed8a8124bedd938b9f354e2d61badca9fa5e7))
* **ingress-nginx:** ssl-redirect with tcp proxy-protocol ([43e760e](https://github.com/HRZNStudio/playhrzn-k8s/commit/43e760e007477b99e60682d524048a788d849a04))
* **logstash:** add services to allow statefulset creation (elastic/helm-charts[#497](https://github.com/HRZNStudio/playhrzn-k8s/issues/497)) ([5cd9579](https://github.com/HRZNStudio/playhrzn-k8s/commit/5cd9579196e239db31f3d40b3c1699914885a8d2))
* **minecraft:** remove wildcard from cloudcmd ingress ([aa732d3](https://github.com/HRZNStudio/playhrzn-k8s/commit/aa732d3218d1efa9e43a1decf834f28551ee4dac))
* **minecraft:** stringify deployment envvars ([98020fb](https://github.com/HRZNStudio/playhrzn-k8s/commit/98020fbd944d99d6684b4e3b83f5460ddc399034))
* **minecraft/cloudcmd:** basic auth for readiness checking ([410870c](https://github.com/HRZNStudio/playhrzn-k8s/commit/410870c2e31dcbc5b7cbda8d6c33ed803dcd3df7))
* **minecraft/cloudcmd:** increase max body size for uploads ([1314f58](https://github.com/HRZNStudio/playhrzn-k8s/commit/1314f582bd8e5d138832668c981bbcafb74d4dd4))
* **minecraft/rcon-web-admin:** split web(socket) config ([918733e](https://github.com/HRZNStudio/playhrzn-k8s/commit/918733e7a63449e545d6a20a4693d2438a198a92))
* **rr5:** enforce server.properties ([736150f](https://github.com/HRZNStudio/playhrzn-k8s/commit/736150f416c5fbc5b1c07562dc2d205f1599e641))
* **rr5:** increase max-world-size to 29999984 ([eedfb00](https://github.com/HRZNStudio/playhrzn-k8s/commit/eedfb009ee65ac2b912bfd93f5c6bc4fa04b7569))
* **rr5:** increase pvc size to 5Gi ([856118b](https://github.com/HRZNStudio/playhrzn-k8s/commit/856118b0a39a54d2cc3e4b7f39b9a3a0e9512327))
* **rr5/cloudcmd:** remove ip6 ingress ([fce97fb](https://github.com/HRZNStudio/playhrzn-k8s/commit/fce97fb5b1a4a34653660dfb5f87cf8c8b9cb87d))


* **minecraft:** migrate from hrznstudio/charts repo ([f90e08d](https://github.com/HRZNStudio/playhrzn-k8s/commit/f90e08d78d725282fe62e4230c72747fa8a5960d))
