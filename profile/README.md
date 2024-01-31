Welcome!
====

Here you will find a collection of projects for which we maintain patches. These
projects will be tracked here as ports.

Finding and Generating Patches
----

We name AOSC tracking branches as follows.

For full AOSC patchsets:

```
aosc/${upstream-tag}
```

For feature-specific patchsets:

```
aosc/${upstream-tag}-${feature}
```

To generate patches, use `git format-patch`.

Managing Branches
----

If patch maintenance involves one or more feature branches, please make sure that patches were merged into the full branch (`aosc/${upstream-tag}`) by rebasing the full branch against feature branches. For instance:

```
git checkout aosc/${upstream-tag}
git rebase aosc/${upstream-tag}-${feature}
```
