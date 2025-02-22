[**babel-plugin-metadata-accumulator**](../../../README.md)

***

[babel-plugin-metadata-accumulator](../../../README.md) / [test/util](../README.md) / MockedEnvOptions

# Type Alias: MockedEnvOptions

> **MockedEnvOptions**: `object`

Defined in: node\_modules/@-xun/test-mock-env/dist/packages/test-mock-env/src/index.d.ts:5

## Type declaration

### passthroughDebugEnv?

> `optional` **passthroughDebugEnv**: `boolean`

If `true`, whenever `process.env.DEBUG` is present, it will be forwarded
as-is to the underlying environment mock even when `replaceEntireEnv` is
`true`. This allows debug output to make it to the screen.

#### Default

```ts
true
```

### replaceEntireEnv?

> `optional` **replaceEntireEnv**: `boolean`

By default, the `process.env` object (**except `process.env.DEBUG_COLORS`,
if it exists**) is emptied and re-hydrated with `newEnv`. Setting `replace`
to `false` will cause `newEnv` to be appended instead. Setting `replace` to
`true` will cause `newEnv` to replace the _entire_ `process.env` object,
including `process.env.DEBUG_COLORS`.

#### Default

```ts
undefined
```

## See

[withMockedEnv](../functions/withMockedEnv.md)
