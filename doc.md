## ghc
コンパイルは「ghc ファイル名」
```
>>ghc hello.hs
[1 of 1] Compiling Main             ( hello.hs, hello.o )
Linking hello.exe ...

>>hello
Hello World
Windowsの場合、コンパイルを行うと中間ファイル(.hiと.o)と実行ファイル(.exe)が作成される
実行は通常の実行ファイルと同じように
```
## runghc
コンパイル＆実行のコマンドは「runghc」
```
>>runghc hello.hs
Hello World
```
