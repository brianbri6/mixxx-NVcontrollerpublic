# Project notes

See README.md for the Mixxx overview, CONTRIBUTING.md for contribution/build guidance,
and README_NV.md for the Raspberry Pi integration.

## Key Architecture

- **ControlObject/ControlProxy**: `[Group], key_name` inter-component communication.
- **Engine thread**: Real-time audio — no allocations, no locks, may emit Qt signals but cannot receive them.
- **parented_ptr/make_parented**: Qt object-tree ownership. Object must get a parent before `parented_ptr` destructs.

## Project Layout

```text
src/          C++ source (engine/, controllers/, library/, mixer/, effects/, qml/, preferences/, util/, test/)
res/          Resources (controllers/ JS/XML, skins/, qml/)
cmake/        CMake modules
tools/        Python helper scripts
```

## Original Numark NV mapping

Read bitedj-nv/docs/NV_EQ_FACTORY_MAPPING.md before controller changes.
Preserve the original factory EQ order on all four channels. Keep the two
res/controllers mapping copies synchronized with bitedj-nv/controller/.
README_NV.md and PROJECT_PROGRESS.md describe the pinned Pi native build target.
