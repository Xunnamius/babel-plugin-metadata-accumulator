[**babel-plugin-metadata-accumulator**](../../README.md)

***

[babel-plugin-metadata-accumulator](../../README.md) / [src](../README.md) / createMetadataAccumulatorPlugin

# Function: createMetadataAccumulatorPlugin()

> **createMetadataAccumulatorPlugin**(): [`PluginAndAccumulator`](../type-aliases/PluginAndAccumulator.md)

Defined in: [src/index.ts:57](https://github.com/Xunnamius/babel-plugin-metadata-accumulator/blob/ca3a4df0e6412657dbf19953fc49fceb9b33736d/src/index.ts#L57)

Create and return a metadata accumulator plugin and corresponding object
containing all accumulated metadata.

If analyzing source with no originating file path, the accumulator will map
retain its metadata under the `"/dev/null"` key.

## Returns

[`PluginAndAccumulator`](../type-aliases/PluginAndAccumulator.md)
