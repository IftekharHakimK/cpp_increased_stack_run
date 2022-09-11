Say your filename is ``a.cpp``. First compile to create executable (named as ``a.exe``). You may use ``-std=c++11`` or ``-std=c++14`` etc too. You may change stack size too.
```
> g++ -O2 -std=c++17 -Wall -Wl,--stack=268435456 a.cpp -o a.exe
```
If your input filename is ``input.txt`` and intended output filename is ``output.txt``, 
```
> a.exe < input.txt > output.txt
```
