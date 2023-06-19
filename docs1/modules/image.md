[dynavo-as](../README.md) / [Exports](../modules.md) / image

# Namespace: image

## Table of contents

### Functions

- [blur](image.md#blur)
- [clone](image.md#clone)
- [create](image.md#create)
- [crop](image.md#crop)
- [getHeight](image.md#getheight)
- [getWidth](image.md#getwidth)
- [load](image.md#load)
- [overlay](image.md#overlay)
- [replace](image.md#replace)
- [resize](image.md#resize)
- [rotate](image.md#rotate)
- [rotateAboutCenter](image.md#rotateaboutcenter)
- [translate](image.md#translate)
- [warp](image.md#warp)

## Functions

### blur

▸ **blur**(`img`, `figma`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |
| `figma` | `number` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:188](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L188)

___

### clone

▸ **clone**(`img`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:184](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L184)

___

### create

▸ **create**(`c`, `w`, `h`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `c` | [`ColorType`](../enums/ColorType.md) |
| `w` | `number` |
| `h` | `number` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:176](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L176)

___

### crop

▸ **crop**(`img`, `x`, `y`, `w`, `h`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |
| `x` | `number` |
| `y` | `number` |
| `w` | `number` |
| `h` | `number` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:192](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L192)

___

### getHeight

▸ **getHeight**(`img`): `u32`

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |

#### Returns

`u32`

#### Defined in

[index.ts:228](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L228)

___

### getWidth

▸ **getWidth**(`img`): `u32`

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |

#### Returns

`u32`

#### Defined in

[index.ts:224](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L224)

___

### load

▸ **load**(`h`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `h` | [`ImageHash`](../classes/ImageHash.md) |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:180](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L180)

___

### overlay

▸ **overlay**(`i`, `j`, `x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `i` | `externref` |
| `j` | `externref` |
| `x` | `i64` |
| `y` | `i64` |

#### Returns

`void`

#### Defined in

[index.ts:200](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L200)

___

### replace

▸ **replace**(`i`, `j`, `x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `i` | `externref` |
| `j` | `externref` |
| `x` | `i64` |
| `y` | `i64` |

#### Returns

`void`

#### Defined in

[index.ts:196](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L196)

___

### resize

▸ **resize**(`img`, `w`, `h`, `f`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |
| `w` | `number` |
| `h` | `number` |
| `f` | `number` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:204](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L204)

___

### rotate

▸ **rotate**(`img`, `x`, `y`, `theta`, `interpolation`, `def`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |
| `x` | `number` |
| `y` | `number` |
| `theta` | `number` |
| `interpolation` | [`Interpolation`](../enums/Interpolation.md) |
| `def` | [`Pixel`](../classes/Pixel.md) |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:208](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L208)

___

### rotateAboutCenter

▸ **rotateAboutCenter**(`img`, `theta`, `interpolation`, `def`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |
| `theta` | `number` |
| `interpolation` | [`Interpolation`](../enums/Interpolation.md) |
| `def` | [`Pixel`](../classes/Pixel.md) |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:212](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L212)

___

### translate

▸ **translate**(`img`, `tx`, `ty`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |
| `tx` | `number` |
| `ty` | `number` |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:216](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L216)

___

### warp

▸ **warp**(`img`, `projection`, `interpolation`, `def`): [`Asset`](../modules.md#asset)

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | `externref` |
| `projection` | `externref` |
| `interpolation` | [`Interpolation`](../enums/Interpolation.md) |
| `def` | [`Pixel`](../classes/Pixel.md) |

#### Returns

[`Asset`](../modules.md#asset)

#### Defined in

[index.ts:220](https://github.com/dynavolabs/dynavo-as/blob/bdc283e/assembly/index.ts#L220)
