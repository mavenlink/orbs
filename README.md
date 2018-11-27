# Orbs

---










Work In Progress while we figure out a little bit of process

---

All our orbs will be released under the `mavenlink` namespace.
**Note:** all orbs will be publicly readable so this repository will always stay public.

## mavenlink/git

### checkout

Git clones and fetches at a depth of 1.
This minimizes disk space (and thus cache size) of source code.
Note: invalidate source code caches when switching from unshallow to shallow git operations.

---

## Contribute

Useful commands:

- `circleci orb create mavenlink/git`
- `circleci orb validate src/git/orb.yml`
- Development: `circleci orb publish src/git/orb.yml mavenlink/git@dev:0.0.0`
- Production: `circleci orb publish src/git/orb.yml mavenlink/git@0.0.0`

## Resources

- [Developing a brand new orb -- update to latest `master`](https://github.com/CircleCI-Public/config-preview-sdk/blob/8e6001785fe7a05c3c2941b8d1daf416ac114bc6/docs/inline-orbs.md)
- [Developing an orb in this repository -- update to latest `master`](https://github.com/CircleCI-Public/config-preview-sdk/blob/master/docs/orbs-authoring.md)
- [List of publicly available orbs for inspiration](https://circleci.com/orbs/registry/?showAll=true)
