[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ShiftOptions

# Interface: ShiftOptions

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

  ↳ **`ShiftOptions`**

## Table of contents

### Properties

- [filter](ShiftOptions.md#filter)
- [nodes](ShiftOptions.md#nodes)
- [reverse](ShiftOptions.md#reverse)
- [sort](ShiftOptions.md#sort)
- [x](ShiftOptions.md#x)
- [y](ShiftOptions.md#y)
- [z](ShiftOptions.md#z)

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

### x

• `Optional` **x**: `number`

#### Defined in

[layout/shift.ts:6](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/shift.ts#lines-6)

___

### y

• `Optional` **y**: `number`

#### Defined in

[layout/shift.ts:7](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/shift.ts#lines-7)

___

### z

• `Optional` **z**: `number`

#### Defined in

[layout/shift.ts:8](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/shift.ts#lines-8)
