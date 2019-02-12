## Getting Started
### Install git-flow
```bash
brew install git-flow
```

### Setting Up git-flow in a Project
```bash
$ git flow init
Initialized empty Git repository in ~/project/.git/
No branches exist yet. Base branches must be created now.
Branch name for production releases: [master]
Branch name for "next release" development: [develop]
How to name your supporting branch prefixes?
Feature branches? [feature/]
Release branches? [release/]
Hotfix branches? [hotfix/]
Support branches? [support/]
Version tag prefix? []
$ git branch
* develop
 master
```

## Feature Branches
### Creating a feature branch
```bash
git flow feature start feature_branch
```

### Finishing a feature branch
```bash
git flow feature finish feature_branch
```

## Release Branches
### Creating a feature branch
```bash
git flow feature start feature_branch
```

### Finishing a feature branch
```bash
git flow feature finish feature_branch
```

## Release Branches
### Creating a release branch
```bash
git flow release start 0.1.0
```

### Finishing a release branch
```bash
git checkout master
git merge release/0.1.0
git flow release finish '0.1.0'
```

## Hotfix Branches
### Creating a hotfix branch
```bash
git flow hotfix start hotfix_branch
```

### Finishing a hotfix branch
```bash
git flow hotfix finish hotfix_branch
```
