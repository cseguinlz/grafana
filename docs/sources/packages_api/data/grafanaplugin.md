+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "GrafanaPlugin"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
draft = true
+++

## GrafanaPlugin class

<b>Signature</b>

```typescript
export declare class GrafanaPlugin<T extends PluginMeta = PluginMeta> 
```
<b>Import</b>

```typescript
import { GrafanaPlugin } from '@grafana/data';
```
<b>Properties</b>

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [angularConfigCtrl](#angularconfigctrl-property) |  | <code>any</code> |  |
|  [configPages](#configpages-property) |  | <code>Array&lt;PluginConfigPage&lt;T&gt;&gt;</code> |  |
|  [loadError](#loaderror-property) |  | <code>boolean</code> |  |
|  [meta](#meta-property) |  | <code>T</code> |  |

<b>Methods</b>

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [addConfigPage(tab)](#addconfigpage-method) |  |  |

### angularConfigCtrl property

<b>Signature</b>

```typescript
angularConfigCtrl?: any;
```

### configPages property

<b>Signature</b>

```typescript
configPages?: Array<PluginConfigPage<T>>;
```

### loadError property

<b>Signature</b>

```typescript
loadError?: boolean;
```

### meta property

<b>Signature</b>

```typescript
meta?: T;
```

### addConfigPage method

<b>Signature</b>

```typescript
addConfigPage(tab: PluginConfigPage<T>): this;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  tab | <code>PluginConfigPage&lt;T&gt;</code> |  |

<b>Returns:</b>

`this`
