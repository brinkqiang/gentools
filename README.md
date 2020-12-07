# 1. gentools

Copyright (c) 2013-2018 brinkqiang (brink.qiang@gmail.com)

# 2. Intro
<!-- TOC -->

- [1. gentools](#1-gentools)
- [2. Intro](#2-intro)
  - [2.1. dmgen 通用工程生成](#21-dmgen-通用工程生成)
  - [2.2. dmgen4cmd 通用命令行工具生成](#22-dmgen4cmd-通用命令行工具生成)
  - [2.3. dmgen4error 通用字符串国际化生成](#23-dmgen4error-通用字符串国际化生成)
  - [2.4. dmgen4gtest 通用gtest框架生成](#24-dmgen4gtest-通用gtest框架生成)
  - [2.5. dmgen4luamodule 通用C++ lua模块生成](#25-dmgen4luamodule-通用c-lua模块生成)
  - [2.6. dmgen4module 通用makefile生成](#26-dmgen4module-通用makefile生成)
- [3. Thanks](#3-thanks)

<!-- /TOC -->

## 2.1. dmgen 通用工程生成
```
通用工程生成 cmake
```
```
dmgen -p projectname
```

## 2.2. dmgen4cmd 通用命令行工具生成
```
通用命令行工具生成 cmake
```
```
dmgen4cmd -p projectname
```

## 2.3. dmgen4error 通用字符串国际化生成
```
通用字符串国际化生成 cmake
```
```
dmgen4error -p projectname
```

## 2.4. dmgen4gtest 通用gtest框架生成
```
通用gtest框架生成 cmake, makefile
```
```
dmgen4gtest -p projectname
```

## 2.5. dmgen4luamodule 通用C++ lua模块生成
```
通用C++ lua模块生成 cmake
```
```
dmgen4luamodule -p projectname
```

## 2.6. dmgen4module 通用makefile生成
```
通用makefile exe版生成
```
```
dmgen4module -p projectname
```

```
通用makefile生成 lib版生成
```
```
dmgen4module -p projectname -t lib
```

# 3. Thanks

