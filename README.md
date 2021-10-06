# `gh add-team-member` GitHub CLI extension

[GitHub CLI](https://github.com/cli/cli) extension for bulk register members to a github team

## Installation
```
gh extension install utamori/gh-add-team-member
```

## Usage

Set the environment variable `GH_ORG` & `GH_TEAM`

```
export GH_ORG={your org}
export GH_TEAM={target team}
```

list the names of the users you want to add to the target team

```
gh add-team-member member1 member2 member3 ...
```
