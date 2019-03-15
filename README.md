## ant

[![Build Status](https://travis-ci.org/Oefenweb/ansible-git-lfs-bitbucket-media-api.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-git-lfs-bitbucket-media-api) 
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-git--lfs--bitbucket--media--api-blue.svg)](https://galaxy.ansible.com/Oefenweb/git-lfs-bitbucket-media-api)

Set up (the latest or a specific version of) [Git LFS Custom Adapter for Bitbucket](https://confluence.atlassian.com/bitbucket/bitbucket-lfs-media-adapter-856699998.html) in Debian-like systems.

#### Requirements

* `curl` (will be installed)
* `unzip` (will be installed)
* `git` (will be installed)

#### Variables

None

## Dependencies

None

## Recommended

* `ansible-latest-git` ([see](https://github.com/Oefenweb/ansible-latest-git))
* `ansible-git-lfs` ([see](https://github.com/Oefenweb/ansible-git-lfs))

#### Example

```yaml
---
- hosts: all
  roles:
    - git-lfs-bitbucket-media-api
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-git-lfs-bitbucket-media-api/issues)!
