# entities-godot-bidirected-graph-min-deviation-flow

A Godot GDExtension that runs libsatsuma's minimum-deviation-flow solver on a bidirected graph.

## What it is for

Minimum-deviation flow on bidirected graphs is the integer step of T-mesh quantization in quad remeshing (Heistermann, Warnett and Bommes, 2023). The extension registers a `BIMDF` class whose `solve()` solves a fixed example graph and prints the flow on each edge.

## Build

```sh
git submodule update --init
scons
```

## Licence

MIT; see `LICENSE`. The vendored libsatsuma is MIT under its own licence file.
