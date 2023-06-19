[dynavo-as](../README.md) / [Exports](../modules.md) / projection

# Namespace: projection

## Table of contents

### Functions

- [andThen](projection.md#andthen)
- [fromControlPoints](projection.md#fromcontrolpoints)
- [fromMatrix](projection.md#frommatrix)
- [revert](projection.md#revert)
- [rotate](projection.md#rotate)
- [scale](projection.md#scale)
- [translate](projection.md#translate)

## Functions

### andThen

▸ **andThen**(`p`, `other`): [`Projection`](../modules.md#projection)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p` | `externref` |
| `other` | `externref` |

#### Returns

[`Projection`](../modules.md#projection)

#### Defined in

[index.ts:302](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L302)

___

### fromControlPoints

▸ **fromControlPoints**(`from`, `to`): [`Projection`](../modules.md#projection)

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | [`ControlPoint`](../classes/ControlPoint.md) |
| `to` | [`ControlPoint`](../classes/ControlPoint.md) |

#### Returns

[`Projection`](../modules.md#projection)

#### Defined in

[index.ts:282](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L282)

___

### fromMatrix

▸ **fromMatrix**(`transform`): [`Projection`](../modules.md#projection)

#### Parameters

| Name | Type |
| :------ | :------ |
| `transform` | [`Transform`](../classes/Transform.md) |

#### Returns

[`Projection`](../modules.md#projection)

#### Defined in

[index.ts:278](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L278)

___

### revert

▸ **revert**(`p`): [`Projection`](../modules.md#projection)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p` | `externref` |

#### Returns

[`Projection`](../modules.md#projection)

#### Defined in

[index.ts:298](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L298)

___

### rotate

▸ **rotate**(`theta`): [`Projection`](../modules.md#projection)

#### Parameters

| Name | Type |
| :------ | :------ |
| `theta` | `number` |

#### Returns

[`Projection`](../modules.md#projection)

#### Defined in

[index.ts:290](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L290)

___

### scale

▸ **scale**(`sx`, `sy`): [`Projection`](../modules.md#projection)

#### Parameters

| Name | Type |
| :------ | :------ |
| `sx` | `number` |
| `sy` | `number` |

#### Returns

[`Projection`](../modules.md#projection)

#### Defined in

[index.ts:294](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L294)

___

### translate

▸ **translate**(`tx`, `ty`): [`Projection`](../modules.md#projection)

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | `number` |
| `ty` | `number` |

#### Returns

[`Projection`](../modules.md#projection)

#### Defined in

[index.ts:286](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L286)
