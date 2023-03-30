[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / LabelsConfig

# Interface: LabelsConfig

## Table of contents

### Properties

- [configs](LabelsConfig.md#configs)
- [getConfig](LabelsConfig.md#getconfig)
- [updateLabel](LabelsConfig.md#updatelabel)

## Properties

### configs

• **configs**: `Record`<[`CategoryId`](../modules.md#categoryid), [`CategoryConfig`](CategoryConfig.md)\>

#### Defined in

[runtime.ts:24](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-24)

___

### getConfig

• **getConfig**: (`category`: [`CategoryId`](../modules.md#categoryid)) => [`CategoryConfig`](CategoryConfig.md)

#### Type declaration

▸ (`category`): [`CategoryConfig`](CategoryConfig.md)

##### Parameters

| Name | Type |
| :------ | :------ |
| `category` | [`CategoryId`](../modules.md#categoryid) |

##### Returns

[`CategoryConfig`](CategoryConfig.md)

#### Defined in

[runtime.ts:25](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-25)

___

### updateLabel

• **updateLabel**: (`config`: [`CategoryConfig`](CategoryConfig.md)) => `void`

#### Type declaration

▸ (`config`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `config` | [`CategoryConfig`](CategoryConfig.md) |

##### Returns

`void`

#### Defined in

[runtime.ts:26](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-26)
