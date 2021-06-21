# Feedback History

Issue

[#405](https://github.com/runebookdev/runebook/issues/405)

User

[tkoba965](https://github.com/tkoba965/)

Language

```
ja
```

Document

```
cmake
```


English

```
If <a href="../prop_tgt/skip_build_rpath#prop_tgt:SKIP_BUILD_RPATH" id="index-1-prop_tgt:SKIP_BUILD_RPATH"><code>SKIP_BUILD_RPATH</code></a>, <a href="../variable/cmake_skip_rpath#variable:CMAKE_SKIP_RPATH" id="index-1-variable:CMAKE_SKIP_RPATH"><code>CMAKE_SKIP_RPATH</code></a> or <a href="../variable/cmake_skip_install_rpath#variable:CMAKE_SKIP_INSTALL_RPATH" id="index-1-variable:CMAKE_SKIP_INSTALL_RPATH"><code>CMAKE_SKIP_INSTALL_RPATH</code></a> were used to strip the directory portion of the <code>install_name</code> of a target, one may set <code>INSTALL_NAME_DIR=""</code> instead.
```

Before

```
場合<a href="../prop_tgt/skip_build_rpath#prop_tgt:SKIP_BUILD_RPATH" id="index-1-prop_tgt:SKIP_BUILD_RPATH"> <code>SKIP_BUILD_RPATH</code> </a>、<a href="../variable/cmake_skip_rpath#variable:CMAKE_SKIP_RPATH" id="index-1-variable:CMAKE_SKIP_RPATH"> <code>CMAKE_SKIP_RPATH</code> </a>又は<a href="../variable/cmake_skip_install_rpath#variable:CMAKE_SKIP_INSTALL_RPATH" id="index-1-variable:CMAKE_SKIP_INSTALL_RPATH"> <code>CMAKE_SKIP_INSTALL_RPATH</code> は</a>ディレクトリ部分剥離するために使用された <code>install_name</code> ターゲットを、一つは設定してもよい <code>INSTALL_NAME_DIR=""</code> 代わりに。
```


After

```
もし<a href="../prop_tgt/skip_build_rpath#prop_tgt:SKIP_BUILD_RPATH" id="index-1-prop_tgt:SKIP_BUILD_RPATH"> <code>SKIP_BUILD_RPATH</code> </a>、<a href="../variable/cmake_skip_rpath#variable:CMAKE_SKIP_RPATH" id="index-1-variable:CMAKE_SKIP_RPATH"> <code>CMAKE_SKIP_RPATH</code> </a>又は<a href="../variable/cmake_skip_install_rpath#variable:CMAKE_SKIP_INSTALL_RPATH" id="index-1-variable:CMAKE_SKIP_INSTALL_RPATH"> <code>CMAKE_SKIP_INSTALL_RPATH</code> を</a> <code>install_name</code> ターゲットを空にするために使いたければ <code>INSTALL_NAME_DIR=""</code> を指定します。
```

---
Thanks!