# Index Spaces (Module)

Wasm Modules refer to various items by their "index".

Each type of item in a given scope has an index space which maps unsigned integers to items of that type.
Whenever a new item of a given type is defined in a scope it is assigned the index one larger than the last item of that type.

In other words, items are referred to using zero-indexed numbers which correspond to the order the items are imported or defined.

## Module Item Index Spaces

Some index spaces exist at the [Module] scope.

## Function Index Spaces
