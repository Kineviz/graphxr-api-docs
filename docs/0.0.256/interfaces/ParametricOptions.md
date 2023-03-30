[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ParametricOptions

# Interface: ParametricOptions

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

- `Partial`<`Pick`<[`AxesOptions`](AxesOptions.md), ``"showAxes"`` \| ``"showGrid"`` \| ``"scale"``\>\>

  ↳ **`ParametricOptions`**

## Table of contents

### Properties

- [filter](ParametricOptions.md#filter)
- [nodes](ParametricOptions.md#nodes)
- [reverse](ParametricOptions.md#reverse)
- [scale](ParametricOptions.md#scale)
- [showAxes](ParametricOptions.md#showaxes)
- [showGrid](ParametricOptions.md#showgrid)
- [sort](ParametricOptions.md#sort)
- [x](ParametricOptions.md#x)
- [y](ParametricOptions.md#y)
- [z](ParametricOptions.md#z)

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

### scale

• `Optional` **scale**: `number`

#### Inherited from

Partial.scale

#### Defined in

[layout/setParametricAxesOptions.ts:20](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/setParametricAxesOptions.ts#lines-20)

___

### showAxes

• `Optional` **showAxes**: `boolean`

#### Inherited from

Partial.showAxes

#### Defined in

[layout/setParametricAxesOptions.ts:18](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/setParametricAxesOptions.ts#lines-18)

___

### showGrid

• `Optional` **showGrid**: `boolean`

#### Inherited from

Partial.showGrid

#### Defined in

[layout/setParametricAxesOptions.ts:19](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/setParametricAxesOptions.ts#lines-19)

___

### sort

• `Optional` **sort**: [`PropertyKey`](../modules.md#propertykey) \| [`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[sort](NodeFilterOptions.md#sort)

#### Defined in

[getNodesWithOptions.ts:31](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/getNodesWithOptions.ts#lines-31)

___

### x

• `Optional` **x**: `number` \| [`PropertyKey`](../modules.md#propertykey) \| [`ParametricDimension`](ParametricDimension.md)

#### Defined in

[layout/parametric.ts:12](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/parametric.ts#lines-12)

___

### y

• `Optional` **y**: `number` \| [`PropertyKey`](../modules.md#propertykey) \| [`ParametricDimension`](ParametricDimension.md)

#### Defined in

[layout/parametric.ts:13](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/parametric.ts#lines-13)

___

### z

• `Optional` **z**: `number` \| [`PropertyKey`](../modules.md#propertykey) \| [`ParametricDimension`](ParametricDimension.md)

#### Defined in

[layout/parametric.ts:14](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layout/parametric.ts#lines-14)
