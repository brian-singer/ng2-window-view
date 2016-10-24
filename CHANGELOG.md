# ChangeLog

## 0.1.0

### Breaking changes

- `WindowViewService#pushWindow<T>` return instance directly instead of promise.

```typescript
let myWindow: MyWindowComponent = this.windowView.pushWindow(MyWindowComponent);
myWindow.result$.subscribe( result => /** Do something */);
```

- `WindowViewService#getWindowInstanceAt` rename to `WindowViewService#getInstanceAt`.

- `WindowViewService#removeWindowByInstance` rename to `WindowViewService#removeByInstance`;