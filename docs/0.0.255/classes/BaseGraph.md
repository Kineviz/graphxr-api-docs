[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / BaseGraph

# Class: BaseGraph

## Hierarchy

- **`BaseGraph`**

  ↳ [`ApiLayoutGraph`](ApiLayoutGraph.md)

  ↳ [`LegacyLayoutGraph`](LegacyLayoutGraph.md)

## Implements

- [`LayoutGraph`](../interfaces/LayoutGraph.md)

## Table of contents

### Constructors

- [constructor](BaseGraph.md#constructor)

### Methods

- [addEdge](BaseGraph.md#addedge)
- [addEdges](BaseGraph.md#addedges)
- [addNode](BaseGraph.md#addnode)
- [addNodes](BaseGraph.md#addnodes)
- [applyLayout](BaseGraph.md#applylayout)
- [applySnapshot](BaseGraph.md#applysnapshot)
- [applyTransform](BaseGraph.md#applytransform)
- [assign](BaseGraph.md#assign)
- [clear](BaseGraph.md#clear)
- [clone](BaseGraph.md#clone)
- [findNeighbors](BaseGraph.md#findneighbors)
- [getAllEdges](BaseGraph.md#getalledges)
- [getAllNodes](BaseGraph.md#getallnodes)
- [getEdge](BaseGraph.md#getedge)
- [getEdgeStyle](BaseGraph.md#getedgestyle)
- [getEdgeStyles](BaseGraph.md#getedgestyles)
- [getEdges](BaseGraph.md#getedges)
- [getNode](BaseGraph.md#getnode)
- [getNodeStyle](BaseGraph.md#getnodestyle)
- [getNodeStyles](BaseGraph.md#getnodestyles)
- [getNodes](BaseGraph.md#getnodes)
- [getSnapshot](BaseGraph.md#getsnapshot)
- [getVisibleEdges](BaseGraph.md#getvisibleedges)
- [getVisibleNodes](BaseGraph.md#getvisiblenodes)
- [hideEdges](BaseGraph.md#hideedges)
- [hideNodes](BaseGraph.md#hidenodes)
- [merge](BaseGraph.md#merge)
- [removeEdge](BaseGraph.md#removeedge)
- [removeEdges](BaseGraph.md#removeedges)
- [removeNode](BaseGraph.md#removenode)
- [removeNodes](BaseGraph.md#removenodes)
- [replace](BaseGraph.md#replace)
- [setEdgeProperties](BaseGraph.md#setedgeproperties)
- [setEdgeStyle](BaseGraph.md#setedgestyle)
- [setEdgeStyles](BaseGraph.md#setedgestyles)
- [setNodeCategory](BaseGraph.md#setnodecategory)
- [setNodeCollection](BaseGraph.md#setnodecollection)
- [setNodeProperties](BaseGraph.md#setnodeproperties)
- [setNodeStyle](BaseGraph.md#setnodestyle)
- [setNodeStyles](BaseGraph.md#setnodestyles)
- [showEdges](BaseGraph.md#showedges)
- [showNodes](BaseGraph.md#shownodes)

## Constructors

### constructor

• **new BaseGraph**()

## Methods

### addEdge

▸ **addEdge**(`_edge`): [`ApiEdge`](ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `_edge` | `Readonly`<[`ApiEdge`](ApiEdge.md)\> |

#### Returns

[`ApiEdge`](ApiEdge.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addEdge](../interfaces/LayoutGraph.md#addedge)

#### Defined in

[layoutGraph.ts:286](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-286)

___

### addEdges

▸ **addEdges**(`_edges`): [`ApiEdge`](ApiEdge.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `_edges` | `Readonly`<[`ApiEdge`](ApiEdge.md)\>[] |

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addEdges](../interfaces/LayoutGraph.md#addedges)

#### Defined in

[layoutGraph.ts:289](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-289)

___

### addNode

▸ **addNode**(`_node`): [`ApiNode`](ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `_node` | `Readonly`<[`ApiNode`](ApiNode.md)\> |

#### Returns

[`ApiNode`](ApiNode.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addNode](../interfaces/LayoutGraph.md#addnode)

#### Defined in

[layoutGraph.ts:265](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-265)

___

### addNodes

▸ **addNodes**(`_nodes`): [`ApiNode`](ApiNode.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `_nodes` | `Readonly`<[`ApiNode`](ApiNode.md)\>[] |

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[addNodes](../interfaces/LayoutGraph.md#addnodes)

#### Defined in

[layoutGraph.ts:268](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-268)

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

#### Defined in

[layoutGraph.ts:112](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-112)

___

### applySnapshot

▸ **applySnapshot**(`_snapshot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_snapshot` | `GraphSnapshot` |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[applySnapshot](../interfaces/LayoutGraph.md#applysnapshot)

#### Defined in

[layoutGraph.ts:355](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-355)

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

#### Defined in

[layoutGraph.ts:116](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-116)

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

#### Defined in

[layoutGraph.ts:127](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-127)

___

### clear

▸ **clear**(): `void`

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[clear](../interfaces/LayoutGraph.md#clear)

#### Defined in

[layoutGraph.ts:250](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-250)

___

### clone

▸ **clone**(): [`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Returns

[`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[clone](../interfaces/LayoutGraph.md#clone)

#### Defined in

[layoutGraph.ts:253](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-253)

___

### findNeighbors

▸ **findNeighbors**(`_id`, `_options?`): `Neighbor`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_options?` | `FindNeighborsOptions` |

#### Returns

`Neighbor`[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[findNeighbors](../interfaces/LayoutGraph.md#findneighbors)

#### Defined in

[layoutGraph.ts:298](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-298)

___

### getAllEdges

▸ **getAllEdges**(): [`ApiEdge`](ApiEdge.md)[]

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getAllEdges](../interfaces/LayoutGraph.md#getalledges)

#### Defined in

[layoutGraph.ts:277](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-277)

___

### getAllNodes

▸ **getAllNodes**(): [`ApiNode`](ApiNode.md)[]

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getAllNodes](../interfaces/LayoutGraph.md#getallnodes)

#### Defined in

[layoutGraph.ts:256](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-256)

___

### getEdge

▸ **getEdge**(`_id`): `undefined` \| [`ApiEdge`](ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |

#### Returns

`undefined` \| [`ApiEdge`](ApiEdge.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdge](../interfaces/LayoutGraph.md#getedge)

#### Defined in

[layoutGraph.ts:283](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-283)

___

### getEdgeStyle

▸ **getEdgeStyle**<`K`\>(`_id`, `_key`): `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`EdgeStyles`](../modules.md#edgestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_key` | `K` |

#### Returns

`Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>[`K`]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdgeStyle](../interfaces/LayoutGraph.md#getedgestyle)

#### Defined in

[layoutGraph.ts:349](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-349)

___

### getEdgeStyles

▸ **getEdgeStyles**(`_id`): `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |

#### Returns

`Partial`<[`EdgeStyles`](../modules.md#edgestyles)\>

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdgeStyles](../interfaces/LayoutGraph.md#getedgestyles)

#### Defined in

[layoutGraph.ts:334](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-334)

___

### getEdges

▸ **getEdges**(): [`ApiEdge`](ApiEdge.md)[]

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getEdges](../interfaces/LayoutGraph.md#getedges)

#### Defined in

[layoutGraph.ts:328](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-328)

___

### getNode

▸ **getNode**(`_id`): `undefined` \| [`ApiNode`](ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |

#### Returns

`undefined` \| [`ApiNode`](ApiNode.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNode](../interfaces/LayoutGraph.md#getnode)

#### Defined in

[layoutGraph.ts:262](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-262)

___

### getNodeStyle

▸ **getNodeStyle**<`K`\>(`_id`, `_key`): `Partial`<[`NodeStyles`](../modules.md#nodestyles)\>[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`NodeStyles`](../modules.md#nodestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_key` | `K` |

#### Returns

`Partial`<[`NodeStyles`](../modules.md#nodestyles)\>[`K`]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNodeStyle](../interfaces/LayoutGraph.md#getnodestyle)

#### Defined in

[layoutGraph.ts:343](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-343)

___

### getNodeStyles

▸ **getNodeStyles**(`_id`): `Partial`<[`NodeStyles`](../modules.md#nodestyles)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |

#### Returns

`Partial`<[`NodeStyles`](../modules.md#nodestyles)\>

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNodeStyles](../interfaces/LayoutGraph.md#getnodestyles)

#### Defined in

[layoutGraph.ts:331](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-331)

___

### getNodes

▸ **getNodes**(): [`ApiNode`](ApiNode.md)[]

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getNodes](../interfaces/LayoutGraph.md#getnodes)

#### Defined in

[layoutGraph.ts:325](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-325)

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

#### Defined in

[layoutGraph.ts:359](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-359)

___

### getVisibleEdges

▸ **getVisibleEdges**(): [`ApiEdge`](ApiEdge.md)[]

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getVisibleEdges](../interfaces/LayoutGraph.md#getvisibleedges)

#### Defined in

[layoutGraph.ts:280](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-280)

___

### getVisibleNodes

▸ **getVisibleNodes**(): [`ApiNode`](ApiNode.md)[]

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[getVisibleNodes](../interfaces/LayoutGraph.md#getvisiblenodes)

#### Defined in

[layoutGraph.ts:259](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-259)

___

### hideEdges

▸ **hideEdges**(`_ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_ids` | `string`[] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[hideEdges](../interfaces/LayoutGraph.md#hideedges)

#### Defined in

[layoutGraph.ts:322](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-322)

___

### hideNodes

▸ **hideNodes**(`_ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_ids` | `string`[] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[hideNodes](../interfaces/LayoutGraph.md#hidenodes)

#### Defined in

[layoutGraph.ts:316](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-316)

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

#### Defined in

[layoutGraph.ts:152](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-152)

___

### removeEdge

▸ **removeEdge**(`_id`): `undefined` \| [`ApiEdge`](ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |

#### Returns

`undefined` \| [`ApiEdge`](ApiEdge.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[removeEdge](../interfaces/LayoutGraph.md#removeedge)

#### Defined in

[layoutGraph.ts:292](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-292)

___

### removeEdges

▸ **removeEdges**(`_ids`): [`ApiEdge`](ApiEdge.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `_ids` | `string`[] |

#### Returns

[`ApiEdge`](ApiEdge.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[removeEdges](../interfaces/LayoutGraph.md#removeedges)

#### Defined in

[layoutGraph.ts:295](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-295)

___

### removeNode

▸ **removeNode**(`_id`): `undefined` \| [`ApiNode`](ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |

#### Returns

`undefined` \| [`ApiNode`](ApiNode.md)

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[removeNode](../interfaces/LayoutGraph.md#removenode)

#### Defined in

[layoutGraph.ts:271](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-271)

___

### removeNodes

▸ **removeNodes**(`_ids`): [`ApiNode`](ApiNode.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `_ids` | `string`[] |

#### Returns

[`ApiNode`](ApiNode.md)[]

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[removeNodes](../interfaces/LayoutGraph.md#removenodes)

#### Defined in

[layoutGraph.ts:274](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-274)

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

#### Defined in

[layoutGraph.ts:137](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-137)

___

### setEdgeProperties

▸ **setEdgeProperties**(`_id`, `_properties`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_properties` | [`Properties`](../modules.md#properties) |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setEdgeProperties](../interfaces/LayoutGraph.md#setedgeproperties)

#### Defined in

[layoutGraph.ts:310](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-310)

___

### setEdgeStyle

▸ **setEdgeStyle**<`K`\>(`_id`, `_key`, `_value`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`EdgeStyles`](../modules.md#edgestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_key` | `K` |
| `_value` | [`EdgeStyles`](../modules.md#edgestyles)[`K`] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setEdgeStyle](../interfaces/LayoutGraph.md#setedgestyle)

#### Defined in

[layoutGraph.ts:352](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-352)

___

### setEdgeStyles

▸ **setEdgeStyles**(`_id`, `_styles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_styles` | `Partial`<[`EdgeStyles`](../modules.md#edgestyles)\> |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setEdgeStyles](../interfaces/LayoutGraph.md#setedgestyles)

#### Defined in

[layoutGraph.ts:340](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-340)

___

### setNodeCategory

▸ **setNodeCategory**(`_id`, `_category`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_category` | [`CategoryId`](../modules.md#categoryid) |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeCategory](../interfaces/LayoutGraph.md#setnodecategory)

#### Defined in

[layoutGraph.ts:301](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-301)

___

### setNodeCollection

▸ **setNodeCollection**(`_id`, `_collection`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_collection` | `NodeCollection` |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeCollection](../interfaces/LayoutGraph.md#setnodecollection)

#### Defined in

[layoutGraph.ts:304](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-304)

___

### setNodeProperties

▸ **setNodeProperties**(`_id`, `_properties`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_properties` | [`Properties`](../modules.md#properties) |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeProperties](../interfaces/LayoutGraph.md#setnodeproperties)

#### Defined in

[layoutGraph.ts:307](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-307)

___

### setNodeStyle

▸ **setNodeStyle**<`K`\>(`_id`, `_key`, `_value`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`NodeStyles`](../modules.md#nodestyles) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_key` | `K` |
| `_value` | [`NodeStyles`](../modules.md#nodestyles)[`K`] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeStyle](../interfaces/LayoutGraph.md#setnodestyle)

#### Defined in

[layoutGraph.ts:346](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-346)

___

### setNodeStyles

▸ **setNodeStyles**(`_id`, `_styles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `_styles` | `Partial`<[`NodeStyles`](../modules.md#nodestyles)\> |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[setNodeStyles](../interfaces/LayoutGraph.md#setnodestyles)

#### Defined in

[layoutGraph.ts:337](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-337)

___

### showEdges

▸ **showEdges**(`_ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_ids` | `string`[] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[showEdges](../interfaces/LayoutGraph.md#showedges)

#### Defined in

[layoutGraph.ts:319](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-319)

___

### showNodes

▸ **showNodes**(`_ids`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_ids` | `string`[] |

#### Returns

`void`

#### Implementation of

[LayoutGraph](../interfaces/LayoutGraph.md).[showNodes](../interfaces/LayoutGraph.md#shownodes)

#### Defined in

[layoutGraph.ts:313](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/layoutGraph.ts#lines-313)
