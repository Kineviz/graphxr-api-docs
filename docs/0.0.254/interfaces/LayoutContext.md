[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / LayoutContext

# Interface: LayoutContext

## Table of contents

### Properties

- [channels](LayoutContext.md#channels)
- [initial](LayoutContext.md#initial)
- [nodes](LayoutContext.md#nodes)
- [view](LayoutContext.md#view)

### Methods

- [makeResult](LayoutContext.md#makeresult)

## Properties

### channels

• **channels**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `initial` | `Record`<``"x"`` \| ``"y"`` \| ``"z"``, `Channel`<`number`\>\> |
| `property` | `Record`<[`PropertyKey`](../modules.md#propertykey), `Channel`<`any`\>\> |

#### Defined in

[layout/layout.ts:36](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layout/layout.ts#lines-36)

___

### initial

• **initial**: [`NodeIdToPosition`](../modules.md#nodeidtoposition)

#### Defined in

[layout/layout.ts:35](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layout/layout.ts#lines-35)

___

### nodes

• **nodes**: [`ApiNode`](../classes/ApiNode.md)[]

#### Defined in

[layout/layout.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layout/layout.ts#lines-33)

___

### view

• **view**: [`LayoutGraph`](LayoutGraph.md)

#### Defined in

[layout/layout.ts:34](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layout/layout.ts#lines-34)

## Methods

### makeResult

▸ **makeResult**(`computePosition`): [`NodeIdToPosition`](../modules.md#nodeidtoposition)

#### Parameters

| Name | Type |
| :------ | :------ |
| `computePosition` | `ComputePosition` |

#### Returns

[`NodeIdToPosition`](../modules.md#nodeidtoposition)

#### Defined in

[layout/layout.ts:40](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layout/layout.ts#lines-40)
