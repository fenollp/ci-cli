# ci-cli
A CLI for all CIs

```
$ cd .../my-repo.git
$ ci logs --tail=1 -f
.
. live logs of your repo's CIs 
.
```

### Continuous Integration providers
* https://github.com/ligurio/awesome-ci
* https://github.com/cicdops/awesome-ciandcd
Ranking:
* `:)`: Go API fetching live build logs **available**
* `:|`: ... **probably available / soon-ish**
* `:(`: ... **nowhere to be found, yet**
#### GitLab
* `:)` https://github.com/profclems/glab/blob/cb159fbaba2c993d7f1e0885f0cb1902a83031d5/commands/pipeline.go
#### GitHub
* `:|` https://github.com/cli/cli/issues/410
* https://github.com/nektos/act
#### Travis CI
* `:)` https://github.com/travis-ci/travis.rb/tree/8e5ef45d61dce201c1cd12e5f494e4b4bc5dbe63#logs
#### CircleCI
* `:(` https://github.com/CircleCI-Public/circleci-cli
#### drone.io
* `:)` https://github.com/drone/drone-cli/blob/8ab39ea77b568b9083411f10bab33fb001f58968/drone/log/log_view.go
