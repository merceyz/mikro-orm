---
id: "core.serverexception"
title: "Class: ServerException"
sidebar_label: "ServerException"
custom_edit_url: null
hide_title: true
---

# Class: ServerException

[core](../modules/core.md).ServerException

Base class for all server related errors detected in the driver.

## Hierarchy

* [*DriverException*](core.driverexception.md)

  ↳ **ServerException**

  ↳↳ [*ConstraintViolationException*](core.constraintviolationexception.md)

  ↳↳ [*DatabaseObjectExistsException*](core.databaseobjectexistsexception.md)

  ↳↳ [*DatabaseObjectNotFoundException*](core.databaseobjectnotfoundexception.md)

  ↳↳ [*DeadlockException*](core.deadlockexception.md)

  ↳↳ [*InvalidFieldNameException*](core.invalidfieldnameexception.md)

  ↳↳ [*LockWaitTimeoutException*](core.lockwaittimeoutexception.md)

  ↳↳ [*NonUniqueFieldNameException*](core.nonuniquefieldnameexception.md)

  ↳↳ [*ReadOnlyException*](core.readonlyexception.md)

  ↳↳ [*SyntaxErrorException*](core.syntaxerrorexception.md)

## Constructors

### constructor

\+ **new ServerException**(`previous`: Error): [*ServerException*](core.serverexception.md)

#### Parameters:

Name | Type |
:------ | :------ |
`previous` | Error |

**Returns:** [*ServerException*](core.serverexception.md)

Inherited from: [DriverException](core.driverexception.md)

Defined in: [packages/core/src/exceptions.ts:10](https://github.com/mikro-orm/mikro-orm/blob/bcf1a0899b/packages/core/src/exceptions.ts#L10)

## Properties

### code

• `Optional` **code**: *string*

Inherited from: [DriverException](core.driverexception.md).[code](core.driverexception.md#code)

Defined in: [packages/core/src/exceptions.ts:6](https://github.com/mikro-orm/mikro-orm/blob/bcf1a0899b/packages/core/src/exceptions.ts#L6)

___

### errmsg

• `Optional` **errmsg**: *string*

Inherited from: [DriverException](core.driverexception.md).[errmsg](core.driverexception.md#errmsg)

Defined in: [packages/core/src/exceptions.ts:10](https://github.com/mikro-orm/mikro-orm/blob/bcf1a0899b/packages/core/src/exceptions.ts#L10)

___

### errno

• `Optional` **errno**: *number*

Inherited from: [DriverException](core.driverexception.md).[errno](core.driverexception.md#errno)

Defined in: [packages/core/src/exceptions.ts:7](https://github.com/mikro-orm/mikro-orm/blob/bcf1a0899b/packages/core/src/exceptions.ts#L7)

___

### message

• **message**: *string*

Inherited from: [DriverException](core.driverexception.md).[message](core.driverexception.md#message)

Defined in: docs/node_modules/typescript/lib/lib.es5.d.ts:974

___

### name

• **name**: *string*

Inherited from: [DriverException](core.driverexception.md).[name](core.driverexception.md#name)

Defined in: docs/node_modules/typescript/lib/lib.es5.d.ts:973

___

### prepareStackTrace

• `Optional` **prepareStackTrace**: (`err`: Error, `stackTraces`: CallSite[]) => *any*

Optional override for formatting stack traces

**`see`** https://v8.dev/docs/stack-trace-api#customizing-stack-traces

#### Type declaration:

▸ (`err`: Error, `stackTraces`: CallSite[]): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`err` | Error |
`stackTraces` | CallSite[] |

**Returns:** *any*

Defined in: node_modules/@types/node/globals.d.ts:11

Inherited from: [DriverException](core.driverexception.md).[prepareStackTrace](core.driverexception.md#preparestacktrace)

Defined in: node_modules/@types/node/globals.d.ts:11

___

### sqlMessage

• `Optional` **sqlMessage**: *string*

Inherited from: [DriverException](core.driverexception.md).[sqlMessage](core.driverexception.md#sqlmessage)

Defined in: [packages/core/src/exceptions.ts:9](https://github.com/mikro-orm/mikro-orm/blob/bcf1a0899b/packages/core/src/exceptions.ts#L9)

___

### sqlState

• `Optional` **sqlState**: *string*

Inherited from: [DriverException](core.driverexception.md).[sqlState](core.driverexception.md#sqlstate)

Defined in: [packages/core/src/exceptions.ts:8](https://github.com/mikro-orm/mikro-orm/blob/bcf1a0899b/packages/core/src/exceptions.ts#L8)

___

### stack

• `Optional` **stack**: *string*

Inherited from: [DriverException](core.driverexception.md).[stack](core.driverexception.md#stack)

Defined in: docs/node_modules/typescript/lib/lib.es5.d.ts:975

___

### stackTraceLimit

• **stackTraceLimit**: *number*

Inherited from: [DriverException](core.driverexception.md).[stackTraceLimit](core.driverexception.md#stacktracelimit)

Defined in: node_modules/@types/node/globals.d.ts:13

## Methods

### captureStackTrace

▸ **captureStackTrace**(`targetObject`: *object*, `constructorOpt?`: Function): *void*

Create .stack property on a target object

#### Parameters:

Name | Type |
:------ | :------ |
`targetObject` | *object* |
`constructorOpt?` | Function |

**Returns:** *void*

Inherited from: [DriverException](core.driverexception.md)

Defined in: node_modules/@types/node/globals.d.ts:4
