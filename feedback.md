# Feedback History

Issue

[#443](https://github.com/runebookdev/runebook/issues/443)

User

[sdass12](https://github.com/sdass12/)

Language

```
ko
```

Document

```
jest
```


English

```
<code>expect.extend</code> also supports async matchers. Async matchers return a Promise so you will need to await the returned value. Let's use an example matcher to illustrate the usage of them. We are going to implement a matcher called <code>toBeDivisibleByExternalValue</code>, where the divisible number is going to be pulled from an external source.
```

Before

```
<code>expect.extend</code> 는 비동기 매처도 지원합니다. 비동기 매처는 약속을 반환하므로 반환 된 값을 기다려야합니다. 예시적인 matcher를 사용하여 사용법을 설명해 봅시다. 우리는 <code>toBeDivisibleByExternalValue</code> 라는 매처를 구현할 것인데 , 여기서 divisible 숫자는 외부 소스에서 가져옵니다.
```


After

```
<code>expect.extend</code> 는 비동기 매처도 지원합니다. 비동기 매처는 프로미스를 반환하므로 반환 된 값을 기다려야합니다. 예시적인 매처를 사용하여 사용법을 설명해 봅시다. 우리는 <code>toBeDivisibleByExternalValue</code> 라는 매처를 구현할 것인데 , 여기서 divisible 숫자는 외부 소스에서 가져옵니다.
```

---
Thanks!