[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / LegacyGraph

# Interface: LegacyGraph

## Table of contents

### Properties

- [addEdges](LegacyGraph.md#addedges)
- [addNodes](LegacyGraph.md#addnodes)
- [clear](LegacyGraph.md#clear)
- [edgeSet](LegacyGraph.md#edgeset)
- [edges](LegacyGraph.md#edges)
- [getEdgeWithId](LegacyGraph.md#getedgewithid)
- [getNodeById](LegacyGraph.md#getnodebyid)
- [getNodeWithProps](LegacyGraph.md#getnodewithprops)
- [layoutEdges](LegacyGraph.md#layoutedges)
- [layoutNodes](LegacyGraph.md#layoutnodes)
- [nodeSet](LegacyGraph.md#nodeset)
- [nodes](LegacyGraph.md#nodes)
- [removeEdgesByIds](LegacyGraph.md#removeedgesbyids)
- [removeNodesByIds](LegacyGraph.md#removenodesbyids)
- [update\_degree](LegacyGraph.md#update_degree)

## Properties

### addEdges

• **addEdges**: (`edges`: [`ApiEdge`](../classes/ApiEdge.md)[]) => [`LegacyEdge`](../modules.md#legacyedge)[]

#### Type declaration

▸ (`edges`): [`LegacyEdge`](../modules.md#legacyedge)[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `edges` | [`ApiEdge`](../classes/ApiEdge.md)[] |

##### Returns

[`LegacyEdge`](../modules.md#legacyedge)[]

#### Defined in

[runtime.ts:110](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-110)

___

### addNodes

• **addNodes**: (`nodes`: [`LegacyNode`](../modules.md#legacynode)[]) => `void`

#### Type declaration

▸ (`nodes`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `nodes` | [`LegacyNode`](../modules.md#legacynode)[] |

##### Returns

`void`

#### Defined in

[runtime.ts:111](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-111)

___

### clear

• **clear**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Defined in

[runtime.ts:112](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-112)

___

### edgeSet

• **edgeSet**: `Record`<`string`, [`LegacyEdge`](../modules.md#legacyedge)\>

#### Defined in

[runtime.ts:116](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-116)

___

### edges

• **edges**: [`LegacyEdge`](../modules.md#legacyedge)[]

#### Defined in

[runtime.ts:115](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-115)

___

### getEdgeWithId

• **getEdgeWithId**: (`sourceId`: [`NodeId`](../modules.md#nodeid), `targetId`: [`NodeId`](../modules.md#nodeid), `relationship?`: [`RelationshipId`](../modules.md#relationshipid)) => `undefined` \| [`LegacyEdge`](../modules.md#legacyedge)

#### Type declaration

▸ (`sourceId`, `targetId`, `relationship?`): `undefined` \| [`LegacyEdge`](../modules.md#legacyedge)

##### Parameters

| Name | Type |
| :------ | :------ |
| `sourceId` | [`NodeId`](../modules.md#nodeid) |
| `targetId` | [`NodeId`](../modules.md#nodeid) |
| `relationship?` | [`RelationshipId`](../modules.md#relationshipid) |

##### Returns

`undefined` \| [`LegacyEdge`](../modules.md#legacyedge)

#### Defined in

[runtime.ts:119](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-119)

___

### getNodeById

• **getNodeById**: (`id`: `string`) => `undefined` \| [`LegacyNode`](../modules.md#legacynode)

#### Type declaration

▸ (`id`): `undefined` \| [`LegacyNode`](../modules.md#legacynode)

##### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `string` |

##### Returns

`undefined` \| [`LegacyNode`](../modules.md#legacynode)

#### Defined in

[runtime.ts:120](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-120)

___

### getNodeWithProps

• **getNodeWithProps**: (`props`: [`ObjectType`](../modules.md#objecttype)) => `undefined` \| [`LegacyNode`](../modules.md#legacynode)

#### Type declaration

▸ (`props`): `undefined` \| [`LegacyNode`](../modules.md#legacynode)

##### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`ObjectType`](../modules.md#objecttype) |

##### Returns

`undefined` \| [`LegacyNode`](../modules.md#legacynode)

#### Defined in

[runtime.ts:121](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-121)

___

### layoutEdges

• **layoutEdges**: [`LegacyEdge`](../modules.md#legacyedge)[]

#### Defined in

[runtime.ts:118](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-118)

___

### layoutNodes

• **layoutNodes**: [`LegacyNode`](../modules.md#legacynode)[]

#### Defined in

[runtime.ts:117](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-117)

___

### nodeSet

• **nodeSet**: `Record`<`string`, [`LegacyNode`](../modules.md#legacynode)\>

#### Defined in

[runtime.ts:114](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-114)

___

### nodes

• **nodes**: [`LegacyNode`](../modules.md#legacynode)[]

#### Defined in

[runtime.ts:113](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-113)

___

### removeEdgesByIds

• **removeEdgesByIds**: (`ids`: [`EdgeId`](../modules.md#edgeid)[]) => `void`

#### Type declaration

▸ (`ids`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`EdgeId`](../modules.md#edgeid)[] |

##### Returns

`void`

#### Defined in

[runtime.ts:122](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-122)

___

### removeNodesByIds

• **removeNodesByIds**: (`ids`: [`NodeId`](../modules.md#nodeid)[], `onlyVisible?`: `boolean`) => `void`

#### Type declaration

▸ (`ids`, `onlyVisible?`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | [`NodeId`](../modules.md#nodeid)[] |
| `onlyVisible?` | `boolean` |

##### Returns

`void`

#### Defined in

[runtime.ts:123](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-123)

___

### update\_degree

• **update\_degree**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Defined in

[runtime.ts:124](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-124)
