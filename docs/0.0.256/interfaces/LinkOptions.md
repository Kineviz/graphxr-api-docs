[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / LinkOptions

# Interface: LinkOptions

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

  ↳ **`LinkOptions`**

## Table of contents

### Properties

- [filter](LinkOptions.md#filter)
- [nodes](LinkOptions.md#nodes)
- [relationship](LinkOptions.md#relationship)
- [reverse](LinkOptions.md#reverse)
- [sort](LinkOptions.md#sort)
- [sourceCategory](LinkOptions.md#sourcecategory)
- [sourceProperty](LinkOptions.md#sourceproperty)
- [targetCategory](LinkOptions.md#targetcategory)
- [targetProperty](LinkOptions.md#targetproperty)

## Properties

### filter

• `Optional` **filter**: [`NodeFilter`](../modules.md#nodefilter)

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[filter](NodeFilterOptions.md#filter)

#### Defined in

[getNodesWithOptions.ts:32](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-32)

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

[transform/link.ts:15](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/link.ts#lines-15)

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

___

### sourceCategory

• **sourceCategory**: [`CategoryId`](../modules.md#categoryid)

#### Defined in

[transform/link.ts:11](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/link.ts#lines-11)

___

### sourceProperty

• **sourceProperty**: [`PropertyKey`](../modules.md#propertykey)

#### Defined in

[transform/link.ts:12](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/link.ts#lines-12)

___

### targetCategory

• **targetCategory**: [`CategoryId`](../modules.md#categoryid)

#### Defined in

[transform/link.ts:13](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/link.ts#lines-13)

___

### targetProperty

• **targetProperty**: [`PropertyKey`](../modules.md#propertykey)

#### Defined in

[transform/link.ts:14](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/transform/link.ts#lines-14)
