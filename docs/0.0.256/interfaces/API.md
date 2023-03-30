[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / API

# Interface: API

## Table of contents

### Properties

- [DIMENSIONS](API.md#dimensions)
- [ExpandNodesEdgeDirection](API.md#expandnodesedgedirection)
- [ExpandNodesStatusCode](API.md#expandnodesstatuscode)
- [\_minimumGraphxrVersion](API.md#_minimumgraphxrversion)
- [\_version](API.md#_version)
- [aggregateFormula](API.md#aggregateformula)
- [mapFormula](API.md#mapformula)

### Methods

- [aggregate](API.md#aggregate)
- [alignBy](API.md#alignby)
- [applyLayout](API.md#applylayout)
- [areGraphSnapshotsEqual](API.md#aregraphsnapshotsequal)
- [betweenness](API.md#betweenness)
- [circle](API.md#circle)
- [closeness](API.md#closeness)
- [collectNodes](API.md#collectnodes)
- [colorNodesByProperty](API.md#colornodesbyproperty)
- [comparePropertyValues](API.md#comparepropertyvalues)
- [connectedComponent](API.md#connectedcomponent)
- [convertToScreenCoordinates](API.md#converttoscreencoordinates)
- [createNodes](API.md#createnodes)
- [cube](API.md#cube)
- [dispatchGraphDataUpdate](API.md#dispatchgraphdataupdate)
- [distributionBy](API.md#distributionby)
- [edgesByRelationship](API.md#edgesbyrelationship)
- [ego](API.md#ego)
- [expandNodes](API.md#expandnodes)
- [explodeCollections](API.md#explodecollections)
- [extract](API.md#extract)
- [flyToCenter](API.md#flytocenter)
- [flyToPosition](API.md#flytoposition)
- [getCategoryColor](API.md#getcategorycolor)
- [getCategoryConfig](API.md#getcategoryconfig)
- [getGraphView](API.md#getgraphview)
- [getLayoutGraph](API.md#getlayoutgraph)
- [getObservableLayoutGraph](API.md#getobservablelayoutgraph)
- [getRuntime](API.md#getruntime)
- [getScene](API.md#getscene)
- [grid](API.md#grid)
- [layout](API.md#layout)
- [line](API.md#line)
- [link](API.md#link)
- [louvain](API.md#louvain)
- [makeCollectionNode](API.md#makecollectionnode)
- [makeColor](API.md#makecolor)
- [makeEdge](API.md#makeedge)
- [makeGraph](API.md#makegraph)
- [makeNode](API.md#makenode)
- [makeNodeId](API.md#makenodeid)
- [makePosition](API.md#makeposition)
- [makeRandomGraph](API.md#makerandomgraph)
- [makeRandomPosition](API.md#makerandomposition)
- [map](API.md#map)
- [merge](API.md#merge)
- [mergeNodes](API.md#mergenodes)
- [mergeRelationships](API.md#mergerelationships)
- [neo4j](API.md#neo4j)
- [nodesByCategory](API.md#nodesbycategory)
- [observe](API.md#observe)
- [on](API.md#on)
- [onChange](API.md#onchange)
- [pageRank](API.md#pagerank)
- [parametric](API.md#parametric)
- [random](API.md#random)
- [range](API.md#range)
- [rotate](API.md#rotate)
- [scale](API.md#scale)
- [setAutoShowImage](API.md#setautoshowimage)
- [setCameraOptions](API.md#setcameraoptions)
- [setCameraRotating](API.md#setcamerarotating)
- [setCategoryCaptionProperties](API.md#setcategorycaptionproperties)
- [setCategorySizeProperty](API.md#setcategorysizeproperty)
- [setEdgeScale](API.md#setedgescale)
- [setFullscreen](API.md#setfullscreen)
- [setParametricAxesOptions](API.md#setparametricaxesoptions)
- [setRuntime](API.md#setruntime)
- [shift](API.md#shift)
- [shortcut](API.md#shortcut)
- [shortestPath](API.md#shortestpath)
- [sleep](API.md#sleep)
- [sortByProperty](API.md#sortbyproperty)
- [spiral](API.md#spiral)
- [stronglyConnectedComponent](API.md#stronglyconnectedcomponent)
- [traceNeighbors](API.md#traceneighbors)
- [triggerForceLayout](API.md#triggerforcelayout)
- [uncollectNodes](API.md#uncollectnodes)

## Properties

### DIMENSIONS

• **DIMENSIONS**: `Record`<``"x"`` \| ``"y"`` \| ``"z"``, ``"x"`` \| ``"y"`` \| ``"z"``\>

#### Defined in

[index.ts:323](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-323)

___

### ExpandNodesEdgeDirection

• **ExpandNodesEdgeDirection**: `Record`<``"INCOMING"`` \| ``"OUTGOING"`` \| ``"BOTH"`` \| ``"ANY"``, `string`\>

#### Defined in

[index.ts:300](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-300)

___

### ExpandNodesStatusCode

• **ExpandNodesStatusCode**: `Record`<``"MAYBE_MORE_RESULTS_AVAILABLE"`` \| ``"NO_MORE_RESULTS_AVAILABLE"``, `string`\>

#### Defined in

[index.ts:301](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-301)

___

### \_minimumGraphxrVersion

• **\_minimumGraphxrVersion**: `string`

#### Defined in

[index.ts:199](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-199)

___

### \_version

• **\_version**: `string`

#### Defined in

[index.ts:200](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-200)

___

### aggregateFormula

• **aggregateFormula**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `average` | `AggregateFormula` |
| `concatenate` | `AggregateFormula` |
| `count` | `AggregateFormula` |
| `max` | `AggregateFormula` |
| `min` | `AggregateFormula` |
| `range` | `AggregateFormula` |
| `sum` | `AggregateFormula` |
| `takeFirst` | `AggregateFormula` |

#### Defined in

[index.ts:327](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-327)

___

### mapFormula

• **mapFormula**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `toDate` | [`MapFormula`](../modules.md#mapformula) |
| `toNumber` | [`MapFormula`](../modules.md#mapformula) |
| `toString` | [`MapFormula`](../modules.md#mapformula) |
| `toWeek` | [`MapFormula`](../modules.md#mapformula) |

#### Defined in

[index.ts:340](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-340)

## Methods

### aggregate

▸ **aggregate**(`options`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`AggregateOptions`](../modules.md#aggregateoptions) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:326](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-326)

___

### alignBy

▸ **alignBy**(`options`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`AlignByOptions`](AlignByOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:266](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-266)

___

### applyLayout

▸ **applyLayout**(`view`, `computeLayout`, `tweenOverrides?`): `Promise`<[`NodeIdToPosition`](../modules.md#nodeidtoposition)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `view` | [`LayoutGraph`](LayoutGraph.md) |
| `computeLayout` | [`LayoutFunction`](../modules.md#layoutfunction) |
| `tweenOverrides?` | `Partial`<`TweenLayoutOptions`\> |

#### Returns

`Promise`<[`NodeIdToPosition`](../modules.md#nodeidtoposition)\>

#### Defined in

[index.ts:267](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-267)

___

### areGraphSnapshotsEqual

▸ **areGraphSnapshotsEqual**(`left`, `right`, `options?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `left` | `GraphSnapshot` |
| `right` | `GraphSnapshot` |
| `options?` | `Partial`<[`AreGraphSnapshotsEqualOptions`](AreGraphSnapshotsEqualOptions.md)\> |

#### Returns

`boolean`

#### Defined in

[index.ts:246](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-246)

___

### betweenness

▸ **betweenness**(`graph`): [`BetweennessResult`](../modules.md#betweennessresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |

#### Returns

[`BetweennessResult`](../modules.md#betweennessresult)

#### Defined in

[index.ts:221](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-221)

___

### circle

▸ **circle**(`options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`NodeFilterOptions`](NodeFilterOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:272](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-272)

___

### closeness

▸ **closeness**(`graph`): [`ClosenessResult`](../modules.md#closenessresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |

#### Returns

[`ClosenessResult`](../modules.md#closenessresult)

#### Defined in

[index.ts:222](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-222)

___

### collectNodes

▸ **collectNodes**(`options?`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`CollectNodesOptions`](CollectNodesOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:226](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-226)

___

### colorNodesByProperty

▸ **colorNodesByProperty**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`ColorNodesByPropertyOptions`](ColorNodesByPropertyOptions.md) |

#### Returns

`void`

#### Defined in

[index.ts:289](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-289)

___

### comparePropertyValues

▸ **comparePropertyValues**(`left`, `right`, `ascending?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `left` | `any` |
| `right` | `any` |
| `ascending?` | `boolean` |

#### Returns

`number`

#### Defined in

[index.ts:316](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-316)

___

### connectedComponent

▸ **connectedComponent**(`graph`): [`ConnectedComponentResult`](../modules.md#connectedcomponentresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |

#### Returns

[`ConnectedComponentResult`](../modules.md#connectedcomponentresult)

#### Defined in

[index.ts:232](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-232)

___

### convertToScreenCoordinates

▸ **convertToScreenCoordinates**(`position`): `Vector3`

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | `Vector3` |

#### Returns

`Vector3`

#### Defined in

[index.ts:203](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-203)

___

### createNodes

▸ **createNodes**(`options?`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`CreateNodesOptions`](CreateNodesOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:258](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-258)

___

### cube

▸ **cube**(`options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`NodeFilterOptions`](NodeFilterOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:273](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-273)

___

### dispatchGraphDataUpdate

▸ **dispatchGraphDataUpdate**(): `void`

#### Returns

`void`

#### Defined in

[index.ts:310](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-310)

___

### distributionBy

▸ **distributionBy**(`options`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`DistributionOptions`](../modules.md#distributionoptions) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:274](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-274)

___

### edgesByRelationship

▸ **edgesByRelationship**(`relationship`): [`EdgeFilter`](../modules.md#edgefilter)

#### Parameters

| Name | Type |
| :------ | :------ |
| `relationship` | [`RelationshipId`](../modules.md#relationshipid) |

#### Returns

[`EdgeFilter`](../modules.md#edgefilter)

#### Defined in

[index.ts:243](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-243)

___

### ego

▸ **ego**(`options`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`EgoOptions`](EgoOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:275](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-275)

___

### expandNodes

▸ **expandNodes**(`options?`): `Promise`<[`ExpandNodesStatusCode`](../enums/ExpandNodesStatusCode.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Omit`<[`ExpandNodesOptions`](ExpandNodesOptions.md), ``"excludedEdgeIds"``\> |

#### Returns

`Promise`<[`ExpandNodesStatusCode`](../enums/ExpandNodesStatusCode.md)\>

#### Defined in

[index.ts:302](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-302)

___

### explodeCollections

▸ **explodeCollections**(`options?`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ExplodeCollectionsOptions`](ExplodeCollectionsOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:227](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-227)

___

### extract

▸ **extract**(`options`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`ExtractOptions`](ExtractOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:337](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-337)

___

### flyToCenter

▸ **flyToCenter**(`view?`, `nodeIds?`, `offset?`, `options?`): `Promise`<`Vector3`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `view?` | [`LayoutGraph`](LayoutGraph.md) |
| `nodeIds?` | [`NodeId`](../modules.md#nodeid)[] |
| `offset?` | `number` |
| `options?` | [`TweenPositionOptions`](TweenPositionOptions.md) |

#### Returns

`Promise`<`Vector3`\>

#### Defined in

[index.ts:204](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-204)

___

### flyToPosition

▸ **flyToPosition**(`position`, `offset?`, `options?`): `Promise`<`Vector3`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | `Vector3` |
| `offset?` | `number` |
| `options?` | [`TweenPositionOptions`](TweenPositionOptions.md) |

#### Returns

`Promise`<`Vector3`\>

#### Defined in

[index.ts:210](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-210)

___

### getCategoryColor

▸ **getCategoryColor**(`categoryId`): `Color`

#### Parameters

| Name | Type |
| :------ | :------ |
| `categoryId` | [`CategoryId`](../modules.md#categoryid) |

#### Returns

`Color`

#### Defined in

[index.ts:215](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-215)

___

### getCategoryConfig

▸ **getCategoryConfig**(`categoryId`): [`CategoryConfig`](CategoryConfig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `categoryId` | [`CategoryId`](../modules.md#categoryid) |

#### Returns

[`CategoryConfig`](CategoryConfig.md)

#### Defined in

[index.ts:216](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-216)

___

### getGraphView

▸ **getGraphView**(): `void`

#### Returns

`void`

#### Defined in

[index.ts:251](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-251)

___

### getLayoutGraph

▸ **getLayoutGraph**(): [`LegacyLayoutGraph`](../classes/LegacyLayoutGraph.md)

#### Returns

[`LegacyLayoutGraph`](../classes/LegacyLayoutGraph.md)

#### Defined in

[index.ts:252](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-252)

___

### getObservableLayoutGraph

▸ **getObservableLayoutGraph**(): [`ObservableLayoutGraph`](../modules.md#observablelayoutgraph)

#### Returns

[`ObservableLayoutGraph`](../modules.md#observablelayoutgraph)

#### Defined in

[index.ts:263](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-263)

___

### getRuntime

▸ **getRuntime**(): [`Runtime`](Runtime.md)

#### Returns

[`Runtime`](Runtime.md)

#### Defined in

[index.ts:197](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-197)

___

### getScene

▸ **getScene**(): `Group`

#### Returns

`Group`

#### Defined in

[index.ts:313](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-313)

___

### grid

▸ **grid**(`options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`NodeFilterOptions`](NodeFilterOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:277](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-277)

___

### layout

▸ **layout**(`computeLayout`, `options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `computeLayout` | [`LayoutNodesFunction`](../modules.md#layoutnodesfunction) |
| `options?` | [`NodeFilterOptions`](NodeFilterOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:276](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-276)

___

### line

▸ **line**(`options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`NodeFilterOptions`](NodeFilterOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:278](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-278)

___

### link

▸ **link**(`options`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`LinkOptions`](LinkOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:338](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-338)

___

### louvain

▸ **louvain**(`graph`): [`LouvainResult`](../modules.md#louvainresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |

#### Returns

[`LouvainResult`](../modules.md#louvainresult)

#### Defined in

[index.ts:233](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-233)

___

### makeCollectionNode

▸ **makeCollectionNode**(`category`, `collection`): [`ApiNode`](../classes/ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `category` | [`CategoryId`](../modules.md#categoryid) |
| `collection` | `NodeCollection` |

#### Returns

[`ApiNode`](../classes/ApiNode.md)

#### Defined in

[index.ts:229](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-229)

___

### makeColor

▸ **makeColor**(`hexOrR`, `g?`, `b?`): `Color`

#### Parameters

| Name | Type |
| :------ | :------ |
| `hexOrR` | `number` |
| `g?` | `number` |
| `b?` | `number` |

#### Returns

`Color`

#### Defined in

[index.ts:320](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-320)

___

### makeEdge

▸ **makeEdge**(`edge`): [`ApiEdge`](../classes/ApiEdge.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `edge` | `Partial`<[`ApiEdge`](../classes/ApiEdge.md)\> |

#### Returns

[`ApiEdge`](../classes/ApiEdge.md)

#### Defined in

[index.ts:254](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-254)

___

### makeGraph

▸ **makeGraph**(): [`LayoutGraph`](LayoutGraph.md)

#### Returns

[`LayoutGraph`](LayoutGraph.md)

#### Defined in

[index.ts:253](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-253)

___

### makeNode

▸ **makeNode**(`options?`): [`ApiNode`](../classes/ApiNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Partial`<[`ApiNode`](../classes/ApiNode.md)\> |

#### Returns

[`ApiNode`](../classes/ApiNode.md)

#### Defined in

[index.ts:256](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-256)

___

### makeNodeId

▸ **makeNodeId**(): [`NodeId`](../modules.md#nodeid)

#### Returns

[`NodeId`](../modules.md#nodeid)

#### Defined in

[index.ts:255](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-255)

___

### makePosition

▸ **makePosition**(`xyz`): `Vector3`

#### Parameters

| Name | Type |
| :------ | :------ |
| `xyz` | `Partial`<`Vector3`\> |

#### Returns

`Vector3`

#### Defined in

[index.ts:321](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-321)

___

### makeRandomGraph

▸ **makeRandomGraph**(`options?`): [`LayoutGraph`](LayoutGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`MakeRandomGraphOptions`](../modules.md#makerandomgraphoptions) |

#### Returns

[`LayoutGraph`](LayoutGraph.md)

#### Defined in

[index.ts:257](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-257)

___

### makeRandomPosition

▸ **makeRandomPosition**(): `Vector3`

#### Returns

`Vector3`

#### Defined in

[index.ts:322](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-322)

___

### map

▸ **map**(`options`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`MapOptions`](MapOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:339](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-339)

___

### merge

▸ **merge**(`options`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`MergeOptions`](MergeOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:346](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-346)

___

### mergeNodes

▸ **mergeNodes**(`options?`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`MergeNodesOptions`](MergeNodesOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:259](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-259)

___

### mergeRelationships

▸ **mergeRelationships**(`options?`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`MergeRelationshipsOptions`](MergeRelationshipsOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:260](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-260)

___

### neo4j

▸ **neo4j**(`query`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | [`Neo4jQuery`](../modules.md#neo4jquery) |
| `options?` | [`Neo4jOptions`](Neo4jOptions.md) |

#### Returns

`void`

#### Defined in

[index.ts:303](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-303)

___

### nodesByCategory

▸ **nodesByCategory**(`category`): [`NodeFilter`](../modules.md#nodefilter)

#### Parameters

| Name | Type |
| :------ | :------ |
| `category` | [`CategoryId`](../modules.md#categoryid) |

#### Returns

[`NodeFilter`](../modules.md#nodefilter)

#### Defined in

[index.ts:242](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-242)

___

### observe

▸ **observe**<`T`\>(`event`, `compute`): `Iterator`<`T`, `any`, `undefined`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`GraphxrEvent`](../modules.md#graphxrevent) |
| `compute` | [`ObserveCallback`](../modules.md#observecallback) |

#### Returns

`Iterator`<`T`, `any`, `undefined`\>

#### Defined in

[index.ts:237](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-237)

___

### on

▸ **on**(`event`, `callback`): [`GraphxrEventCallbackId`](../modules.md#graphxreventcallbackid)

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`GraphxrEvent`](../modules.md#graphxrevent) |
| `callback` | [`GraphxrEventCallback`](../modules.md#graphxreventcallback) |

#### Returns

[`GraphxrEventCallbackId`](../modules.md#graphxreventcallbackid)

#### Defined in

[index.ts:239](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-239)

___

### onChange

▸ **onChange**<`T`\>(`callback`): `Iterator`<`T`, `any`, `undefined`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | [`ObserveCallback`](../modules.md#observecallback) |

#### Returns

`Iterator`<`T`, `any`, `undefined`\>

#### Defined in

[index.ts:238](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-238)

___

### pageRank

▸ **pageRank**(`graph`, `options?`): [`PageRankResult`](../modules.md#pagerankresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |
| `options?` | [`PageRankOptions`](PageRankOptions.md) |

#### Returns

[`PageRankResult`](../modules.md#pagerankresult)

#### Defined in

[index.ts:223](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-223)

___

### parametric

▸ **parametric**(`options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ParametricOptions`](ParametricOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:279](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-279)

___

### random

▸ **random**(`options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`NodeFilterOptions`](NodeFilterOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:280](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-280)

___

### range

▸ **range**(`size`): `number`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `size` | `number` |

#### Returns

`number`[]

#### Defined in

[index.ts:350](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-350)

___

### rotate

▸ **rotate**(`options`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`RotateOptions`](RotateOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:281](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-281)

___

### scale

▸ **scale**(`options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScaleOptions`](ScaleOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:282](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-282)

___

### setAutoShowImage

▸ **setAutoShowImage**(`value`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`boolean`

#### Defined in

[index.ts:306](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-306)

___

### setCameraOptions

▸ **setCameraOptions**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`CameraOptions`](CameraOptions.md) |

#### Returns

`void`

#### Defined in

[index.ts:212](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-212)

___

### setCameraRotating

▸ **setCameraRotating**(`isRotating`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `isRotating` | `boolean` |

#### Returns

`void`

#### Defined in

[index.ts:211](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-211)

___

### setCategoryCaptionProperties

▸ **setCategoryCaptionProperties**(`options`): `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`SetCategoryCaptionPropertiesOptions`](SetCategoryCaptionPropertiesOptions.md) |

#### Returns

`Promise`<`unknown`\>

#### Defined in

[index.ts:217](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-217)

___

### setCategorySizeProperty

▸ **setCategorySizeProperty**(`options`): `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`SetCategorySizePropertyOptions`](SetCategorySizePropertyOptions.md) |

#### Returns

`Promise`<`unknown`\>

#### Defined in

[index.ts:218](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-218)

___

### setEdgeScale

▸ **setEdgeScale**(`value`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`number`

#### Defined in

[index.ts:307](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-307)

___

### setFullscreen

▸ **setFullscreen**(`value`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`boolean`

#### Defined in

[index.ts:354](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-354)

___

### setParametricAxesOptions

▸ **setParametricAxesOptions**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `Partial`<[`AxesOptions`](AxesOptions.md)\> |

#### Returns

`void`

#### Defined in

[index.ts:283](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-283)

___

### setRuntime

▸ **setRuntime**(`runtime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `runtime` | [`Runtime`](Runtime.md) |

#### Returns

`void`

#### Defined in

[index.ts:198](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-198)

___

### shift

▸ **shift**(`options`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`ShiftOptions`](ShiftOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:284](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-284)

___

### shortcut

▸ **shortcut**(`options`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`ShortcutOptions`](ShortcutOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:347](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-347)

___

### shortestPath

▸ **shortestPath**(`graph`, `options`): ``null`` \| [`DijkstraEdge`](../modules.md#dijkstraedge)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |
| `options` | [`ShortestPathOptions`](ShortestPathOptions.md) |

#### Returns

``null`` \| [`DijkstraEdge`](../modules.md#dijkstraedge)[]

#### Defined in

[index.ts:292](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-292)

___

### sleep

▸ **sleep**(`ms`): `Promise`<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ms` | `number` |

#### Returns

`Promise`<`number`\>

#### Defined in

[index.ts:351](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-351)

___

### sortByProperty

▸ **sortByProperty**(`property`): [`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `property` | [`SortByPropertyOptions`](SortByPropertyOptions.md) |

#### Returns

[`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Defined in

[index.ts:317](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-317)

___

### spiral

▸ **spiral**(`options?`): [`LayoutFunction`](../modules.md#layoutfunction)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`NodeFilterOptions`](NodeFilterOptions.md) |

#### Returns

[`LayoutFunction`](../modules.md#layoutfunction)

#### Defined in

[index.ts:285](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-285)

___

### stronglyConnectedComponent

▸ **stronglyConnectedComponent**(`graph`): [`ConnectedComponentResult`](../modules.md#connectedcomponentresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `graph` | [`LayoutGraph`](LayoutGraph.md) |

#### Returns

[`ConnectedComponentResult`](../modules.md#connectedcomponentresult)

#### Defined in

[index.ts:234](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-234)

___

### traceNeighbors

▸ **traceNeighbors**(`view`, `rootId`, `options?`): `MapPolyfill`<[`NodeId`](../modules.md#nodeid), `boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `view` | [`LegacyLayoutGraph`](../classes/LegacyLayoutGraph.md) |
| `rootId` | [`NodeId`](../modules.md#nodeid) |
| `options?` | [`TraceNeighborsOptions`](TraceNeighborsOptions.md) |

#### Returns

`MapPolyfill`<[`NodeId`](../modules.md#nodeid), `boolean`\>

#### Defined in

[index.ts:293](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-293)

___

### triggerForceLayout

▸ **triggerForceLayout**(): `void`

#### Returns

`void`

#### Defined in

[index.ts:286](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-286)

___

### uncollectNodes

▸ **uncollectNodes**(`options?`): `TransformFunction`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`UncollectNodesOptions`](UncollectNodesOptions.md) |

#### Returns

`TransformFunction`

#### Defined in

[index.ts:228](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/index.ts#lines-228)
