[**babel-plugin-metadata-accumulator**](../../README.md)

***

[babel-plugin-metadata-accumulator](../../README.md) / [src](../README.md) / createMetadataAccumulatorPlugin

# Function: createMetadataAccumulatorPlugin()

> **createMetadataAccumulatorPlugin**(): [`PluginAndAccumulator`](../type-aliases/PluginAndAccumulator.md)

Defined in: [src/index.ts:62](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/834cd6171b06ba444ef3659b0f9b36ab753b30e4/src/index.ts#L62)

Create and return a metadata accumulator plugin and corresponding object
containing all accumulated metadata.

If analyzing source with no originating file path, the accumulator will map
retain its metadata under the `"/dev/null"` key.

## Returns

[`PluginAndAccumulator`](../type-aliases/PluginAndAccumulator.md)
