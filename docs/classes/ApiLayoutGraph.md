[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ApiLayoutGraph

# Class: ApiLayoutGraph

## Hierarchy

- [`BaseGraph`](BaseGraph.md)

  ↳ **`ApiLayoutGraph`**

## Implements

- [`LayoutGraph`](../interfaces/LayoutGraph.md)

## Table of contents

### Constructors

- [constructor](ApiLayoutGraph.md#constructor)

### Properties

- [edgeStyles](ApiLayoutGraph.md#edgestyles)
- [edges](ApiLayoutGraph.md#edges)
- [neighbors](ApiLayoutGraph.md#neighbors)
- [nodeStyles](ApiLayoutGraph.md#nodestyles)
- [nodes](ApiLayoutGraph.md#nodes)

### Methods

- [addEdge](ApiLayoutGraph.md#addedge)
- [addEdges](ApiLayoutGraph.md#addedges)
- [addNode](ApiLayoutGraph.md#addnode)
- [addNodes](ApiLayoutGraph.md#addnodes)
- [applyLayout](ApiLayoutGraph.md#applylayout)
- [applySnapshot](ApiLayoutGraph.md#applysnapshot)
- [applyTransform](ApiLayoutGraph.md#applytransform)
- [assign](ApiLayoutGraph.md#assign)
- [clear](ApiLayoutGraph.md#clear)
- [clone](ApiLayoutGraph.md#clone)
- [findNeighbors](ApiLayoutGraph.md#findneighbors)
- [getAllEdges](ApiLayoutGraph.md#getalledges)
- [getAllNodes](ApiLayoutGraph.md#getallnodes)
- [getEdge](ApiLayoutGraph.md#getedge)
- [getEdgeStyle](ApiLayoutGraph.md#getedgestyle)
- [getEdgeStyles](ApiLayoutGraph.md#getedgestyles)
- [getEdges](ApiLayoutGraph.md#getedges)
- [getNode](ApiLayoutGraph.md#getnode)
- [getNodeStyle](ApiLayoutGraph.md#getnodestyle)
- [getNodeStyles](ApiLayoutGraph.md#getnodestyles)
- [getNodes](ApiLayoutGraph.md#getnodes)
- [getSnapshot](ApiLayoutGraph.md#getsnapshot)
- [getVisibleEdges](ApiLayoutGraph.md#getvisibleedges)
- [getVisibleNodes](ApiLayoutGraph.md#getvisiblenodes)
- [hideEdges](ApiLayoutGraph.md#hideedges)
- [hideNodes](ApiLayoutGraph.md#hidenodes)
- [merge](ApiLayoutGraph.md#merge)
- [removeEdge](ApiLayoutGraph.md#removeedge)
- [removeEdges](ApiLayoutGraph.md#removeedges)
- [removeNode](ApiLayoutGraph.md#removenode)
- [removeNodes](ApiLayoutGraph.md#removenodes)
- [replace](ApiLayoutGraph.md#replace)
- [setEdgeProperties](ApiLayoutGraph.md#setedgeproperties)
- [setEdgeStyle](ApiLayoutGraph.md#setedgestyle)
- [setEdgeStyles](ApiLayoutGraph.md#setedgestyles)
- [setNodeCategory](ApiLayoutGraph.md#setnodecategory)
- [setNodeCollection](ApiLayoutGraph.md#setnodecollection)
- [setNodeProperties](ApiLayoutGraph.md#setnodeproperties)
- [setNodeStyle](ApiLayoutGraph.md#setnodestyle)
- [setNodeStyles](ApiLayoutGraph.md#setnodestyles)
- [showEdges](ApiLayoutGraph.md#showedges)
- [showNodes](ApiLayoutGraph.md#shownodes)

## Constructors

### constructor

• **new ApiLayoutGraph**()

#### Overrides

[BaseGraph](BaseGraph.md).[constructor](BaseGraph.md#constructor)

#### Defined in

[apiLayoutGraph.ts:28](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-28)

## Properties

### edgeStyles

• **edgeStyles**: `Record`<[`EdgeId`](../modules.md#edgeid), [`EdgeStyles`](../modules.md#edgestyles)\>

#### Defined in

[apiLayoutGraph.ts:25](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-25)

___

### edges

• **edges**: `Record`<[`EdgeId`](../modules.md#edgeid), [`ApiEdge`](ApiEdge.md)\>

#### Defined in

[apiLayoutGraph.ts:20](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-20)

___

### neighbors

• **neighbors**: `Record`<[`NodeId`](../modules.md#nodeid), `Neighbor`[]\>

#### Defined in

[apiLayoutGraph.ts:26](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-26)

___

### nodeStyles

• **nodeStyles**: `Record`<[`NodeId`](../modules.md#nodeid), [`NodeStyles`](../modules.md#nodestyles)\>

#### Defined in

[apiLayoutGraph.ts:24](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-24)

___

### nodes

• **nodes**: `Object`

#### Index signature

▪ [id: [`NodeId`](../modules.md#nodeid)]: [`ApiNode`](ApiNode.md)

#### Defined in

[apiLayoutGraph.ts:21](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-21)

## Methods

### addEdge

▸ **addEdge**(`edge`, `styles?`): [`ApiEdge`](ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `edge` | [`ApiEdge`](ApiEdge.md) |
| `styles?` | `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\> |

#### Returns

[`ApiEdge`](ApiEdge.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addEdge](../interfaces/LayoutGraph.md#addedge)

#### Overrides

[BaseGraph](BaseGraph.md).[addEdge](BaseGraph.md#addedge)

#### Defined in

[apiLayoutGraph.ts:144](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-144)

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

[apiLayoutGraph.ts:173](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-173)

___

### addNode

▸ **addNode**(`node`, `styles?`): [`ApiNode`](ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`ApiNode`](ApiNode.md) |
| `styles?` | `Partial`<[`NodeStyles`](../modules.md#nodestyles)\> |

#### Returns

[`ApiNode`](ApiNode.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addNode](../interfaces/LayoutGraph.md#addnode)

#### Overrides

[BaseGraph](BaseGraph.md).[addNode](BaseGraph.md#addnode)

#### Defined in

[apiLayoutGraph.ts:54](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-54)

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

[apiLayoutGraph.ts:82](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-82)

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

[layoutGraph.ts:112](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-112)

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

[apiLayoutGraph.ts:293](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-293)

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

#### Inherited from

[BaseGraph](BaseGraph.md).[applyTransform](BaseGraph.md#applytransform)

#### Defined in

[layoutGraph.ts:116](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-116)

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

[layoutGraph.ts:127](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-127)

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

[apiLayoutGraph.ts:276](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-276)

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

[apiLayoutGraph.ts:269](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-269)

___

### findNeighbors

▸ **findNeighbors**(`id`, `options?`): `Neighbor`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | [`NodeId`](../modules.md#nodeid) |
| `options` | `FindNeighborsOptions` |

#### Returns

`Neighbor`[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[findNeighbors](../interfaces/LayoutGraph.md#findneighbors)

#### Overrides

[BaseGraph](BaseGraph.md).[findNeighbors](BaseGraph.md#findneighbors)

#### Defined in

[apiLayoutGraph.ts:284](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-284)

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

[apiLayoutGraph.ts:127](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-127)

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

[apiLayoutGraph.ts:37](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-37)

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

[apiLayoutGraph.ts:140](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-140)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdgeStyle](../interfaces/LayoutGraph.md#getedgestyle)

#### Overrides

[BaseGraph](BaseGraph.md).[getEdgeStyle](BaseGraph.md#getedgestyle)

#### Defined in

[apiLayoutGraph.ts:225](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-225)

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

[apiLayoutGraph.ts:234](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-234)

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

[apiLayoutGraph.ts:131](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-131)

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

[apiLayoutGraph.ts:50](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-50)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNodeStyle](../interfaces/LayoutGraph.md#getnodestyle)

#### Overrides

[BaseGraph](BaseGraph.md).[getNodeStyle](BaseGraph.md#getnodestyle)

#### Defined in

[apiLayoutGraph.ts:205](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-205)

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

[apiLayoutGraph.ts:215](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-215)

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

[apiLayoutGraph.ts:41](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-41)

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

[layoutGraph.ts:359](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-359)

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

[apiLayoutGraph.ts:136](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-136)

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

[apiLayoutGraph.ts:46](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-46)

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

[apiLayoutGraph.ts:257](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-257)

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

[apiLayoutGraph.ts:244](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-244)

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

[layoutGraph.ts:152](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-152)

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

[apiLayoutGraph.ts:178](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-178)

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

[apiLayoutGraph.ts:193](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-193)

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

[apiLayoutGraph.ts:86](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-86)

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

[apiLayoutGraph.ts:100](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-100)

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

[layoutGraph.ts:137](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/layoutGraph.ts#lines-137)

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

[apiLayoutGraph.ts:197](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-197)

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

[apiLayoutGraph.ts:230](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-230)

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

[apiLayoutGraph.ts:239](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-239)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeCategory](../interfaces/LayoutGraph.md#setnodecategory)

#### Overrides

[BaseGraph](BaseGraph.md).[setNodeCategory](BaseGraph.md#setnodecategory)

#### Defined in

[apiLayoutGraph.ts:111](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-111)

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

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeCollection](../interfaces/LayoutGraph.md#setnodecollection)

#### Overrides

[BaseGraph](BaseGraph.md).[setNodeCollection](BaseGraph.md#setnodecollection)

#### Defined in

[apiLayoutGraph.ts:118](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-118)

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

[apiLayoutGraph.ts:104](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-104)

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

[apiLayoutGraph.ts:210](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-210)

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

[apiLayoutGraph.ts:220](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-220)

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

[apiLayoutGraph.ts:263](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-263)

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

[apiLayoutGraph.ts:253](https://bitbucket.org/kineviz/graphxr-api/src/3b69512/src/apiLayoutGraph.ts#lines-253)
