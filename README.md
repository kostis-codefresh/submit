# Codefresh plugins 

Codefresh Plugins are Docker images made especially for use in Codefresh freestyle steps. Each plugin facilitates a common task that would otherwise be difficult to achieve.
See each plugin readme for more info and usage instructions.

## Plugins

| Plugin|  Description| Tags|
| --- | --- |  --- |
| [Helm](https://github.com/codefresh-plugins/helm/README.md) | Deploy Helm charts | `kubernetes` `helm`|
| [Codefresh Cli](https://github.com/codefresh-plugins/codefresh-cli/README.md) | Operate on Codefresh resources | `cli` `codefresh`|
| [Slack](https://github.com/codefresh-plugins/slack/README.md)| Send message to slack| `slack` `notify`|
| [Deploy to ECS](https://github.com/codefresh-plugins/ecs-deploy/README.md)| Deploy docker image to ECS| `ecs` `deploy` `containers` `aws`                         |
| [Annotate Gitlab Merge](https://github.com/codefresh-plugins/cf-gitlab-mr-annotate/README.md) | Annotate GitLab Merge Requests | `git` `gitlab` `ci`   |
| [Deploy Kompose](https://github.com/codefresh-plugins/kompose/README.md)| Deploy Docker Compose to Kubernetes cluster with Kubernetes [Kompose](http://kompose.io) | `docker` `docker-compose` `kompose` `deploy` `kubernetes` |
| [GitHub PR](https://github.com/codefresh-plugins/github-pr/README.MD)| Operates on pull requests on GitHub | `github` `pull-request` |
| [Run Jenkins Jobs](https://github.com/codefresh-plugins/cf-run-jenkins-jobs/README.md)| Run jenkins job from codefresh pipeline| `jenkins` `job`|
| [Deploy to DCOS](https://github.com/codefresh-plugins/cf-deploy-dcos/README.md) | Deploy application image to DC/OS cluster | `dcos` `deploy` `containers` |
| [Interact with Jira](https://github.com/codefresh-plugins/jira-cli/README.md) | Interact with Jira from codefresh pipelines| `jira` `workflow`|
| [Makisu](https://github.com/codefresh-plugins/makisu/README.md) | Building images using the Makisu tool | `makisu` `uber`|
| [release to npm](https://github.com/codefresh-plugins/release-to-NPM/README.md) | Release npm modules from a pipeline | `npm` |
| [Twistlock](https://github.com/codefresh-plugins/cfstep-twistlock) | Security scanning of docker images using Twistlock | `security` |
| [Clair](https://github.com/codefresh-plugins/clair/README.md) |  Security scanning of Docker images using Clair | `security` |
| [Import Docker Images](https://github.com/codefresh-plugins/import-docker-images/README.md) | Import Docker images metadata into Codefresh| `docker` `codefresh`|
| [Google KMS](https://github.com/codefresh-plugins/google-kms/README.md) | Encryption/Decryption with Google KMS| `KMS` `codefresh`|
| [Github Release](https://github.com/codefresh-plugins/github-release/README.md) | Managing GitHub releases | `github` `release`|
| [Google GKE](https://github.com/codefresh-plugins/gke/README.md) | GKE Clusters | `GKE` `codefresh`|
| [Vault](https://github.com/codefresh-plugins/vault/README.md) | Export Vault Key/Value pairs as ENV variables | `Vault` `codefresh`|
