# Feedback History

Issue

[#417](https://github.com/runebookdev/runebook/issues/417)

User

[seal-git](https://github.com/seal-git/)

Language

```
ja
```

Document

```
flask
```


English

```
So far we only split up the views and the routing, but the module is still loaded upfront. The trick is to actually load the view function as needed. This can be accomplished with a helper class that behaves just like a function but internally imports the real function on first use:
```

Before

```
今のところビューとルーティングだけを分割していますが、モジュールは前もってロードされています。トリックは、必要に応じて実際にビュー関数をロードすることです。これは、関数のように振る舞いますが、最初の使用時に実際の関数を内部的にインポートするヘルパークラスを使うことで実現できます。
```


After

```
今のところビューとルーティングだけを分割していますが、モジュールは前もってロードされています。トリックは、必要に応じて実際にビュー関数をロードすることです。これを実現するヘルパークラスは、関数のように振る舞いますが、最初の使用時に実際の関数を内部的にインポートします。
```

---
Thanks!