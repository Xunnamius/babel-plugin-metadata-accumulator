[**babel-plugin-metadata-accumulator**](../../README.md)

***

[babel-plugin-metadata-accumulator](../../README.md) / [src](../README.md) / PluginAndAccumulator

# Type Alias: PluginAndAccumulator

> **PluginAndAccumulator**: `object`

Defined in: [src/index.ts:33](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/834cd6171b06ba444ef3659b0f9b36ab753b30e4/src/index.ts#L33)

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
