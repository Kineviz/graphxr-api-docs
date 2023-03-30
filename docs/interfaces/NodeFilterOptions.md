[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / NodeFilterOptions

# Interface: NodeFilterOptions

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

- **`NodeFilterOptions`**

  ↳ [`AlignByOptions`](AlignByOptions.md)

  ↳ [`EgoOptions`](EgoOptions.md)

  ↳ [`ParametricOptions`](ParametricOptions.md)

  ↳ [`RotateOptions`](RotateOptions.md)

  ↳ [`ScaleOptions`](ScaleOptions.md)

  ↳ [`ShiftOptions`](ShiftOptions.md)

  ↳ [`ExtractOptions`](ExtractOptions.md)

  ↳ [`LinkOptions`](LinkOptions.md)

  ↳ [`MapOptions`](MapOptions.md)

  ↳ [`MergeOptions`](MergeOptions.md)

  ↳ [`ShortcutOptions`](ShortcutOptions.md)

## Table of contents

### Properties

- [filter](NodeFilterOptions.md#filter)
- [nodes](NodeFilterOptions.md#nodes)
- [reverse](NodeFilterOptions.md#reverse)
- [sort](NodeFilterOptions.md#sort)

## Properties

### filter

• `Optional` **filter**: [`NodeFilter`](../modules.md#nodefilter)

#### Defined in

[getNodesWithOptions.ts:32](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-32)

___

### nodes

• `Optional` **nodes**: [`NodeId`](../modules.md#nodeid)[] \| [`ApiNode`](../classes/ApiNode.md)[]

#### Defined in

[getNodesWithOptions.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-33)

___

### reverse

• `Optional` **reverse**: `boolean`

#### Defined in

[getNodesWithOptions.ts:34](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-34)

___

### sort

• `Optional` **sort**: [`PropertyKey`](../modules.md#propertykey) \| [`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Defined in

[getNodesWithOptions.ts:31](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/getNodesWithOptions.ts#lines-31)
