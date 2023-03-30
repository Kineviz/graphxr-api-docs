[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / MergeOptions

# Interface: MergeOptions

e.g.

```
api.line({
  sort: (a, b) => a.properties.seasonNumber - b.properties.seasonNumber,
  sort: 'seasonNumber', // same as above
  reverse: true, // sort descending
})

api.ego({
  filter: (node) => node.properties.Level === 1, // Find the root node[s]
})

const rootNodes = // nodes that are the root node[s]
api.ego ({
  nodes: rootNodes,
  nodes: rootNodes.map(n => n.id) // same as above
})
```

## Hierarchy

- [`NodeFilterOptions`](NodeFilterOptions.md)

  ↳ **`MergeOptions`**

## Table of contents

### Properties

- [category](MergeOptions.md#category)
- [clearUnselectedProperties](MergeOptions.md#clearunselectedproperties)
- [directional](MergeOptions.md#directional)
- [filter](MergeOptions.md#filter)
- [keyProperties](MergeOptions.md#keyproperties)
- [nodes](MergeOptions.md#nodes)
- [relationship](MergeOptions.md#relationship)
- [reverse](MergeOptions.md#reverse)
- [sort](MergeOptions.md#sort)

## Properties

### category

• `Optional` **category**: [`CategoryId`](../modules.md#categoryid)

#### Defined in

[transform/merge.ts:14](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/merge.ts#lines-14)

___

### clearUnselectedProperties

• `Optional` **clearUnselectedProperties**: `boolean`

#### Defined in

[transform/merge.ts:17](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/merge.ts#lines-17)

___

### directional

• `Optional` **directional**: `boolean`

#### Defined in

[transform/merge.ts:18](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/merge.ts#lines-18)

___

### filter

• `Optional` **filter**: [`NodeFilter`](../modules.md#nodefilter)

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[filter](NodeFilterOptions.md#filter)

#### Defined in

[getNodesWithOptions.ts:32](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-32)

___

### keyProperties

• `Optional` **keyProperties**: [`PropertyKey`](../modules.md#propertykey)[]

#### Defined in

[transform/merge.ts:16](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/merge.ts#lines-16)

___

### nodes

• `Optional` **nodes**: [`NodeId`](../modules.md#nodeid)[] \| [`ApiNode`](../classes/ApiNode.md)[]

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[nodes](NodeFilterOptions.md#nodes)

#### Defined in

[getNodesWithOptions.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-33)

___

### relationship

• `Optional` **relationship**: [`RelationshipId`](../modules.md#relationshipid)

#### Defined in

[transform/merge.ts:15](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/merge.ts#lines-15)

___

### reverse

• `Optional` **reverse**: `boolean`

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[reverse](NodeFilterOptions.md#reverse)

#### Defined in

[getNodesWithOptions.ts:34](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-34)

___

### sort

• `Optional` **sort**: [`PropertyKey`](../modules.md#propertykey) \| [`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[sort](NodeFilterOptions.md#sort)

#### Defined in

[getNodesWithOptions.ts:31](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-31)
