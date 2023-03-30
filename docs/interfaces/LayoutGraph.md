[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / LayoutGraph

# Interface: LayoutGraph

## Implemented by

- [`ApiLayoutGraph`](../classes/ApiLayoutGraph.md)
- [`BaseGraph`](../classes/BaseGraph.md)
- [`LegacyLayoutGraph`](../classes/LegacyLayoutGraph.md)

## Table of contents

### Methods

- [addEdge](LayoutGraph.md#addedge)
- [addEdges](LayoutGraph.md#addedges)
- [addNode](LayoutGraph.md#addnode)
- [addNodes](LayoutGraph.md#addnodes)
- [applyLayout](LayoutGraph.md#applylayout)
- [applySnapshot](LayoutGraph.md#applysnapshot)
- [applyTransform](LayoutGraph.md#applytransform)
- [assign](LayoutGraph.md#assign)
- [clear](LayoutGraph.md#clear)
- [clone](LayoutGraph.md#clone)
- [findNeighbors](LayoutGraph.md#findneighbors)
- [getAllEdges](LayoutGraph.md#getalledges)
- [getAllNodes](LayoutGraph.md#getallnodes)
- [getEdge](LayoutGraph.md#getedge)
- [getEdgeStyle](LayoutGraph.md#getedgestyle)
- [getEdgeStyles](LayoutGraph.md#getedgestyles)
- [getEdges](LayoutGraph.md#getedges)
- [getNode](LayoutGraph.md#getnode)
- [getNodeStyle](LayoutGraph.md#getnodestyle)
- [getNodeStyles](LayoutGraph.md#getnodestyles)
- [getNodes](LayoutGraph.md#getnodes)
- [getSnapshot](LayoutGraph.md#getsnapshot)
- [getVisibleEdges](LayoutGraph.md#getvisibleedges)
- [getVisibleNodes](LayoutGraph.md#getvisiblenodes)
- [hideEdges](LayoutGraph.md#hideedges)
- [hideNodes](LayoutGraph.md#hidenodes)
- [merge](LayoutGraph.md#merge)
- [removeEdge](LayoutGraph.md#removeedge)
- [removeEdges](LayoutGraph.md#removeedges)
- [removeNode](LayoutGraph.md#removenode)
- [removeNodes](LayoutGraph.md#removenodes)
- [replace](LayoutGraph.md#replace)
- [setEdgeProperties](LayoutGraph.md#setedgeproperties)
- [setEdgeStyle](LayoutGraph.md#setedgestyle)
- [setEdgeStyles](LayoutGraph.md#setedgestyles)
- [setNodeCategory](LayoutGraph.md#setnodecategory)
- [setNodeCollection](LayoutGraph.md#setnodecollection)
- [setNodeProperties](LayoutGraph.md#setnodeproperties)
- [setNodeStyle](LayoutGraph.md#setnodestyle)
- [setNodeStyles](LayoutGraph.md#setnodestyles)
- [showEdges](LayoutGraph.md#showedges)
- [showNodes](LayoutGraph.md#shownodes)

## Methods

### addEdge

▸ **addEdge**(`edge`): [`ApiEdge`](../classes/ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `edge` | [`ApiEdge`](../classes/ApiEdge.md) |

#### Returns

[`ApiEdge`](../classes/ApiEdge.md)

#### Defined in

[layoutGraph.ts:71](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-71)

___

### addEdges

▸ **addEdges**(`edges`): [`ApiEdge`](../classes/ApiEdge.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `edges` | [`ApiEdge`](../classes/ApiEdge.md)[] |

#### Returns

[`ApiEdge`](../classes/ApiEdge.md)[]

#### Defined in

[layoutGraph.ts:72](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-72)

___

### addNode

▸ **addNode**(`node`): [`ApiNode`](../classes/ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`ApiNode`](../classes/ApiNode.md) |

#### Returns

[`ApiNode`](../classes/ApiNode.md)

#### Defined in

[layoutGraph.ts:61](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-61)

___

### addNodes

▸ **addNodes**(`nodes`): [`ApiNode`](../classes/ApiNode.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `nodes` | [`ApiNode`](../classes/ApiNode.md)[] |

#### Returns

[`ApiNode`](../classes/ApiNode.md)[]

#### Defined in

[layoutGraph.ts:62](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-62)

___

### applyLayout

▸ **applyLayout**(`layout`, `tweenOverrides?`): `Promise`<[`NodeIdToPosition`](../modules.md#nodeidtoposition)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `layout` | [`LayoutFunction`](../modules.md#layoutfunction) |
| `tweenOverrides?` | `Partial`<`TweenLayoutOptions`\> |

#### Returns

`Promise`<[`NodeIdToPosition`](../modules.md#nodeidtoposition)\>

#### Defined in

[layoutGraph.ts:102](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-102)

___

### applySnapshot

▸ **applySnapshot**(`snapshot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `snapshot` | `GraphSnapshot` |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:67](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-67)

___

### applyTransform

▸ **applyTransform**(`transform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `transform` | `TransformFunction` |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:76](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-76)

___

### assign

▸ **assign**(`graph`): [`LayoutGraph`](LayoutGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |

#### Returns

[`LayoutGraph`](LayoutGraph.md)

#### Defined in

[layoutGraph.ts:77](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-77)

___

### clear

▸ **clear**(): `void`

#### Returns

`void`

#### Defined in

[layoutGraph.ts:55](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-55)

___

### clone

▸ **clone**(): [`LayoutGraph`](LayoutGraph.md)

#### Returns

[`LayoutGraph`](LayoutGraph.md)

#### Defined in

[layoutGraph.ts:56](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-56)

___

### findNeighbors

▸ **findNeighbors**(`id`, `options?`): `Neighbor`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `options?` | `FindNeighborsOptions` |

#### Returns

`Neighbor`[]

#### Defined in

[layoutGraph.ts:75](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-75)

___

### getAllEdges

▸ **getAllEdges**(): [`ApiEdge`](../classes/ApiEdge.md)[]

#### Returns

[`ApiEdge`](../classes/ApiEdge.md)[]

#### Defined in

[layoutGraph.ts:65](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-65)

___

### getAllNodes

▸ **getAllNodes**(): [`ApiNode`](../classes/ApiNode.md)[]

#### Returns

[`ApiNode`](../classes/ApiNode.md)[]

#### Defined in

[layoutGraph.ts:57](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-57)

___

### getEdge

▸ **getEdge**(`id`): `undefined` \| [`ApiEdge`](../classes/ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |

#### Returns

`undefined` \| [`ApiEdge`](../classes/ApiEdge.md)

#### Defined in

[layoutGraph.ts:70](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-70)

___

### getEdgeStyle

▸ **getEdgeStyle**<`K`\>(`id`, `key`): `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`EdgeStyles`](../modules.md#edgestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |
| `key` | `K` |

#### Returns

`Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>[`K`]

#### Defined in

[layoutGraph.ts:98](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-98)

___

### getEdgeStyles

▸ **getEdgeStyles**(`id`): `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |

#### Returns

`Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>

#### Defined in

[layoutGraph.ts:93](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-93)

___

### getEdges

▸ **getEdges**(): [`ApiEdge`](../classes/ApiEdge.md)[]

#### Returns

[`ApiEdge`](../classes/ApiEdge.md)[]

#### Defined in

[layoutGraph.ts:66](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-66)

___

### getNode

▸ **getNode**(`id`): `undefined` \| [`ApiNode`](../classes/ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |

#### Returns

`undefined` \| [`ApiNode`](../classes/ApiNode.md)

#### Defined in

[layoutGraph.ts:60](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-60)

___

### getNodeStyle

▸ **getNodeStyle**<`K`\>(`id`, `key`): `Partial`<[`NodeStyles`](../modules.md#nodestyles)\>[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`NodeStyles`](../modules.md#nodestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `key` | `K` |

#### Returns

`Partial`<[`NodeStyles`](../modules.md#nodestyles)\>[`K`]

#### Defined in

[layoutGraph.ts:96](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-96)

___

### getNodeStyles

▸ **getNodeStyles**(`id`): `Partial`<[`NodeStyles`](../modules.md#nodestyles)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |

#### Returns

`Partial`<[`NodeStyles`](../modules.md#nodestyles)\>

#### Defined in

[layoutGraph.ts:92](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-92)

___

### getNodes

▸ **getNodes**(): [`ApiNode`](../classes/ApiNode.md)[]

#### Returns

[`ApiNode`](../classes/ApiNode.md)[]

#### Defined in

[layoutGraph.ts:58](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-58)

___

### getSnapshot

▸ **getSnapshot**(`options?`): `GraphSnapshot`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `GraphSnapshotOptions` |

#### Returns

`GraphSnapshot`

#### Defined in

[layoutGraph.ts:68](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-68)

___

### getVisibleEdges

▸ **getVisibleEdges**(): [`ApiEdge`](../classes/ApiEdge.md)[]

#### Returns

[`ApiEdge`](../classes/ApiEdge.md)[]

#### Defined in

[layoutGraph.ts:69](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-69)

___

### getVisibleNodes

▸ **getVisibleNodes**(): [`ApiNode`](../classes/ApiNode.md)[]

#### Returns

[`ApiNode`](../classes/ApiNode.md)[]

#### Defined in

[layoutGraph.ts:59](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-59)

___

### hideEdges

▸ **hideEdges**(`ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`EdgeId`](../modules.md#edgeid)[] |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:108](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-108)

___

### hideNodes

▸ **hideNodes**(`ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`NodeId`](../modules.md#nodeid)[] |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:106](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-106)

___

### merge

▸ **merge**(`graph`, `options`): [`LayoutGraph`](LayoutGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |
| `options` | [`GraphMergeOptions`](GraphMergeOptions.md) |

#### Returns

[`LayoutGraph`](LayoutGraph.md)

#### Defined in

[layoutGraph.ts:79](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-79)

___

### removeEdge

▸ **removeEdge**(`id`): `undefined` \| [`ApiEdge`](../classes/ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |

#### Returns

`undefined` \| [`ApiEdge`](../classes/ApiEdge.md)

#### Defined in

[layoutGraph.ts:73](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-73)

___

### removeEdges

▸ **removeEdges**(`ids`): [`ApiEdge`](../classes/ApiEdge.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`EdgeId`](../modules.md#edgeid)[] |

#### Returns

[`ApiEdge`](../classes/ApiEdge.md)[]

#### Defined in

[layoutGraph.ts:74](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-74)

___

### removeNode

▸ **removeNode**(`id`): `undefined` \| [`ApiNode`](../classes/ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |

#### Returns

`undefined` \| [`ApiNode`](../classes/ApiNode.md)

#### Defined in

[layoutGraph.ts:63](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-63)

___

### removeNodes

▸ **removeNodes**(`ids`): [`ApiNode`](../classes/ApiNode.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`NodeId`](../modules.md#nodeid)[] |

#### Returns

[`ApiNode`](../classes/ApiNode.md)[]

#### Defined in

[layoutGraph.ts:64](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-64)

___

### replace

▸ **replace**(`graph`): [`LayoutGraph`](LayoutGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |

#### Returns

[`LayoutGraph`](LayoutGraph.md)

#### Defined in

[layoutGraph.ts:78](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-78)

___

### setEdgeProperties

▸ **setEdgeProperties**(`id`, `properties`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |
| `properties` | [`Properties`](../modules.md#properties) |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:89](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-89)

___

### setEdgeStyle

▸ **setEdgeStyle**<`K`\>(`id`, `key`, `value`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`EdgeStyles`](../modules.md#edgestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |
| `key` | `K` |
| `value` | [`EdgeStyles`](../modules.md#edgestyles)[`K`] |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:99](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-99)

___

### setEdgeStyles

▸ **setEdgeStyles**(`id`, `styles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |
| `styles` | `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\> |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:95](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-95)

___

### setNodeCategory

▸ **setNodeCategory**(`id`, `category`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `category` | [`CategoryId`](../modules.md#categoryid) |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:82](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-82)

___

### setNodeCollection

▸ **setNodeCollection**(`id`, `collection`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `collection` | `NodeCollection` |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:85](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-85)

___

### setNodeProperties

▸ **setNodeProperties**(`id`, `properties`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `properties` | [`Properties`](../modules.md#properties) |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:88](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-88)

___

### setNodeStyle

▸ **setNodeStyle**<`K`\>(`id`, `key`, `value`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`NodeStyles`](../modules.md#nodestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `key` | `K` |
| `value` | [`NodeStyles`](../modules.md#nodestyles)[`K`] |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:97](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-97)

___

### setNodeStyles

▸ **setNodeStyles**(`id`, `styles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `styles` | `Partial`<[`NodeStyles`](../modules.md#nodestyles)\> |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:94](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-94)

___

### showEdges

▸ **showEdges**(`ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`EdgeId`](../modules.md#edgeid)[] |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:107](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-107)

___

### showNodes

▸ **showNodes**(`ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`NodeId`](../modules.md#nodeid)[] |

#### Returns

`void`

#### Defined in

[layoutGraph.ts:105](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-105)
