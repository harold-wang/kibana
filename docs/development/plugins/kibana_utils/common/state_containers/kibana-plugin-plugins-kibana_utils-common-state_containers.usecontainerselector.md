<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-plugins-kibana\_utils-common-state\_containers](./kibana-plugin-plugins-kibana_utils-common-state_containers.md) &gt; [useContainerSelector](./kibana-plugin-plugins-kibana_utils-common-state_containers.usecontainerselector.md)

## useContainerSelector variable

React hook to apply selector to state container to extract only needed information. Will re-render your component only when the section changes.

<b>Signature:</b>

```typescript
useContainerSelector: <Container extends StateContainer<any, any, {}>, Result>(container: Container, selector: (state: UnboxState<Container>) => Result, comparator?: Comparator<Result>) => Result
```
