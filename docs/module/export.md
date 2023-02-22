[Module]: ./index.md
[identifier]: ./
[identifier]: ./
[external kind]: ./
[index space]: ./index-space.md

[Function]: ./function.md
[Table]: ./table.md
[Memory]: ./memory.md
[Global]: ./global.md

# Export (Module)

An export represents some resource that a [Module] provides when instantiated. 

| Field Name      | Type               | Description                             |
| --------------- | ------------------ | --------------------------------------- |
| `name`          | [identifier]       | field name                              |
| `kind`          | [external kind]    | the kind of export                      |
| `index`         | index              | an index into an [index space]          |

Functionally, exports take an item in the index space and make it externally-available.

## Export Types

It's possible to export all of the same types that can be [imported](./import.md#import-types).

* [Function]
* [Table]
* [Memory]
* [Global]

