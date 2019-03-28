# mac 操作


### mac 安装软件包 brew
- https://brew.sh/index_zh-cn
- brew 安装

```aidl

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```


```aidl

brew install wget


```

```aidl
$ cd /usr/local
$ find Cellar
Cellar/wget/1.16.1
Cellar/wget/1.16.1/bin/wget
Cellar/wget/1.16.1/share/man/man1/wget.1

 ls -l bin
```


### brew 安装软件包
```aidl
 brew install cmake
```



###  c++ 升级到 4.9 
- https://www.cnblogs.com/iscodercn/p/8482975.html
- 安装 gcc@4.9

```aidl
brew install gcc@4.9

```

- 设置别称,vi ~/.zshrc

```aidl
alias gcc="gcc-4.9"
alias g++="g++-4.9"
alias cc="gcc-4.9"
alias c++="c++-4.9"
```

- 查看版本,重新打开终端才生效

```aidl
gcc -v

```


```aidl
g++ --version
g++-4.9 (Homebrew GCC 4.9.4_1) 4.9.4
Copyright (C) 2015 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```