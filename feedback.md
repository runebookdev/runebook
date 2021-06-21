# Feedback History

Issue

[#425](https://github.com/runebookdev/runebook/issues/425)

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
Another case where you may encounter this type is type inference. The nullable variant of this type, <code>Nothing?</code>, has exactly one possible value, which is <code>null</code>. If you use <code>null</code> to initialize a value of an inferred type and there's no other information that can be used to determine a more specific type, the compiler will infer the <code>Nothing?</code> type:
```

Before

```
このタイプに遭遇する可能性のあるもう1つのケースは、タイプの推論です。この型のnull可能なバリアント、 <code>Nothing?</code> には、1つの可能な値、つまり <code>null</code> があります。 <code>null</code> を使用して推論された型の値を初期化し、より具体的な型を決定するために使用できる他の情報がない場合、コンパイラーは <code>Nothing?</code> タイプ：
```


After

```
この型に遭遇する可能性のあるもう1つのケースは、型の推論です。この型のnullになりうるバリアントである <code>Nothing?</code> には、たしかに1つの値、つまり <code>null</code> がありえます。 <code>null</code> を使用して推論された型の値を初期化し、より具体的な型を決定するために使用できる他の情報がない場合、コンパイラーは <code>Nothing?</code> の型を推論します：
```

---
Thanks!