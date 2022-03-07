# ansible-git-mirror

Ansible role for installing a list git mirrors on a gitlab runner.

## Table of content

[[_TOC_]]

## Git repositories

* Main repo: https://gitlab.comwork.io/oss/ansible-iac/ansible-git-mirror.git
* Github mirror: https://github.com/idrissneumann/ansible-git-mirror.git
* Gitlab mirror: https://gitlab.com/ineumann/ansible-git-mirror.git
* Bitbucket mirror: https://bitbucket.org/idrissneumann/ansible-git-mirror.git
* Froggit mirror: https://lab.frogg.it/ineumann/ansible-git-mirror.git

## Getting started

1. Just use this ansible role on your gitlab runners, override the [default configuration](defaults/main.yml) with the list of repository and their mirrors/remotes and the git credentials
2. Use a pipeline that will run [this bash script](ci/mirror.sh) on git push. Here's an example with [gitlab runner](.gitlab-ci.yml).
