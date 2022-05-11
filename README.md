# vscode-cpp
vscode中配置C/C++环境


``` powershell
版权所有 (C) Microsoft Corporation。保留所有权利。
This is free software; see the source for copying conditions.  There is NO       
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.   
   
PS G:\github\c\vscode-cpp> g++ --version
g++.exe (GCC) 11.2.0
Copyright (C) 2021 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO      
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.     

PS G:\github\c\vscode-cpp> if ($?) { g++ test.cpp -o test } ; if ($?) { .\test}  
Hello world
PS G:\github\c\vscode-cpp>
```

## 参考 

https://blog.csdn.net/qq_59403105/article/details/123133959

