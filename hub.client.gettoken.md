<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@textile/hub](./hub.md) &gt; [Client](./hub.client.md) &gt; [getToken](./hub.client.gettoken.md)

## Client.getToken() method

Obtain a token for interacting with the remote API.

<b>Signature:</b>

```typescript
getToken(identity: Identity, ctx?: ContextInterface): Promise<string>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  identity | Identity | A user identity to use for creating records in the database. A random identity can be created with \`<!-- -->Client.randomIdentity(), however, it is not easy/possible to migrate identities after the fact. Please store or otherwise persist any identity information if you wish to retrieve user data later, or use an external identity provider. |
|  ctx | ContextInterface | Context object containing web-gRPC headers and settings. |

<b>Returns:</b>

Promise&lt;string&gt;
