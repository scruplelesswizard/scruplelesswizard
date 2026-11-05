# Jason Murray

### Platform engineer in Canada. I make infrastructure boring and CI fast.

I build the Kubernetes, Terraform and CI/CD foundations that let product teams ship without thinking about
them. My open source work follows the same idea: small, well-tested tools and automation that remove waiting
from the developer feedback loop.

<a href="https://linkedin.com/in/scruplelesswizard" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="scruplelesswizard" height="30" width="40" /></a>
<a href="https://wizardswithoutscruples.com" target="_blank">wizardswithoutscruples.com</a>

---

### My own projects

**[split-tests](https://github.com/scruplelesswizard/split-tests)** · GitHub Action · ⭐ 34
I wrote this to split a test suite into equal-time groups so parallel CI jobs finish together instead of
waiting on the slowest runner. It works with any test runner. The underlying binary is pinned and
SHA256-verified, a weekly workflow proposes upgrades, and the smoke tests assert that every partition is
non-empty, disjoint and covers the full suite.

**[junit-munger](https://github.com/scruplelesswizard/junit-munger)** · Go CLI · v1.0.0
I wrote this to merge per-worker RSpec JUnit reports into per-file timings, which is the input split-tests
needs to balance runs by real durations. It has unit tests, and CI publishes cross-platform binaries and cuts
a release on every merge.

**[meshtastic-node-red](https://github.com/scruplelesswizard/meshtastic-node-red)** · Node-RED · ⭐ 18 · archived reference
A telemetry pipeline for off-grid LoRa mesh networks: MQTT ingest, protobuf decoding, deduplication and six
InfluxDB measurement streams, ready to chart in Grafana. I archived it, but it still works as a reference.

### Open source contributions

- **[meshtastic/node-red-contrib-meshtastic](https://github.com/search?q=repo%3Ameshtastic%2Fnode-red-contrib-meshtastic+author%3Ascruplelesswizard&type=commits)**: 26 commits. I added decoding for NeighborInfo, StoreAndForward, range test and other port numbers, consolidated the payload decoding, moved telemetry handling, added CI and release workflows, and documented the v1 to v2 data structure changes.
- **[meshtastic/firmware](https://github.com/search?q=repo%3Ameshtastic%2Ffirmware+author%3Ascruplelesswizard&type=commits)**: 13 commits of CI/CD work. I consolidated the variant build steps, added Dependabot, automated the protobuf-bump PRs, and added a PR comment that links the build artifact.
- **[meshtastic/js](https://github.com/search?q=repo%3Ameshtastic%2Fjs+author%3Ascruplelesswizard&type=commits)**: 5 commits for dependency updates, cleanup of an obsolete payload case, and a CI check that the package version is bumped.
- **[ProtonMail/go-crypto](https://github.com/search?q=repo%3AProtonMail%2Fgo-crypto+author%3Ascruplelesswizard&type=commits)**: added OpenPGP key flags (authenticate, group key, split key) support in Go.
- **[kubermatic/kubermatic](https://github.com/search?q=repo%3Akubermatic%2Fkubermatic+author%3Ascruplelesswizard&type=commits)**: wrote the guide for creating a new seed cluster and refactored a Helm chart.

I have also made smaller fixes in Terraform, Kubernetes, Atlantis, Argo Helm and tfsec.

### What I bring

- **Platform and infrastructure:** Kubernetes, Helm and Terraform on AWS, GCP and Azure
- **Developer experience:** faster CI, test parallelization, release automation
- **Engineering habits:** tests and CI on everything, automated dependency updates, documented and versioned releases
- **Languages:** Go, TypeScript, Python, Bash

### By the numbers

On GitHub since 2015 · 1,100+ contributions in the last year · 50 public repositories · 55 stars across my own projects

### Tools

<a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/></a>
<a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/></a>
<a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/></a>
<a href="https://circleci.com" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/circleci/circleci-icon.svg" alt="circleci" width="40" height="40"/></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
<a href="https://www.elastic.co" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/elastic/elastic-icon.svg" alt="elasticsearch" width="40" height="40"/></a>
<a href="https://cloud.google.com" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/></a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>
<a href="https://golang.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/></a>
<a href="https://kubernetes.io" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/></a>
<a href="https://www.linux.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/></a>
<a href="https://mariadb.org/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg" alt="mariadb" width="40" height="40"/></a>
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/></a>
<a href="https://www.nginx.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/></a>
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/></a>
<a href="https://redis.io" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/></a>
<a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/></a>

---

Want to talk platform engineering, CI speed or mesh networks? Find me on LinkedIn above.
