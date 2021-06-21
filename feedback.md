# Feedback History

Issue

[#423](https://github.com/runebookdev/runebook/issues/423)

User

[simonNozaki](https://github.com/simonNozaki/)

Language

```
ja
```

Document

```
kotlin
```


English

```
What does this signature say? It says that every time I append a string to something (a <code>StringBuilder</code>, some kind of a log, a console, etc.) I have to catch those <code>IOExceptions</code>. Why? Because it might be performing IO (<code>Writer</code> also implements <code>Appendable</code>)&hellip; So it results in this kind of code all over the place:
```

Before

```
この署名は何と言っていますか？何か（ <code>StringBuilder</code> 、ある種のログ、コンソールなど）に文字列を追加するたびに、それらの <code>IOExceptions</code> をキャッチする必要があると書かれています。どうして？IOを実行している可能性があるため（ <code>Writer</code> は <code>Appendable</code> も実装しています）&hellip;したがって、この種のコードがいたるところに発生します。
```


After

```
このシグネチャは何を伝えているでしょうか？ <code>StringBuilder</code> 、ある種のログ、コンソールなどのなにかに文字列を付け加えるたび、それらの <code>IOExceptions</code> をキャッチする必要があると書かれています。なぜでしょうか？文字列が付け加えられたものがIOを実行している可能性があるため（ <code>Writer</code> は <code>Appendable</code> も実装しています）…したがって、この種のコードがいたるところに発生します。
```

---
Thanks!