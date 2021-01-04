## C++-GCC-Env
C++ programming(gcc) with vscode（For Mac）

### Basic Installation

__gcc__
```
brew install gcc
```

__setup path__

```shell
$ ln -s /usr/local/bin/g++-10 /usr/local/bin/g++
$ exec $SHELL -l
```

NG
```shell
$ which g++
/usr/bin/g++
```

OK
```
$ which g++
/usr/local/bin/g++
```

__Install VSCode Extension__

- [C/C++ for Visual Studio Code](https://code.visualstudio.com/docs/languages/cpp)
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

### Compile & Running
Run `Ctrl + Opt + n`

