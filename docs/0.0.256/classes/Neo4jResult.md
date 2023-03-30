[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / Neo4jResult

# Class: Neo4jResult

## Table of contents

### Constructors

- [constructor](Neo4jResult.md#constructor)

### Properties

- [\_content](Neo4jResult.md#_content)

### Accessors

- [data](Neo4jResult.md#data)
- [type](Neo4jResult.md#type)

### Methods

- [toGraph](Neo4jResult.md#tograph)

## Constructors

### constructor

• **new Neo4jResult**(`content`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `content` | [`Neo4jResponseContent`](../interfaces/Neo4jResponseContent.md) |

#### Defined in

[neo4j/neo4jResult.ts:8](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/neo4j/neo4jResult.ts#lines-8)

## Properties

### \_content

• `Private` **\_content**: [`Neo4jResponseContent`](../interfaces/Neo4jResponseContent.md)

#### Defined in

[neo4j/neo4jResult.ts:6](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/neo4j/neo4jResult.ts#lines-6)

## Accessors

### data

• `get` **data**(): [`Neo4jData`](../modules.md#neo4jdata)

#### Returns

[`Neo4jData`](../modules.md#neo4jdata)

#### Defined in

[neo4j/neo4jResult.ts:16](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/neo4j/neo4jResult.ts#lines-16)

___

### type

• `get` **type**(): [`Neo4jResultType`](../enums/Neo4jResultType.md)

#### Returns

[`Neo4jResultType`](../enums/Neo4jResultType.md)

#### Defined in

[neo4j/neo4jResult.ts:12](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/neo4j/neo4jResult.ts#lines-12)

## Methods

### toGraph

▸ **toGraph**(): [`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Returns

[`LayoutGraph`](../interfaces/LayoutGraph.md)

#### Defined in

[neo4j/neo4jResult.ts:20](https://bitbucket.org/kineviz/graphxr-api/src/c752a8c/src/neo4j/neo4jResult.ts#lines-20)
