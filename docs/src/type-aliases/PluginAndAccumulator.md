[**babel-plugin-metadata-accumulator**](../../README.md)

***

[babel-plugin-metadata-accumulator](../../README.md) / [src](../README.md) / PluginAndAccumulator

# Type Alias: PluginAndAccumulator

> **PluginAndAccumulator**: `object`

Defined in: [src/index.ts:33](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/1cb7c85862a6dd782a6e2b7aca80332634e6af1b/src/index.ts#L33)

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
