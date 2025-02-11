[**babel-plugin-metadata-accumulator**](../../README.md)

***

[babel-plugin-metadata-accumulator](../../README.md) / [src](../README.md) / PluginAndAccumulator

# Type Alias: PluginAndAccumulator

> **PluginAndAccumulator**: `object`

Defined in: [src/index.ts:28](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/ca3a4df0e6412657dbf19953fc49fceb9b33736d/src/index.ts#L28)

## Type declaration

### accumulator

> **accumulator**: `Map`\<`AbsolutePath`, [`AccumulatedMetadata`](AccumulatedMetadata.md)\>

A Map mapping absolute file paths to their accumulated metadata.

### plugin

> **plugin**: `PluginObj`\<`State`\>

The actual metadata accumulator plugin itself. This should be passed into
Babel when calling `babel.transform` etc.

## See

[createMetadataAccumulatorPlugin](../functions/createMetadataAccumulatorPlugin.md)
