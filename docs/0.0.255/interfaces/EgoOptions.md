[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / EgoOptions

# Interface: EgoOptions

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

  ↳ **`EgoOptions`**

## Table of contents

### Properties

- [alongRelationships](EgoOptions.md#alongrelationships)
- [depth](EgoOptions.md#depth)
- [edgeLength](EgoOptions.md#edgelength)
- [filter](EgoOptions.md#filter)
- [mode](EgoOptions.md#mode)
- [nodes](EgoOptions.md#nodes)
- [orientation](EgoOptions.md#orientation)
- [reverse](EgoOptions.md#reverse)
- [sort](EgoOptions.md#sort)
- [sortByProperty](EgoOptions.md#sortbyproperty)

## Properties

### alongRelationships

• `Optional` **alongRelationships**: [`RelationshipId`](../modules.md#relationshipid)[]

#### Defined in

[layout/ego.ts:17](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layout/ego.ts#lines-17)

___

### depth

• `Optional` **depth**: `number`

#### Defined in

[layout/ego.ts:18](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layout/ego.ts#lines-18)

___

### edgeLength

• `Optional` **edgeLength**: `number`

#### Defined in

[layout/ego.ts:19](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layout/ego.ts#lines-19)

___

### filter

• `Optional` **filter**: [`NodeFilter`](../modules.md#nodefilter)

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[filter](NodeFilterOptions.md#filter)

#### Defined in

[getNodesWithOptions.ts:32](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/getNodesWithOptions.ts#lines-32)

___

### mode

• `Optional` **mode**: `EgoMode`

#### Defined in

[layout/ego.ts:20](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layout/ego.ts#lines-20)

___

### nodes

• `Optional` **nodes**: [`NodeId`](../modules.md#nodeid)[] \| [`ApiNode`](../classes/ApiNode.md)[]

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[nodes](NodeFilterOptions.md#nodes)

#### Defined in

[getNodesWithOptions.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/getNodesWithOptions.ts#lines-33)

___

### orientation

• `Optional` **orientation**: `EgoOrientation`

#### Defined in

[layout/ego.ts:21](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layout/ego.ts#lines-21)

___

### reverse

• `Optional` **reverse**: `boolean`

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[reverse](NodeFilterOptions.md#reverse)

#### Defined in

[getNodesWithOptions.ts:34](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/getNodesWithOptions.ts#lines-34)

___

### sort

• `Optional` **sort**: [`PropertyKey`](../modules.md#propertykey) \| [`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[sort](NodeFilterOptions.md#sort)

#### Defined in

[getNodesWithOptions.ts:31](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/getNodesWithOptions.ts#lines-31)

___

### sortByProperty

• `Optional` **sortByProperty**: [`PropertyKey`](../modules.md#propertykey)

#### Defined in

[layout/ego.ts:22](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layout/ego.ts#lines-22)
