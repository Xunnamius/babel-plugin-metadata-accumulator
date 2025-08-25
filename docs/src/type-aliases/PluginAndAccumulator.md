[**babel-plugin-metadata-accumulator**](../../README.md)

***

[babel-plugin-metadata-accumulator](../../README.md) / [src](../README.md) / PluginAndAccumulator

# Type Alias: PluginAndAccumulator

> **PluginAndAccumulator** = `object`

Defined in: [src/index.ts:26](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/d33fcf6daecd44dbedd2bdc6645db1a0febccf9e/src/index.ts#L26)

## See

[createMetadataAccumulatorPlugin](../functions/createMetadataAccumulatorPlugin.md)

## Properties

### accumulator

> **accumulator**: `Map`\<`AbsolutePath`, [`AccumulatedMetadata`](AccumulatedMetadata.md)\>

Defined in: [src/index.ts:35](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/d33fcf6daecd44dbedd2bdc6645db1a0febccf9e/src/index.ts#L35)

A Map mapping absolute file paths to their accumulated metadata.

***

### plugin

> **plugin**: `PluginObj`\<`State`\>

Defined in: [src/index.ts:31](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/d33fcf6daecd44dbedd2bdc6645db1a0febccf9e/src/index.ts#L31)

The actual metadata accumulator plugin itself. This should be passed into
Babel when calling `babel.transform` etc.
