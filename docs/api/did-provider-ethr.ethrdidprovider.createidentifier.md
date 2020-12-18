---
id: did-provider-ethr.ethrdidprovider.createidentifier
title: EthrDIDProvider.createIdentifier() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## EthrDIDProvider.createIdentifier() method

<b>Signature:</b>

```typescript
createIdentifier({ kms, options }: {
        kms?: string;
        options?: any;
    }, context: IContext): Promise<Omit<IIdentifier, 'provider'>>;
```

## Parameters

| Parameter        | Type                             | Description |
| ---------------- | -------------------------------- | ----------- |
| { kms, options } | { kms?: string; options?: any; } |             |
| context          | IContext                         |             |

<b>Returns:</b>

Promise&lt;Omit&lt;[IIdentifier](./core.iidentifier.md) , 'provider'&gt;&gt;