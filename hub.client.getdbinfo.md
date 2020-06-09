<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@textile/hub](./hub.md) &gt; [Client](./hub.client.md) &gt; [getDBInfo](./hub.client.getdbinfo.md)

## Client.getDBInfo() method

getDBInfo returns invite 'links' unseful for inviting other peers to join a given store/thread.

<b>Signature:</b>

```typescript
getDBInfo(threadID: ThreadID): Promise<{
        address: string;
        key: string;
    }[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  threadID | ThreadID | the ID of the database |

<b>Returns:</b>

Promise&lt;{ address: string; key: string; }\[\]&gt;
