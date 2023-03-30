[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ApiEdge

# Class: ApiEdge

## Table of contents

### Constructors

- [constructor](ApiEdge.md#constructor)

### Properties

- [\_neo4jID](ApiEdge.md#_neo4jid)
- [graph](ApiEdge.md#graph)
- [properties](ApiEdge.md#properties)
- [relationship](ApiEdge.md#relationship)
- [sourceId](ApiEdge.md#sourceid)
- [targetId](ApiEdge.md#targetid)
- [uid](ApiEdge.md#uid)

### Accessors

- [id](ApiEdge.md#id)
- [visible](ApiEdge.md#visible)

### Methods

- [clone](ApiEdge.md#clone)
- [equals](ApiEdge.md#equals)
- [generateUid](ApiEdge.md#generateuid)
- [getStyle](ApiEdge.md#getstyle)
- [getStyles](ApiEdge.md#getstyles)
- [setStyle](ApiEdge.md#setstyle)
- [setStyles](ApiEdge.md#setstyles)

## Constructors

### constructor

• **new ApiEdge**(`sourceId`, `targetId`, `relationship`, `properties`, `uid?`, `_neo4jID?`, `graph?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `sourceId` | [`NodeId`](../modules.md#nodeid) |
| `targetId` | [`NodeId`](../modules.md#nodeid) |
| `relationship` | [`RelationshipId`](../modules.md#relationshipid) |
| `properties` | [`Properties`](../modules.md#properties) |
| `uid?` | `string` |
| `_neo4jID?` | `string` |
| `graph?` | [`LayoutGraph`](../interfaces/LayoutGraph.md) |

#### Defined in

[apiEdge.ts:21](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-21)

## Properties

### \_neo4jID

• `Optional` **\_neo4jID**: `string`

#### Defined in

[apiEdge.ts:19](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-19)

___

### graph

• `Optional` **graph**: [`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Defined in

[apiEdge.ts:18](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-18)

___

### properties

• **properties**: [`Properties`](../modules.md#properties)

#### Defined in

[apiEdge.ts:17](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-17)

___

### relationship

• **relationship**: [`RelationshipId`](../modules.md#relationshipid)

#### Defined in

[apiEdge.ts:16](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-16)

___

### sourceId

• `Readonly` **sourceId**: [`NodeId`](../modules.md#nodeid)

#### Defined in

[apiEdge.ts:13](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-13)

___

### targetId

• `Readonly` **targetId**: [`NodeId`](../modules.md#nodeid)

#### Defined in

[apiEdge.ts:14](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-14)

___

### uid

• **uid**: `string`

#### Defined in

[apiEdge.ts:15](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-15)

## Accessors

### id

• `get` **id**(): [`EdgeId`](../modules.md#edgeid)

#### Returns

[`EdgeId`](../modules.md#edgeid)

#### Defined in

[apiEdge.ts:98](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-98)

___

### visible

• `get` **visible**(): `boolean`

#### Returns

`boolean`

#### Defined in

[apiEdge.ts:62](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-62)

## Methods

### clone

▸ **clone**(): [`ApiEdge`](ApiEdge.md)

Identity

#### Returns

[`ApiEdge`](ApiEdge.md)

#### Defined in

[apiEdge.ts:69](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-69)

___

### equals

▸ **equals**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`ApiEdge`](ApiEdge.md) |

#### Returns

`boolean`

#### Defined in

[apiEdge.ts:81](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-81)

___

### generateUid

▸ **generateUid**(): `string`

#### Returns

`string`

#### Defined in

[apiEdge.ts:94](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-94)

___

### getStyle

▸ **getStyle**<`K`\>(`key`): [`EdgeStyles`](../modules.md#edgestyles)[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`EdgeStyles`](../modules.md#edgestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `K` |

#### Returns

[`EdgeStyles`](../modules.md#edgestyles)[`K`]

#### Defined in

[apiEdge.ts:52](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-52)

___

### getStyles

▸ **getStyles**(): `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>

Styles

#### Returns

`Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>

#### Defined in

[apiEdge.ts:42](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-42)

___

### setStyle

▸ **setStyle**<`K`\>(`key`, `value`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`EdgeStyles`](../modules.md#edgestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `K` |
| `value` | [`EdgeStyles`](../modules.md#edgestyles)[`K`] |

#### Returns

`void`

#### Defined in

[apiEdge.ts:57](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-57)

___

### setStyles

▸ **setStyles**(`styles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `styles` | `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\> |

#### Returns

`void`

#### Defined in

[apiEdge.ts:47](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiEdge.ts#lines-47)
