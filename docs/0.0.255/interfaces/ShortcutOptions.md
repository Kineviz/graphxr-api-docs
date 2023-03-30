[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / ShortcutOptions

# Interface: ShortcutOptions

e.g.

```
api.line({
  sort: (a, b) => a.properties.seasonNumber - b.properties.seasonNumber,
  sort: 'seasonNumber', // same as above
  reverse: true, // sort descending
})

api.ego({
  filter: (node) => node.properties.Level === 1, // Find the root node[s]
})

const rootNodes = // nodes that are the root node[s]
api.ego ({
  nodes: rootNodes,
  nodes: rootNodes.map(n => n.id) // same as above
})
```

## Hierarchy

- [`NodeFilterOptions`](NodeFilterOptions.md)

  ↳ **`ShortcutOptions`**

## Table of contents

### Properties

- [aggregateProperties](ShortcutOptions.md#aggregateproperties)
- [centerCategory](ShortcutOptions.md#centercategory)
- [countLinks](ShortcutOptions.md#countlinks)
- [directional](ShortcutOptions.md#directional)
- [filter](ShortcutOptions.md#filter)
- [incomingRelationship](ShortcutOptions.md#incomingrelationship)
- [nodes](ShortcutOptions.md#nodes)
- [outgoingRelationship](ShortcutOptions.md#outgoingrelationship)
- [reverse](ShortcutOptions.md#reverse)
- [shortcutRelationship](ShortcutOptions.md#shortcutrelationship)
- [sort](ShortcutOptions.md#sort)

## Properties

### aggregateProperties

• `Optional` **aggregateProperties**: `AggregateProperty`[]

#### Defined in

[transform/shortcut.ts:20](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/transform/shortcut.ts#lines-20)

___

### centerCategory

• **centerCategory**: [`CategoryId`](../modules.md#categoryid)

#### Defined in

[transform/shortcut.ts:18](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/transform/shortcut.ts#lines-18)

___

### countLinks

• `Optional` **countLinks**: `boolean`

#### Defined in

[transform/shortcut.ts:21](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/transform/shortcut.ts#lines-21)

___

### directional

• `Optional` **directional**: `boolean`

#### Defined in

[transform/shortcut.ts:22](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/transform/shortcut.ts#lines-22)

___

### filter

• `Optional` **filter**: [`NodeFilter`](../modules.md#nodefilter)

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[filter](NodeFilterOptions.md#filter)

#### Defined in

[getNodesWithOptions.ts:32](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/getNodesWithOptions.ts#lines-32)

___

### incomingRelationship

• **incomingRelationship**: [`RelationshipId`](../modules.md#relationshipid)

#### Defined in

[transform/shortcut.ts:16](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/transform/shortcut.ts#lines-16)

___

### nodes

• `Optional` **nodes**: [`NodeId`](../modules.md#nodeid)[] \| [`ApiNode`](../classes/ApiNode.md)[]

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[nodes](NodeFilterOptions.md#nodes)

#### Defined in

[getNodesWithOptions.ts:33](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/getNodesWithOptions.ts#lines-33)

___

### outgoingRelationship

• **outgoingRelationship**: [`RelationshipId`](../modules.md#relationshipid)

#### Defined in

[transform/shortcut.ts:17](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/transform/shortcut.ts#lines-17)

___

### reverse

• `Optional` **reverse**: `boolean`

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[reverse](NodeFilterOptions.md#reverse)

#### Defined in

[getNodesWithOptions.ts:34](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/getNodesWithOptions.ts#lines-34)

___

### shortcutRelationship

• **shortcutRelationship**: [`RelationshipId`](../modules.md#relationshipid)

#### Defined in

[transform/shortcut.ts:19](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/transform/shortcut.ts#lines-19)

___

### sort

• `Optional` **sort**: [`PropertyKey`](../modules.md#propertykey) \| [`Sort`](../modules.md#sort)<[`ApiNode`](../classes/ApiNode.md)\>

#### Inherited from

[NodeFilterOptions](NodeFilterOptions.md).[sort](NodeFilterOptions.md#sort)

#### Defined in

[getNodesWithOptions.ts:31](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/getNodesWithOptions.ts#lines-31)
