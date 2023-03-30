[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / LegacyLayoutGraph

# Class: LegacyLayoutGraph

## Hierarchy

- [`BaseGraph`](BaseGraph.md)

  ↳ **`LegacyLayoutGraph`**

## Implements

- [`LayoutGraph`](../interfaces/LayoutGraph.md)

## Table of contents

### Constructors

- [constructor](LegacyLayoutGraph.md#constructor)

### Properties

- [graph](LegacyLayoutGraph.md#graph)

### Methods

- [addEdge](LegacyLayoutGraph.md#addedge)
- [addEdges](LegacyLayoutGraph.md#addedges)
- [addNode](LegacyLayoutGraph.md#addnode)
- [addNodes](LegacyLayoutGraph.md#addnodes)
- [applyLayout](LegacyLayoutGraph.md#applylayout)
- [applySnapshot](LegacyLayoutGraph.md#applysnapshot)
- [applyTransform](LegacyLayoutGraph.md#applytransform)
- [assign](LegacyLayoutGraph.md#assign)
- [clear](LegacyLayoutGraph.md#clear)
- [clone](LegacyLayoutGraph.md#clone)
- [findNeighbors](LegacyLayoutGraph.md#findneighbors)
- [getAllEdges](LegacyLayoutGraph.md#getalledges)
- [getAllNodes](LegacyLayoutGraph.md#getallnodes)
- [getEdge](LegacyLayoutGraph.md#getedge)
- [getEdgeStyle](LegacyLayoutGraph.md#getedgestyle)
- [getEdgeStyles](LegacyLayoutGraph.md#getedgestyles)
- [getEdges](LegacyLayoutGraph.md#getedges)
- [getNode](LegacyLayoutGraph.md#getnode)
- [getNodeStyle](LegacyLayoutGraph.md#getnodestyle)
- [getNodeStyles](LegacyLayoutGraph.md#getnodestyles)
- [getNodes](LegacyLayoutGraph.md#getnodes)
- [getSnapshot](LegacyLayoutGraph.md#getsnapshot)
- [getVisibleEdges](LegacyLayoutGraph.md#getvisibleedges)
- [getVisibleNodes](LegacyLayoutGraph.md#getvisiblenodes)
- [hideEdges](LegacyLayoutGraph.md#hideedges)
- [hideNodes](LegacyLayoutGraph.md#hidenodes)
- [merge](LegacyLayoutGraph.md#merge)
- [removeEdge](LegacyLayoutGraph.md#removeedge)
- [removeEdges](LegacyLayoutGraph.md#removeedges)
- [removeNode](LegacyLayoutGraph.md#removenode)
- [removeNodes](LegacyLayoutGraph.md#removenodes)
- [replace](LegacyLayoutGraph.md#replace)
- [setEdgeProperties](LegacyLayoutGraph.md#setedgeproperties)
- [setEdgeStyle](LegacyLayoutGraph.md#setedgestyle)
- [setEdgeStyles](LegacyLayoutGraph.md#setedgestyles)
- [setNodeCategory](LegacyLayoutGraph.md#setnodecategory)
- [setNodeCollection](LegacyLayoutGraph.md#setnodecollection)
- [setNodeProperties](LegacyLayoutGraph.md#setnodeproperties)
- [setNodeStyle](LegacyLayoutGraph.md#setnodestyle)
- [setNodeStyles](LegacyLayoutGraph.md#setnodestyles)
- [showEdges](LegacyLayoutGraph.md#showedges)
- [showNodes](LegacyLayoutGraph.md#shownodes)
- [toApiEdge](LegacyLayoutGraph.md#toapiedge)
- [toApiNode](LegacyLayoutGraph.md#toapinode)
- [toLegacyEdge](LegacyLayoutGraph.md#tolegacyedge)
- [toLegacyNode](LegacyLayoutGraph.md#tolegacynode)

## Constructors

### constructor

• **new LegacyLayoutGraph**(`graph`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LegacyGraph`](../interfaces/LegacyGraph.md) |

#### Overrides

[BaseGraph](BaseGraph.md).[constructor](BaseGraph.md#constructor)

#### Defined in

[legacyLayoutGraph.ts:30](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-30)

## Properties

### graph

• `Private` **graph**: [`LegacyGraph`](../interfaces/LegacyGraph.md)

#### Defined in

[legacyLayoutGraph.ts:28](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-28)

## Methods

### addEdge

▸ **addEdge**(`edge`): [`ApiEdge`](ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `edge` | [`ApiEdge`](ApiEdge.md) |

#### Returns

[`ApiEdge`](ApiEdge.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addEdge](../interfaces/LayoutGraph.md#addedge)

#### Overrides

[BaseGraph](BaseGraph.md).[addEdge](BaseGraph.md#addedge)

#### Defined in

[legacyLayoutGraph.ts:209](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-209)

___

### addEdges

▸ **addEdges**(`edges`): [`ApiEdge`](ApiEdge.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `edges` | [`ApiEdge`](ApiEdge.md)[] |

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addEdges](../interfaces/LayoutGraph.md#addedges)

#### Overrides

[BaseGraph](BaseGraph.md).[addEdges](BaseGraph.md#addedges)

#### Defined in

[legacyLayoutGraph.ts:197](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-197)

___

### addNode

▸ **addNode**(`node`): [`ApiNode`](ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`ApiNode`](ApiNode.md) |

#### Returns

[`ApiNode`](ApiNode.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addNode](../interfaces/LayoutGraph.md#addnode)

#### Overrides

[BaseGraph](BaseGraph.md).[addNode](BaseGraph.md#addnode)

#### Defined in

[legacyLayoutGraph.ts:90](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-90)

___

### addNodes

▸ **addNodes**(`nodes`): [`ApiNode`](ApiNode.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `nodes` | [`ApiNode`](ApiNode.md)[] |

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addNodes](../interfaces/LayoutGraph.md#addnodes)

#### Overrides

[BaseGraph](BaseGraph.md).[addNodes](BaseGraph.md#addnodes)

#### Defined in

[legacyLayoutGraph.ts:86](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-86)

___

### applyLayout

▸ **applyLayout**(`computeLayout`, `tweenOverrides?`): `Promise`<[`NodeIdToPosition`](../modules.md#nodeidtoposition)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `computeLayout` | [`LayoutFunction`](../modules.md#layoutfunction) |
| `tweenOverrides?` | `Partial`<`TweenLayoutOptions`\> |

#### Returns

`Promise`<[`NodeIdToPosition`](../modules.md#nodeidtoposition)\>

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[applyLayout](../interfaces/LayoutGraph.md#applylayout)

#### Inherited from

[BaseGraph](BaseGraph.md).[applyLayout](BaseGraph.md#applylayout)

#### Defined in

[layoutGraph.ts:112](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layoutGraph.ts#lines-112)

___

### applySnapshot

▸ **applySnapshot**(`snapshot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `snapshot` | `GraphSnapshot` |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[applySnapshot](../interfaces/LayoutGraph.md#applysnapshot)

#### Overrides

[BaseGraph](BaseGraph.md).[applySnapshot](BaseGraph.md#applysnapshot)

#### Defined in

[legacyLayoutGraph.ts:370](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-370)

___

### applyTransform

▸ **applyTransform**(`transform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `transform` | `TransformFunction` |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[applyTransform](../interfaces/LayoutGraph.md#applytransform)

#### Overrides

[BaseGraph](BaseGraph.md).[applyTransform](BaseGraph.md#applytransform)

#### Defined in

[legacyLayoutGraph.ts:247](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-247)

___

### assign

▸ **assign**(`source`): [`LayoutGraph`](../interfaces/LayoutGraph.md)

`assign` copies the source graph into this graph, similar to Object.assign(target, source).
`assign` uses Object.assign to merge properties and replaces node styles.
Useful when you get a Neo4j result and want to overlay it on the graph workspace.

#### Parameters

| Name | Type |
| :------ | :------ |
| `source` | [`LayoutGraph`](../interfaces/LayoutGraph.md) |

#### Returns

[`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[assign](../interfaces/LayoutGraph.md#assign)

#### Inherited from

[BaseGraph](BaseGraph.md).[assign](BaseGraph.md#assign)

#### Defined in

[layoutGraph.ts:127](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layoutGraph.ts#lines-127)

___

### clear

▸ **clear**(): `void`

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[clear](../interfaces/LayoutGraph.md#clear)

#### Overrides

[BaseGraph](BaseGraph.md).[clear](BaseGraph.md#clear)

#### Defined in

[legacyLayoutGraph.ts:35](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-35)

___

### clone

▸ **clone**(): [`ApiLayoutGraph`](ApiLayoutGraph.md)

#### Returns

[`ApiLayoutGraph`](ApiLayoutGraph.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[clone](../interfaces/LayoutGraph.md#clone)

#### Overrides

[BaseGraph](BaseGraph.md).[clone](BaseGraph.md#clone)

#### Defined in

[legacyLayoutGraph.ts:230](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-230)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[findNeighbors](../interfaces/LayoutGraph.md#findneighbors)

#### Overrides

[BaseGraph](BaseGraph.md).[findNeighbors](BaseGraph.md#findneighbors)

#### Defined in

[legacyLayoutGraph.ts:366](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-366)

___

### getAllEdges

▸ **getAllEdges**(): [`ApiEdge`](ApiEdge.md)[]

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getAllEdges](../interfaces/LayoutGraph.md#getalledges)

#### Overrides

[BaseGraph](BaseGraph.md).[getAllEdges](BaseGraph.md#getalledges)

#### Defined in

[legacyLayoutGraph.ts:147](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-147)

___

### getAllNodes

▸ **getAllNodes**(): [`ApiNode`](ApiNode.md)[]

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getAllNodes](../interfaces/LayoutGraph.md#getallnodes)

#### Overrides

[BaseGraph](BaseGraph.md).[getAllNodes](BaseGraph.md#getallnodes)

#### Defined in

[legacyLayoutGraph.ts:39](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-39)

___

### getEdge

▸ **getEdge**(`id`): `undefined` \| [`ApiEdge`](ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |

#### Returns

`undefined` \| [`ApiEdge`](ApiEdge.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdge](../interfaces/LayoutGraph.md#getedge)

#### Overrides

[BaseGraph](BaseGraph.md).[getEdge](BaseGraph.md#getedge)

#### Defined in

[legacyLayoutGraph.ts:160](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-160)

___

### getEdgeStyle

▸ **getEdgeStyle**<`K`\>(`id`, `key`): [`EdgeStyles`](../modules.md#edgestyles)[`K`]

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

[`EdgeStyles`](../modules.md#edgestyles)[`K`]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdgeStyle](../interfaces/LayoutGraph.md#getedgestyle)

#### Overrides

[BaseGraph](BaseGraph.md).[getEdgeStyle](BaseGraph.md#getedgestyle)

#### Defined in

[legacyLayoutGraph.ts:310](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-310)

___

### getEdgeStyles

▸ **getEdgeStyles**(`id`): `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |

#### Returns

`Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdgeStyles](../interfaces/LayoutGraph.md#getedgestyles)

#### Overrides

[BaseGraph](BaseGraph.md).[getEdgeStyles](BaseGraph.md#getedgestyles)

#### Defined in

[legacyLayoutGraph.ts:304](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-304)

___

### getEdges

▸ **getEdges**(): [`ApiEdge`](ApiEdge.md)[]

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdges](../interfaces/LayoutGraph.md#getedges)

#### Overrides

[BaseGraph](BaseGraph.md).[getEdges](BaseGraph.md#getedges)

#### Defined in

[legacyLayoutGraph.ts:151](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-151)

___

### getNode

▸ **getNode**(`id`): `undefined` \| [`ApiNode`](ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |

#### Returns

`undefined` \| [`ApiNode`](ApiNode.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNode](../interfaces/LayoutGraph.md#getnode)

#### Overrides

[BaseGraph](BaseGraph.md).[getNode](BaseGraph.md#getnode)

#### Defined in

[legacyLayoutGraph.ts:52](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-52)

___

### getNodeStyle

▸ **getNodeStyle**<`K`\>(`id`, `key`): [`NodeStyles`](../modules.md#nodestyles)[`K`]

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

[`NodeStyles`](../modules.md#nodestyles)[`K`]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNodeStyle](../interfaces/LayoutGraph.md#getnodestyle)

#### Overrides

[BaseGraph](BaseGraph.md).[getNodeStyle](BaseGraph.md#getnodestyle)

#### Defined in

[legacyLayoutGraph.ts:270](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-270)

___

### getNodeStyles

▸ **getNodeStyles**(`id`): `Partial`<[`NodeStyles`](../modules.md#nodestyles)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |

#### Returns

`Partial`<[`NodeStyles`](../modules.md#nodestyles)\>

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNodeStyles](../interfaces/LayoutGraph.md#getnodestyles)

#### Overrides

[BaseGraph](BaseGraph.md).[getNodeStyles](BaseGraph.md#getnodestyles)

#### Defined in

[legacyLayoutGraph.ts:256](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-256)

___

### getNodes

▸ **getNodes**(): [`ApiNode`](ApiNode.md)[]

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNodes](../interfaces/LayoutGraph.md#getnodes)

#### Overrides

[BaseGraph](BaseGraph.md).[getNodes](BaseGraph.md#getnodes)

#### Defined in

[legacyLayoutGraph.ts:43](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-43)

___

### getSnapshot

▸ **getSnapshot**(`partialOptions?`): `GraphSnapshot`

#### Parameters

| Name | Type |
| :------ | :------ |
| `partialOptions` | `GraphSnapshotOptions` |

#### Returns

`GraphSnapshot`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getSnapshot](../interfaces/LayoutGraph.md#getsnapshot)

#### Inherited from

[BaseGraph](BaseGraph.md).[getSnapshot](BaseGraph.md#getsnapshot)

#### Defined in

[layoutGraph.ts:359](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layoutGraph.ts#lines-359)

___

### getVisibleEdges

▸ **getVisibleEdges**(): [`ApiEdge`](ApiEdge.md)[]

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getVisibleEdges](../interfaces/LayoutGraph.md#getvisibleedges)

#### Overrides

[BaseGraph](BaseGraph.md).[getVisibleEdges](BaseGraph.md#getvisibleedges)

#### Defined in

[legacyLayoutGraph.ts:156](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-156)

___

### getVisibleNodes

▸ **getVisibleNodes**(): [`ApiNode`](ApiNode.md)[]

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getVisibleNodes](../interfaces/LayoutGraph.md#getvisiblenodes)

#### Overrides

[BaseGraph](BaseGraph.md).[getVisibleNodes](BaseGraph.md#getvisiblenodes)

#### Defined in

[legacyLayoutGraph.ts:48](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-48)

___

### hideEdges

▸ **hideEdges**(`ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`EdgeId`](../modules.md#edgeid)[] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[hideEdges](../interfaces/LayoutGraph.md#hideedges)

#### Overrides

[BaseGraph](BaseGraph.md).[hideEdges](BaseGraph.md#hideedges)

#### Defined in

[legacyLayoutGraph.ts:356](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-356)

___

### hideNodes

▸ **hideNodes**(`ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`NodeId`](../modules.md#nodeid)[] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[hideNodes](../interfaces/LayoutGraph.md#hidenodes)

#### Overrides

[BaseGraph](BaseGraph.md).[hideNodes](BaseGraph.md#hidenodes)

#### Defined in

[legacyLayoutGraph.ts:336](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-336)

___

### merge

▸ **merge**(`source`, `options?`): [`LayoutGraph`](../interfaces/LayoutGraph.md)

`merge` takes a source graph and merges it into this graph.
New nodes and edges from the source graph are added.
Attributes (e.g. `properties`, `styles`, `category`) of nodes with same id are copied.
Attributes (e.g. `properties`, `styles`, `relationship`) of edges with same id are copied.
If deleteMissingNodesAndEdges is true, then any nodes and edges in the source graph that are not in the target graph (this graph) will be **deleted**.
If deleteMissingNodesAndEdges is false, then any nodes and edges in the source graph that are not in the target graph (this graph) will be **kept**.

#### Parameters

| Name | Type |
| :------ | :------ |
| `source` | [`LayoutGraph`](../interfaces/LayoutGraph.md) |
| `options?` | [`GraphMergeOptions`](../interfaces/GraphMergeOptions.md) |

#### Returns

[`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[merge](../interfaces/LayoutGraph.md#merge)

#### Inherited from

[BaseGraph](BaseGraph.md).[merge](BaseGraph.md#merge)

#### Defined in

[layoutGraph.ts:152](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layoutGraph.ts#lines-152)

___

### removeEdge

▸ **removeEdge**(`id`): `undefined` \| [`ApiEdge`](ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`EdgeId`](../modules.md#edgeid) |

#### Returns

`undefined` \| [`ApiEdge`](ApiEdge.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[removeEdge](../interfaces/LayoutGraph.md#removeedge)

#### Overrides

[BaseGraph](BaseGraph.md).[removeEdge](BaseGraph.md#removeedge)

#### Defined in

[legacyLayoutGraph.ts:219](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-219)

___

### removeEdges

▸ **removeEdges**(`ids`): [`ApiEdge`](ApiEdge.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`EdgeId`](../modules.md#edgeid)[] |

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[removeEdges](../interfaces/LayoutGraph.md#removeedges)

#### Overrides

[BaseGraph](BaseGraph.md).[removeEdges](BaseGraph.md#removeedges)

#### Defined in

[legacyLayoutGraph.ts:213](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-213)

___

### removeNode

▸ **removeNode**(`id`): `undefined` \| [`ApiNode`](ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |

#### Returns

`undefined` \| [`ApiNode`](ApiNode.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[removeNode](../interfaces/LayoutGraph.md#removenode)

#### Overrides

[BaseGraph](BaseGraph.md).[removeNode](BaseGraph.md#removenode)

#### Defined in

[legacyLayoutGraph.ts:114](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-114)

___

### removeNodes

▸ **removeNodes**(`ids`): [`ApiNode`](ApiNode.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`NodeId`](../modules.md#nodeid)[] |

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[removeNodes](../interfaces/LayoutGraph.md#removenodes)

#### Overrides

[BaseGraph](BaseGraph.md).[removeNodes](BaseGraph.md#removenodes)

#### Defined in

[legacyLayoutGraph.ts:108](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-108)

___

### replace

▸ **replace**(`source`): [`LayoutGraph`](../interfaces/LayoutGraph.md)

Useful when you want to replace the target graph with another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `source` | [`LayoutGraph`](../interfaces/LayoutGraph.md) |

#### Returns

[`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[replace](../interfaces/LayoutGraph.md#replace)

#### Inherited from

[BaseGraph](BaseGraph.md).[replace](BaseGraph.md#replace)

#### Defined in

[layoutGraph.ts:137](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/layoutGraph.ts#lines-137)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setEdgeProperties](../interfaces/LayoutGraph.md#setedgeproperties)

#### Overrides

[BaseGraph](BaseGraph.md).[setEdgeProperties](BaseGraph.md#setedgeproperties)

#### Defined in

[legacyLayoutGraph.ts:224](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-224)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setEdgeStyle](../interfaces/LayoutGraph.md#setedgestyle)

#### Overrides

[BaseGraph](BaseGraph.md).[setEdgeStyle](BaseGraph.md#setedgestyle)

#### Defined in

[legacyLayoutGraph.ts:321](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-321)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setEdgeStyles](../interfaces/LayoutGraph.md#setedgestyles)

#### Overrides

[BaseGraph](BaseGraph.md).[setEdgeStyles](BaseGraph.md#setedgestyles)

#### Defined in

[legacyLayoutGraph.ts:296](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-296)

___

### setNodeCategory

▸ **setNodeCategory**(`id`, `category`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `string` |
| `category` | [`CategoryId`](../modules.md#categoryid) |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeCategory](../interfaces/LayoutGraph.md#setnodecategory)

#### Overrides

[BaseGraph](BaseGraph.md).[setNodeCategory](BaseGraph.md#setnodecategory)

#### Defined in

[legacyLayoutGraph.ts:125](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-125)

___

### setNodeCollection

▸ **setNodeCollection**(`id`, `collection`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `string` |
| `collection` | `NodeCollection` |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeCollection](../interfaces/LayoutGraph.md#setnodecollection)

#### Overrides

[BaseGraph](BaseGraph.md).[setNodeCollection](BaseGraph.md#setnodecollection)

#### Defined in

[legacyLayoutGraph.ts:132](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-132)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeProperties](../interfaces/LayoutGraph.md#setnodeproperties)

#### Overrides

[BaseGraph](BaseGraph.md).[setNodeProperties](BaseGraph.md#setnodeproperties)

#### Defined in

[legacyLayoutGraph.ts:119](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-119)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeStyle](../interfaces/LayoutGraph.md#setnodestyle)

#### Overrides

[BaseGraph](BaseGraph.md).[setNodeStyle](BaseGraph.md#setnodestyle)

#### Defined in

[legacyLayoutGraph.ts:281](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-281)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeStyles](../interfaces/LayoutGraph.md#setnodestyles)

#### Overrides

[BaseGraph](BaseGraph.md).[setNodeStyles](BaseGraph.md#setnodestyles)

#### Defined in

[legacyLayoutGraph.ts:262](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-262)

___

### showEdges

▸ **showEdges**(`ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`EdgeId`](../modules.md#edgeid)[] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[showEdges](../interfaces/LayoutGraph.md#showedges)

#### Overrides

[BaseGraph](BaseGraph.md).[showEdges](BaseGraph.md#showedges)

#### Defined in

[legacyLayoutGraph.ts:360](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-360)

___

### showNodes

▸ **showNodes**(`ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`NodeId`](../modules.md#nodeid)[] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[showNodes](../interfaces/LayoutGraph.md#shownodes)

#### Overrides

[BaseGraph](BaseGraph.md).[showNodes](BaseGraph.md#shownodes)

#### Defined in

[legacyLayoutGraph.ts:345](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-345)

___

### toApiEdge

▸ **toApiEdge**(`legacyEdge`): [`ApiEdge`](ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `legacyEdge` | [`LegacyEdge`](../modules.md#legacyedge) |

#### Returns

[`ApiEdge`](ApiEdge.md)

#### Defined in

[legacyLayoutGraph.ts:142](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-142)

___

### toApiNode

▸ **toApiNode**(`node`): [`ApiNode`](ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`LegacyNode`](../modules.md#legacynode) |

#### Returns

[`ApiNode`](ApiNode.md)

#### Defined in

[legacyLayoutGraph.ts:57](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-57)

___

### toLegacyEdge

▸ **toLegacyEdge**(`edge`, `styles?`): [`LegacyEdge`](../modules.md#legacyedge)

#### Parameters

| Name | Type |
| :------ | :------ |
| `edge` | [`ApiEdge`](ApiEdge.md) |
| `styles` | `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\> |

#### Returns

[`LegacyEdge`](../modules.md#legacyedge)

#### Defined in

[legacyLayoutGraph.ts:165](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-165)

___

### toLegacyNode

▸ **toLegacyNode**(`node`, `styles?`): [`LegacyNode`](../modules.md#legacynode)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`ApiNode`](ApiNode.md) |
| `styles` | `Partial`<[`NodeStyles`](../modules.md#nodestyles)\> |

#### Returns

[`LegacyNode`](../modules.md#legacynode)

#### Defined in

[legacyLayoutGraph.ts:61](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/legacyLayoutGraph.ts#lines-61)
