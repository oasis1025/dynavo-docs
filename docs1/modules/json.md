[dynavo-as](../README.md) / [Exports](../modules.md) / json

# Namespace: json

## Table of contents

### Functions

- [create](json.md#create)
- [getStrAt](json.md#getstrat)
- [getU64At](json.md#getu64at)
- [load](json.md#load)
- [loadImageAt](json.md#loadimageat)
- [loadJsonAt](json.md#loadjsonat)
- [setStrAt](json.md#setstrat)
- [setU64At](json.md#setu64at)

## Functions

### create

▸ **create**(`v`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `String` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:244](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L244)

___

### getStrAt

▸ **getStrAt**(`a`, `p`): `String`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `externref` |
| `p` | `String` |

#### Returns

`String`

#### Defined in

[index.ts:260](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L260)

___

### getU64At

▸ **getU64At**(`a`, `p`): `u64`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `externref` |
| `p` | `String` |

#### Returns

`u64`

#### Defined in

[index.ts:264](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L264)

___

### load

▸ **load**(`h`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `h` | [`JsonHash`](../classes/JsonHash.md) |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:248](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L248)

___

### loadImageAt

▸ **loadImageAt**(`a`, `p`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `externref` |
| `p` | `String` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:272](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L272)

___

### loadJsonAt

▸ **loadJsonAt**(`a`, `p`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `externref` |
| `p` | `String` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:268](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L268)

___

### setStrAt

▸ **setStrAt**(`a`, `p`, `v`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `externref` |
| `p` | `String` |
| `v` | `String` |

#### Returns

`void`

#### Defined in

[index.ts:252](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L252)

___

### setU64At

▸ **setU64At**(`a`, `p`, `v`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `externref` |
| `p` | `String` |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[index.ts:256](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L256)
