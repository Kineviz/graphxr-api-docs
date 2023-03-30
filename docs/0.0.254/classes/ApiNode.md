[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ApiNode

# Class: ApiNode

## Table of contents

### Constructors

- [constructor](ApiNode.md#constructor)

### Properties

- [category](ApiNode.md#category)
- [collection](ApiNode.md#collection)
- [graph](ApiNode.md#graph)
- [id](ApiNode.md#id)
- [legacyNode](ApiNode.md#legacynode)
- [properties](ApiNode.md#properties)

### Accessors

- [visible](ApiNode.md#visible)

### Methods

- [clone](ApiNode.md#clone)
- [equals](ApiNode.md#equals)
- [getStyle](ApiNode.md#getstyle)
- [getStyles](ApiNode.md#getstyles)
- [setStyle](ApiNode.md#setstyle)
- [setStyles](ApiNode.md#setstyles)

## Constructors

### constructor

• **new ApiNode**(`id`, `category`, `properties`, `collection?`, `legacyNode?`, `graph?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `category` | [`CategoryId`](../modules.md#categoryid) |
| `properties` | [`Properties`](../modules.md#properties) |
| `collection?` | `NodeCollection` |
| `legacyNode?` | [`LegacyNode`](../modules.md#legacynode) |
| `graph?` | [`LayoutGraph`](../interfaces/LayoutGraph.md) |

#### Defined in

[apiNode.ts:20](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-20)

## Properties

### category

• `Readonly` **category**: [`CategoryId`](../modules.md#categoryid)

#### Defined in

[apiNode.ts:14](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-14)

___

### collection

• `Optional` **collection**: `NodeCollection`

#### Defined in

[apiNode.ts:16](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-16)

___

### graph

• `Optional` **graph**: [`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Defined in

[apiNode.ts:18](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-18)

___

### id

• `Readonly` **id**: [`NodeId`](../modules.md#nodeid)

#### Defined in

[apiNode.ts:13](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-13)

___

### legacyNode

• `Optional` **legacyNode**: [`LegacyNode`](../modules.md#legacynode)

#### Defined in

[apiNode.ts:17](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-17)

___

### properties

• **properties**: [`Properties`](../modules.md#properties)

#### Defined in

[apiNode.ts:15](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-15)

## Accessors

### visible

• `get` **visible**(): `boolean`

#### Returns

`boolean`

#### Defined in

[apiNode.ts:59](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-59)

## Methods

### clone

▸ **clone**(`updates?`): [`ApiNode`](ApiNode.md)

Identity

#### Parameters

| Name | Type |
| :------ | :------ |
| `updates?` | `Partial`<[`ApiNode`](ApiNode.md)\> |

#### Returns

[`ApiNode`](ApiNode.md)

#### Defined in

[apiNode.ts:66](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-66)

___

### equals

▸ **equals**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`ApiNode`](ApiNode.md) |

#### Returns

`boolean`

#### Defined in

[apiNode.ts:77](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-77)

___

### getStyle

▸ **getStyle**<`K`\>(`key`): [`NodeStyles`](../modules.md#nodestyles)[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`NodeStyles`](../modules.md#nodestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `K` |

#### Returns

[`NodeStyles`](../modules.md#nodestyles)[`K`]

#### Defined in

[apiNode.ts:49](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-49)

___

### getStyles

▸ **getStyles**(): `Partial`<[`NodeStyles`](../modules.md#nodestyles)\>

Styles

#### Returns

`Partial`<[`NodeStyles`](../modules.md#nodestyles)\>

#### Defined in

[apiNode.ts:39](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-39)

___

### setStyle

▸ **setStyle**<`K`\>(`key`, `value`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`NodeStyles`](../modules.md#nodestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `K` |
| `value` | [`NodeStyles`](../modules.md#nodestyles)[`K`] |

#### Returns

`void`

#### Defined in

[apiNode.ts:54](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-54)

___

### setStyles

▸ **setStyles**(`styles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `styles` | `Partial`<[`NodeStyles`](../modules.md#nodestyles)\> |

#### Returns

`void`

#### Defined in

[apiNode.ts:44](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiNode.ts#lines-44)
