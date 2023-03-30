[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ExpandNodesOptions

# Interface: ExpandNodesOptions

## Table of contents

### Properties

- [edgeDirection](ExpandNodesOptions.md#edgedirection)
- [excludedEdgeIds](ExpandNodesOptions.md#excludededgeids)
- [excludedRelationshipIds](ExpandNodesOptions.md#excludedrelationshipids)
- [expandBetweenSourceNodes](ExpandNodesOptions.md#expandbetweensourcenodes)
- [includedRelationshipIds](ExpandNodesOptions.md#includedrelationshipids)
- [limit](ExpandNodesOptions.md#limit)
- [maxHops](ExpandNodesOptions.md#maxhops)
- [sourceNodeIds](ExpandNodesOptions.md#sourcenodeids)

## Properties

### edgeDirection

• `Optional` **edgeDirection**: [`ExpandNodesEdgeDirection`](../enums/ExpandNodesEdgeDirection.md)

Restrict returned edges to those that have the specified direction.
If `ExpandNodesEdgeDirection.INCOMING`, then `(n)<-[r]-(m)`.
If `ExpandNodesEdgeDirection.OUTGOING`, then `(n)-[r]->(m)`.
If `ExpandNodesEdgeDirection.BOTH`, then `(n)<-[r]->(m)`.
Default: `ExpandNodesEdgeDirection.ANY`, then `(n)-[r]-(m)`.

#### Defined in

[neo4j/expandNodes.ts:27](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/neo4j/expandNodes.ts#lines-27)

___

### excludedEdgeIds

• `Optional` **excludedEdgeIds**: `number`[]

An array of edge ids that should be excluded from the result.
This is used to implement paging. To get the next page, exclude everything from the previous page(s).
Do not pass this parameter, since it is handled internally.

#### Defined in

[neo4j/expandNodes.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/neo4j/expandNodes.ts#lines-33)

___

### excludedRelationshipIds

• `Optional` **excludedRelationshipIds**: [`RelationshipId`](../modules.md#relationshipid)[]

An optional array of relationships to exclude from the result.
If omitted, no relationships will be excluded.
e.g. ["inSeason"]

#### Defined in

[neo4j/expandNodes.ts:39](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/neo4j/expandNodes.ts#lines-39)

___

### expandBetweenSourceNodes

• `Optional` **expandBetweenSourceNodes**: `boolean`

If true, only return edges and nodes that are on some path between two source nodes.
Defaults to false.

#### Defined in

[neo4j/expandNodes.ts:61](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/neo4j/expandNodes.ts#lines-61)

___

### includedRelationshipIds

• `Optional` **includedRelationshipIds**: [`RelationshipId`](../modules.md#relationshipid)[]

An optional array of relationships to include in the result.
If omitted, all relationships are included.
e.g. ["inSeason"]

#### Defined in

[neo4j/expandNodes.ts:45](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/neo4j/expandNodes.ts#lines-45)

___

### limit

• `Optional` **limit**: `number`

The maximum number of rows in the Neo4j query result.
Defaults to 1000.

#### Defined in

[neo4j/expandNodes.ts:50](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/neo4j/expandNodes.ts#lines-50)

___

### maxHops

• `Optional` **maxHops**: `number`

The maximum number of hops between the start and end nodes.
Defaults to 1.
e.g., if maxHops is 2, then (n)-[r1]-(n1)-[r2]-(m)

#### Defined in

[neo4j/expandNodes.ts:56](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/neo4j/expandNodes.ts#lines-56)

___

### sourceNodeIds

• `Optional` **sourceNodeIds**: [`NodeId`](../modules.md#nodeid)[]

An optional array of node ids to whitelist as the source nodes in the result.
i.e. the expanded nodes. If absent, all nodes are included.

#### Defined in

[neo4j/expandNodes.ts:66](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/neo4j/expandNodes.ts#lines-66)
