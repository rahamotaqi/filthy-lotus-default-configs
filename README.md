# filthy-lotus-default-configs
A simple repo to compare the config files of lotus between releases


![github compare img](https://github.com/Factor8Solutions/filthy-lotus-default-configs/blob/master/img/github-compare.png?raw=true)

# HowTo

Visit the [Github Compare Page](https://github.com/Factor8Solutions/filthy-lotus-default-configs/compare) for this repo and choose a base branch/tag and a compare branch/tag. Github will show you the changes between the two tags/branches.

# Branches

## master 

The `master` branch contains the `lotus` and `lotus-miner` config files. We try to keep them in sync with the latest releases in [Filecoin-Project Lotus Repo](https://github.com/filecoin-project/lotus).

## files

The `files` branch contains the full config files of each release. The files are generated with the commands `lotus config default` and `lotus-miner config default`. 

# Notes

- starts with `v1.11.3` - earlier versions need golang clusterfu to build, thats why
- there is no `lotus-worker config default` command. If this changes we will add a config file for `lotus-worker` too
- we might be late by a day or two until we properly automated this repo!