[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ScaleOptions

# Interface: ScaleOptions

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

  ↳ **`ScaleOptions`**

## Table of contents

### Properties

- [filter](ScaleOptions.md#filter)
- [nodes](ScaleOptions.md#nodes)
- [reverse](ScaleOptions.md#reverse)
- [sort](ScaleOptions.md#sort)
- [x](ScaleOptions.md#x)
- [y](ScaleOptions.md#y)
- [z](ScaleOptions.md#z)

## Properties

### filter

• `Optional` **filter**: [`NodeFilter`](../modules.md#nodefilter)

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[filter](NodeFilterOptions.md#filter)

#### Defined in

[getNodesWithOptions.ts:32](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-32)

___

### nodes

• `Optional` **nodes**: [`NodeId`](../modules.md#nodeid)[] \| [`ApiNode`](../classes/ApiNode.md)[]

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[nodes](NodeFilterOptions.md#nodes)

#### Defined in

[getNodesWithOptions.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-33)

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

___

### x

• `Optional` **x**: `number`

#### Defined in

[layout/scale.ts:8](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layout/scale.ts#lines-8)

___

### y

• `Optional` **y**: `number`

#### Defined in

[layout/scale.ts:9](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layout/scale.ts#lines-9)

___

### z

• `Optional` **z**: `number`

#### Defined in

[layout/scale.ts:10](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layout/scale.ts#lines-10)
