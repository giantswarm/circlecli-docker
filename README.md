# circlecli-docker

Docker image for the [`circlecli`](https://github.com/TheRealJoeLinux/circlecli) utility. Automatically built as `giantswarm/circlecli`.

Set an alias like this, applying your personal CircleCI token ([get one here](https://circleci.com/account/api)):

```
alias circlecli="docker run --rm -ti -e CIRCLE_TOKEN=your_token_here giantswarm/circlecli"
```

Then execute `circlecli` just as if you had it installed. E. g.

```
circlecli --help
circlecli env -u orgname -p projectname -s ENV_VAR_NAME=value
```
