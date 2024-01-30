Welcome to the AOSC Code Tracking Project!
====

Here you will find a collection of project for which we maintain patches. These
projects will be tracked here as ports.

How to find and generate patchsets
----

We name AOSC tracking branches as follows.

For full AOSC patchsets:

```
aosc/${upstream-tag}
```

For feature-specific patchsets:

```
aosc/${upstream-tag}-feature
```

To generate patches, use `git format-patch`.
