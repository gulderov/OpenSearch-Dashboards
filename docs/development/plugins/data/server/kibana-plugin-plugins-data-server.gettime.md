<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-plugins-data-server](./kibana-plugin-plugins-data-server.md) &gt; [getTime](./kibana-plugin-plugins-data-server.gettime.md)

## getTime() function

<b>Signature:</b>

```typescript
export declare function getTime(indexPattern: IIndexPattern | undefined, timeRange: TimeRange, options?: {
    forceNow?: Date;
    fieldName?: string;
}): import("../..").RangeFilter | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  indexPattern | <code>IIndexPattern &#124; undefined</code> |  |
|  timeRange | <code>TimeRange</code> |  |
|  options | <code>{</code><br/><code>    forceNow?: Date;</code><br/><code>    fieldName?: string;</code><br/><code>}</code> |  |

<b>Returns:</b>

`import("../..").RangeFilter | undefined`
