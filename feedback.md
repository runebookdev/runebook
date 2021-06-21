# Feedback History

Issue

[#406](https://github.com/runebookdev/runebook/issues/406)

User

[Summer498](https://github.com/Summer498/)

Language

```
ja
```

Document

```
gcc
```


English

```
If you are writing a header file that must work when included in ISO C programs, write <code><strong>typeof</strong></code> instead of <code>typeof</code>. See <a href="alternate-keywords#Alternate-Keywords">Alternate Keywords</a>.
```

Before

```
ISO Cプログラムに含まれたときに必須の作業というヘッダファイルを作成している場合、書き込みが <code>__typeof__</code> の代わりに <code>typeof</code> 演算。<a href="alternate-keywords#Alternate-Keywords">代替キーワードを</a>参照してください。
```


After

```
ISO Cプログラムに含まれたときに機能するべきヘッダファイルを作成している場合、<code>typeof</code> の代わりに<code><strong>typeof</strong></code>と書いてください。<a href="alternate-keywords#Alternate-Keywords">代替キーワードを</a>参照してください。
```

---
Thanks!