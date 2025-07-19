# Interface: IBinding\<V\>

Interface representing a Binding.

This interface defines the contract for all types of bindings in the service container.
Bindings are used to manage dependencies and control how objects are instantiated within the container.

## Author

Mr. Stone <evensstone@gmail.com>

## Type Parameters

### V

`V` *extends* [`BindingValue`](../type-aliases/BindingValue.md)

The type of value that this binding holds.

## Properties

### resolve()

```ts
resolve: (container) => undefined | V;
```

Resolve and return the value of the binding.

#### Parameters

##### container

[`IContainer`](IContainer.md)

The container to resolve dependencies from.

#### Returns

`undefined` \| `V`

The resolved value of the binding.
