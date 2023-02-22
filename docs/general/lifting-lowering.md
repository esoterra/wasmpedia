[Module function]: ../module/function.md
[Component function]: ../component/function.md

# Lifting & Lowering



## Lifting

Lifting describes how to take a low-level thing and convert it into a higher-level thing.

| From | To |
| ---- | --- |
| [Module function] [exports](../module/export.md) | [Component function] [exports](../component/export.md)
| [Module values] | [Component values]

## Lowering

Lowering describes how to take a high-level thing and convert it into a lower-level thing.

| From | To |
| ---- | --- |
| [Component function] [imports](../component/import.md) | [Module function] [exports](../module/import.md)
| [Component values] | [Module values]