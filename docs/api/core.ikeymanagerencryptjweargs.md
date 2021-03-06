---
id: core.ikeymanagerencryptjweargs
title: IKeyManagerEncryptJWEArgs interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IKeyManagerEncryptJWEArgs interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Input arguments for [keyManagerEncryptJWE](./core.ikeymanager.keymanagerencryptjwe.md)

<b>Signature:</b>

```typescript
export interface IKeyManagerEncryptJWEArgs
```

## Properties

| Property                                         | Type                                       | Description                                       |
| ------------------------------------------------ | ------------------------------------------ | ------------------------------------------------- |
| [data](./core.ikeymanagerencryptjweargs.data.md) | string                                     | <b><i>(BETA)</i></b> Data to encrypt              |
| [kid](./core.ikeymanagerencryptjweargs.kid.md)   | string                                     | <b><i>(BETA)</i></b> Key ID to use for encryption |
| [to](./core.ikeymanagerencryptjweargs.to.md)     | Omit&lt;[IKey](./core.ikey.md) , 'kms'&gt; | <b><i>(BETA)</i></b> Recipient key object         |
