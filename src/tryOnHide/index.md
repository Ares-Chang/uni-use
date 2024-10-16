# tryOnHide

尝试获取组件生命周期，并调用 `onHide`

超过重试次数，根据 `runFinally` 直接执行或抛出异常

```typescript
import { tryOnHide } from '@uni-helper/uni-use'

tryOnHide(() => {
  ...
});
```