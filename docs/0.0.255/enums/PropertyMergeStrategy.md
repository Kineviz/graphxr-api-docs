[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / PropertyMergeStrategy

# Enumeration: PropertyMergeStrategy

## Table of contents

### Enumeration Members

- [ASSIGN](PropertyMergeStrategy.md#assign)
- [KEEP](PropertyMergeStrategy.md#keep)
- [REPLACE](PropertyMergeStrategy.md#replace)

## Enumeration Members

### ASSIGN

• **ASSIGN** = ``0``

Copy properties from the source to the target. Properties in the target which are not in the source are kept.

#### Defined in

[layoutGraph.ts:42](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-42)

___

### KEEP

• **KEEP** = ``2``

Don't touch properties in the target

#### Defined in

[layoutGraph.ts:50](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-50)

___

### REPLACE

• **REPLACE** = ``1``

Erase properties in the target and then copy properties from the source to the target.

#### Defined in

[layoutGraph.ts:46](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-46)
