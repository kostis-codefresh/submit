# Codefresh plugins 

Codefresh Plugins are Docker images made especially for use in Codefresh freestyle steps. Each plugin facilitates a common task that would otherwise be difficult to achieve.
See each plugin readme for more info and usage instructions.

## Plugins

| Plugin|  Description| Tags|
| --- | --- |  --- |
| [Helm](https://github.com/codefresh-plugins/helmblob/master/README.md) | Deploy Helm charts | `kubernetes` `helm`|
| [Codefresh Cli](https://github.com/codefresh-plugins/codefresh-cliblob/master/README.md) | Operate on Codefresh resources | `cli` `codefresh`|
| [Slack](https://github.com/codefresh-plugins/slackblob/master/README.md)| Send message to slack| `slack` `notify`|
| [Deploy to ECS](https://github.com/codefresh-plugins/ecs-deployblob/master/README.md)| Deploy docker image to ECS| `ecs` `deploy` `containers` `aws`                         |
| [Annotate Gitlab Merge](https://github.com/codefresh-plugins/cf-gitlab-mr-annotateblob/master/README.md) | Annotate GitLab Merge Requests | `git` `gitlab` `ci`   |
| [Deploy Kompose](https://github.com/codefresh-plugins/komposeblob/master/README.md)| Deploy Docker Compose to Kubernetes cluster with Kubernetes [Kompose](http://kompose.io) | `docker` `docker-compose` `kompose` `deploy` `kubernetes` |
| [GitHub PR](https://github.com/codefresh-plugins/github-prblob/master/README.md)| Operates on pull requests on GitHub | `github` `pull-request` |
| [Run Jenkins Jobs](https://github.com/codefresh-plugins/cf-run-jenkins-jobsblob/master/README.md)| Run jenkins job from codefresh pipeline| `jenkins` `job`|
| [Deploy to DCOS](https://github.com/codefresh-plugins/cf-deploy-dcosblob/master/README.md) | Deploy application image to DC/OS cluster | `dcos` `deploy` `containers` |
| [Interact with Jira](https://github.com/codefresh-plugins/jira-cliblob/master/README.md) | Interact with Jira from codefresh pipelines| `jira` `workflow`|
| [Makisu](https://github.com/codefresh-plugins/makisublob/master/README.md) | Building images using the Makisu tool | `makisu` `uber`|
| [release to npm](https://github.com/codefresh-plugins/release-to-NPMblob/master/README.md) | Release npm modules from a pipeline | `npm` |
| [Twistlock](https://github.com/codefresh-plugins/cfstep-twistlock) | Security scanning of docker images using Twistlock | `security` |
| [Clair](https://github.com/codefresh-plugins/clairblob/master/README.md) |  Security scanning of Docker images using Clair | `security` |
| [Import Docker Images](https://github.com/codefresh-plugins/import-docker-imagesblob/master/README.md) | Import Docker images metadata into Codefresh| `docker` `codefresh`|
| [Google KMS](https://github.com/codefresh-plugins/google-kmsblob/master/README.md) | Encryption/Decryption with Google KMS| `KMS` `codefresh`|
| [Github Release](https://github.com/codefresh-plugins/github-releaseblob/master/README.md) | Managing GitHub releases | `github` `release`|
| [Google GKE](https://github.com/codefresh-plugins/gkeblob/master/README.md) | GKE Clusters | `GKE` `codefresh`|
| [Vault](https://github.com/codefresh-plugins/vaultblob/master/README.md) | Export Vault Key/Value pairs as ENV variables | `Vault` `codefresh`|
