[**babel-plugin-metadata-accumulator**](../../README.md)

***

[babel-plugin-metadata-accumulator](../../README.md) / [src](../README.md) / createMetadataAccumulatorPlugin

# Function: createMetadataAccumulatorPlugin()

> **createMetadataAccumulatorPlugin**(): [`PluginAndAccumulator`](../type-aliases/PluginAndAccumulator.md)

Defined in: [src/index.ts:62](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/1cb7c85862a6dd782a6e2b7aca80332634e6af1b/src/index.ts#L62)

Create and return a metadata accumulator plugin and corresponding object
containing all accumulated metadata.

If analyzing source with no originating file path, the accumulator will map
retain its metadata under the `"/dev/null"` key.

## Returns

[`PluginAndAccumulator`](../type-aliases/PluginAndAccumulator.md)
