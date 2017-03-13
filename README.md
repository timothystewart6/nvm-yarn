# nvm-yarn

## Why?

I like `node`.  I like `yarn`.  I like `nvm` to manage node while still getting the benefits of using yarn.

## Usage

This image can be used for many reasons but my primary use case is for building during CI.  I use `nvm` to manage my version of node.  I found that I end up setting my node version in multiple places and multiple changes are needed to bump my version of node.  This image can be used for CI services like Travis, GitLab, Drone, and many other systems that use docker images during CI.

## Requirements

Be sure that you have a `.nvmrc` file in the root of your repo.  It should look something like this:

`.nvmrc`
```bash
v6.10.0
```


