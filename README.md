# Goldstar CircleCI Orbs

-------------------------------------------------------------------------------

### Note: All orbs are public -- do not put private data in this repo nor in the orbs deployed to circleci.

#### Publishing the Orb:

We still need to figure out a way for this repo to build, test and publish Orbs. Right now I run the following:

```bash
circleci orb validate publish-gem/@orb.yml
```

Once that's all good, I run:

```bash
circleci orb publish increment publish-gem/@orb.yml goldstar/publish-gem minor
```

Then it bumps the version and publishes. These don't change that often so this manual process is fine for now.
