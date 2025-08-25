[**babel-plugin-metadata-accumulator**](../../README.md)

***

[babel-plugin-metadata-accumulator](../../README.md) / [src](../README.md) / createMetadataAccumulatorPlugin

# Function: createMetadataAccumulatorPlugin()

> **createMetadataAccumulatorPlugin**(): [`PluginAndAccumulator`](../type-aliases/PluginAndAccumulator.md)

Defined in: [src/index.ts:55](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/d33fcf6daecd44dbedd2bdc6645db1a0febccf9e/src/index.ts#L55)

Create and return a metadata accumulator plugin and corresponding object
containing all accumulated metadata.

If analyzing source with no originating file path, the accumulator will map
its metadata under the `"/dev/null"` key.

## Returns

[`PluginAndAccumulator`](../type-aliases/PluginAndAccumulator.md)
