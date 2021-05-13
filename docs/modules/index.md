[protobuf-to-runtypes](../README.md) / index

# Module: index

## Table of contents

### Functions

- [parseToGenerator](index.md#parsetogenerator)
- [parseTypeFromSchema](index.md#parsetypefromschema)

## Functions

### parseToGenerator

▸ **parseToGenerator**(`buffer`: *string* \| Buffer): RootType[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `buffer` | *string* \| Buffer |

**Returns:** RootType[]

Defined in: [index.ts:74](https://github.com/cobraz/protobuf-to-runtypes/blob/1495d47/src/index.ts#L74)

___

### parseTypeFromSchema

▸ **parseTypeFromSchema**(`field`: Field, `message`: Message, `protobufSchema`: Schema): AnyType

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | Field |
| `message` | Message |
| `protobufSchema` | Schema |

**Returns:** AnyType

Defined in: [index.ts:5](https://github.com/cobraz/protobuf-to-runtypes/blob/1495d47/src/index.ts#L5)
