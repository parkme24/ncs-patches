# Zephyr patches

To apply a patch run from the root directory to be patched:

```
git am /path/to/patch
```
or
```
git am --3way /path/to/patch
```

To create a patch from the root directory of the change, commit the change to
generate a patch from and:

```
git format-patch -1 HEAD -o /path/to/patch
```
