# Feedback History

Issue

[#408](https://github.com/runebookdev/runebook/issues/408)

User

[mrsh71](https://github.com/mrsh71/)

Language

```
ko
```

Document

```
julia
```


English

```
Though most code can be written in Julia, there are many high-quality, mature libraries for numerical computing already written in C and Fortran. To allow easy use of this existing code, Julia makes it simple and efficient to call C and Fortran functions. Julia has a "no boilerplate" philosophy: functions can be called directly from Julia without any "glue" code, code generation, or compilation &ndash; even from the interactive prompt. This is accomplished just by making an appropriate call with <a href="../../base/c/index#ccall"><code>ccall</code></a> syntax, which looks like an ordinary function call.
```

Before

```
대부분의 코드는 Julia로 작성할 수 있지만 C와 Fortran으로 이미 작성된 수치 컴퓨팅을위한 고품질의 성숙 라이브러리가 많이 있습니다. 이 기존 코드를 쉽게 사용할 수 있도록 Julia는 C 및 Fortran 함수를 간단하고 효율적으로 호출 할 수 있도록합니다. Julia는 "보일러 플레이트 없음"철학을 가지고 있습니다. "접착제"코드, 코드 생성 또는 컴파일없이 대화 형 프롬프트에서도 함수를 Julia에서 직접 호출 할 수 있습니다. 이것은 일반적인 함수 호출처럼 보이는 <a href="../../base/c/index#ccall"> <code>ccall</code> </a> 구문으로 적절한 호출을 수행함으로써 달성됩니다 .
```


After

```
대부분의 코드는 Julia로 작성할 수 있지만 C와 Fortran으로 이미 작성된 수치 컴퓨팅을위한 고품질의 성숙 라이브러리가 많이 있습니다. 이 기존 코드를 쉽게 사용할 수 있도록 Julia는 C 및 Fortran 함수를 간단하고 효율적으로 호출 할 수 있도록합니다. Julia는 "비고착"철학을 가지고 있습니다. "접착제"코드, 코드 생성 또는 컴파일없이 대화 형 프롬프트에서도 함수를 Julia에서 직접 호출 할 수 있습니다. 이것은 일반적인 함수 호출처럼 보이는 <a href="../../base/c/index#ccall"> <code>ccall</code> </a> 구문으로 적절한 호출을 수행함으로써 달성됩니다 .
```

---
Thanks!