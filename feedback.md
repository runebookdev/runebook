# Feedback History

Issue

[#451](https://github.com/runebookdev/runebook/issues/451)

User

[juggernautjp](https://github.com/juggernautjp/)

Language

```
ja
```

Document

```
babel
```


English

```
When <code>true</code>, this transform will pretend <code>document.all</code> does not exist, and perform loose equality checks with <code>null</code> instead of strict equality checks against both <code>null</code> and <code>undefined</code>.
```

Before

```
場合は <code>true</code> 、これがふります変換 <code>document.all</code> の存在しない、として緩やかな平等のチェックを行う <code>null</code> 代わりの両方に対する厳密な等価性チェックの <code>null</code> と <code>undefined</code> 。
```


After

```
<code>true</code> の場合、この変換は、<code>document.all</code> が存在しないことを装い、<code>null</code>と<code>undefined</code> の両方に対する厳格な等値性チェックの代わりに、<code>null</code> との緩やかな等値性チェックを実行します。
```

---
Thanks!