[@kineviz/graphxr-api](../README.md) / [Exports](../modules.md) / Runtime

# Interface: Runtime

## Table of contents

### Properties

- [\_AppActions](Runtime.md#_appactions)
- [\_GXR](Runtime.md#_gxr)
- [\_app](Runtime.md#_app)
- [\_hd](Runtime.md#_hd)
- [\_plot](Runtime.md#_plot)
- [\_requestData](Runtime.md#_requestdata)
- [\_testEnvironmentMocks](Runtime.md#_testenvironmentmocks)
- [globalVariable](Runtime.md#globalvariable)
- [isMockRuntime](Runtime.md#ismockruntime)

## Properties

### \_AppActions

• **\_AppActions**: `ReduxActions`

#### Defined in

[runtime.ts:36](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-36)

___

### \_GXR

• **\_GXR**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `Edge` | `any` |
| `GraphObservable` | { `next`: () => `void` ; `subscribe`: (`callback`: () => `void`) => [`RxjsSubscription`](RxjsSubscription.md) ; `subscribeDebounced`: (`callback`: () => `void`, `delay`: `number`) => [`RxjsSubscription`](RxjsSubscription.md)  } |
| `GraphObservable.next` | () => `void` |
| `GraphObservable.subscribe` | (`callback`: () => `void`) => [`RxjsSubscription`](RxjsSubscription.md) |
| `GraphObservable.subscribeDebounced` | (`callback`: () => `void`, `delay`: `number`) => [`RxjsSubscription`](RxjsSubscription.md) |
| `LabelsConfig` | { `instance`: () => [`LabelsConfig`](LabelsConfig.md)  } |
| `LabelsConfig.instance` | () => [`LabelsConfig`](LabelsConfig.md) |
| `Node` | `any` |
| `RelationshipConfig` | { `instance`: () => [`RelationshipConfig`](RelationshipConfig.md)  } |
| `RelationshipConfig.instance` | () => [`RelationshipConfig`](RelationshipConfig.md) |
| `TypeColor` | { `getColorByType`: (`type`: [`CategoryId`](../modules.md#categoryid)) => `string`  } |
| `TypeColor.getColorByType` | (`type`: [`CategoryId`](../modules.md#categoryid)) => `string` |

#### Defined in

[runtime.ts:64](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-64)

___

### \_app

• **\_app**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `controller` | { `API`: { `on`: (`event`: [`GraphxrEvent`](../modules.md#graphxrevent), `callback`: [`GraphxrEventCallback`](../modules.md#graphxreventcallback), `id`: `string`) => `void`  } ; `drawing`: { `GPUPicker`: { `lineCloud`: { `_widthScale`: `number`  }  } ; `cloudScene`: `Group` ; `convertCloudPoint`: (`position`: `Vector3`) => `Vector3` ; `forceStartLayout`: () => `void` ; `graph2DControl`: { `object`: `Group` ; `rotating`: `boolean` ; `showAxes`: (`visible`: `boolean`) => `void`  } ; `nodeCloud`: { `_showImage`: `boolean`  }  } ; `graph`: [`LegacyGraph`](LegacyGraph.md)  } |
| `controller.API` | { `on`: (`event`: [`GraphxrEvent`](../modules.md#graphxrevent), `callback`: [`GraphxrEventCallback`](../modules.md#graphxreventcallback), `id`: `string`) => `void`  } |
| `controller.API.on` | (`event`: [`GraphxrEvent`](../modules.md#graphxrevent), `callback`: [`GraphxrEventCallback`](../modules.md#graphxreventcallback), `id`: `string`) => `void` |
| `controller.drawing` | { `GPUPicker`: { `lineCloud`: { `_widthScale`: `number`  }  } ; `cloudScene`: `Group` ; `convertCloudPoint`: (`position`: `Vector3`) => `Vector3` ; `forceStartLayout`: () => `void` ; `graph2DControl`: { `object`: `Group` ; `rotating`: `boolean` ; `showAxes`: (`visible`: `boolean`) => `void`  } ; `nodeCloud`: { `_showImage`: `boolean`  }  } |
| `controller.drawing.GPUPicker` | { `lineCloud`: { `_widthScale`: `number`  }  } |
| `controller.drawing.GPUPicker.lineCloud` | { `_widthScale`: `number`  } |
| `controller.drawing.GPUPicker.lineCloud._widthScale` | `number` |
| `controller.drawing.cloudScene` | `Group` |
| `controller.drawing.convertCloudPoint` | (`position`: `Vector3`) => `Vector3` |
| `controller.drawing.forceStartLayout` | () => `void` |
| `controller.drawing.graph2DControl` | { `object`: `Group` ; `rotating`: `boolean` ; `showAxes`: (`visible`: `boolean`) => `void`  } |
| `controller.drawing.graph2DControl.object` | `Group` |
| `controller.drawing.graph2DControl.rotating` | `boolean` |
| `controller.drawing.graph2DControl.showAxes` | (`visible`: `boolean`) => `void` |
| `controller.drawing.nodeCloud` | { `_showImage`: `boolean`  } |
| `controller.drawing.nodeCloud._showImage` | `boolean` |
| `controller.graph` | [`LegacyGraph`](LegacyGraph.md) |
| `store` | `ReduxStore` |

#### Defined in

[runtime.ts:37](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-37)

___

### \_hd

• **\_hd**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `axisText` | { `x`: `any` ; `y`: `any` ; `z`: `any`  } |
| `axisText.x` | `any` |
| `axisText.y` | `any` |
| `axisText.z` | `any` |
| `axisTitle` | `any` |
| `setScale` | (`scale`: `Vector3`) => `void` |

#### Defined in

[runtime.ts:89](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-89)

___

### \_plot

• **\_plot**: `any`

#### Defined in

[runtime.ts:88](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-88)

___

### \_requestData

• **\_requestData**: [`RequestData`](RequestData.md)

#### Defined in

[runtime.ts:98](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-98)

___

### \_testEnvironmentMocks

• `Optional` **\_testEnvironmentMocks**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `makeNodeId?` | () => [`NodeId`](../modules.md#nodeid) |
| `projectId?` | `string` |

#### Defined in

[runtime.ts:99](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-99)

___

### globalVariable

• `Optional` **globalVariable**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `name?` | `string` |
| `version?` | `string` |

#### Defined in

[runtime.ts:84](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-84)

___

### isMockRuntime

• `Optional` **isMockRuntime**: `boolean`

#### Defined in

[runtime.ts:35](https://bitbucket.org/kineviz/graphxr-api/src/019f384/src/runtime.ts#lines-35)
