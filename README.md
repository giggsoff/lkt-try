Just two packages I want to build with linuxkit. `pkg2` uses the tag from `pkg1`.

I want to build `pkg2`, so I build `pkg1` before:

```console
linuxkit pkg build --platforms linux/amd64 pkg1
linuxkit pkg build --platforms linux/amd64 pkg2
```