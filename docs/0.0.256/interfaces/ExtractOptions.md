[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ExtractOptions

# Interface: ExtractOptions

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

  ↳ **`ExtractOptions`**

## Table of contents

### Properties

- [category](ExtractOptions.md#category)
- [filter](ExtractOptions.md#filter)
- [inheritLinks](ExtractOptions.md#inheritlinks)
- [newCategory](ExtractOptions.md#newcategory)
- [newRelationship](ExtractOptions.md#newrelationship)
- [nodes](ExtractOptions.md#nodes)
- [props](ExtractOptions.md#props)
- [reverse](ExtractOptions.md#reverse)
- [skipEmpty](ExtractOptions.md#skipempty)
- [sort](ExtractOptions.md#sort)

## Properties

### category

• **category**: [`CategoryId`](../modules.md#categoryid)

#### Defined in

[transform/extract.ts:24](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/extract.ts#lines-24)

___

### filter

• `Optional` **filter**: [`NodeFilter`](../modules.md#nodefilter)

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[filter](NodeFilterOptions.md#filter)

#### Defined in

[getNodesWithOptions.ts:32](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-32)

___

### inheritLinks

• `Optional` **inheritLinks**: `boolean`

#### Defined in

[transform/extract.ts:28](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/extract.ts#lines-28)

___

### newCategory

• `Optional` **newCategory**: [`CategoryId`](../modules.md#categoryid)

#### Defined in

[transform/extract.ts:26](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/extract.ts#lines-26)

___

### newRelationship

• `Optional` **newRelationship**: [`RelationshipId`](../modules.md#relationshipid)

#### Defined in

[transform/extract.ts:27](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/extract.ts#lines-27)

___

### nodes

• `Optional` **nodes**: [`NodeId`](../modules.md#nodeid)[] \| [`ApiNode`](../classes/ApiNode.md)[]

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[nodes](NodeFilterOptions.md#nodes)

#### Defined in

[getNodesWithOptions.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-33)

___

### props

• **props**: [`ExtractProperty`](ExtractProperty.md)[]

#### Defined in

[transform/extract.ts:25](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/extract.ts#lines-25)

___

### reverse

• `Optional` **reverse**: `boolean`

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[reverse](NodeFilterOptions.md#reverse)

#### Defined in

[getNodesWithOptions.ts:34](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-34)

___

### skipEmpty

• `Optional` **skipEmpty**: `boolean`

#### Defined in

[transform/extract.ts:29](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/extract.ts#lines-29)

___

### sort

• `Optional` **sort**: [`PropertyKey`](../modules.md#propertykey) \| [`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[sort](NodeFilterOptions.md#sort)

#### Defined in

[getNodesWithOptions.ts:31](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-31)
