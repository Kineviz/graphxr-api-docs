[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / MapOptions

# Interface: MapOptions

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

  ↳ **`MapOptions`**

## Table of contents

### Properties

- [category](MapOptions.md#category)
- [filter](MapOptions.md#filter)
- [mappedProperties](MapOptions.md#mappedproperties)
- [nodes](MapOptions.md#nodes)
- [relationship](MapOptions.md#relationship)
- [reverse](MapOptions.md#reverse)
- [sort](MapOptions.md#sort)

## Properties

### category

• `Optional` **category**: [`CategoryId`](../modules.md#categoryid)

#### Defined in

[transform/map.ts:22](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/transform/map.ts#lines-22)

___

### filter

• `Optional` **filter**: [`NodeFilter`](../modules.md#nodefilter)

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[filter](NodeFilterOptions.md#filter)

#### Defined in

[getNodesWithOptions.ts:32](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-32)

___

### mappedProperties

• **mappedProperties**: [`MappedProperty`](MappedProperty.md)[]

#### Defined in

[transform/map.ts:24](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/transform/map.ts#lines-24)

___

### nodes

• `Optional` **nodes**: [`NodeId`](../modules.md#nodeid)[] \| [`ApiNode`](../classes/ApiNode.md)[]

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[nodes](NodeFilterOptions.md#nodes)

#### Defined in

[getNodesWithOptions.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-33)

___

### relationship

• `Optional` **relationship**: [`RelationshipId`](../modules.md#relationshipid)

#### Defined in

[transform/map.ts:23](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/transform/map.ts#lines-23)

___

### reverse

• `Optional` **reverse**: `boolean`

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[reverse](NodeFilterOptions.md#reverse)

#### Defined in

[getNodesWithOptions.ts:34](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-34)

___

### sort

• `Optional` **sort**: [`PropertyKey`](../modules.md#propertykey) \| [`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[sort](NodeFilterOptions.md#sort)

#### Defined in

[getNodesWithOptions.ts:31](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-31)
