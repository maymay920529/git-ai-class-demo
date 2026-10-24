# Git and AI class demo

A tiny C++ example used in an introductory Git and GitHub lesson.

## Build and run

```powershell
g++ -std=c++17 main.cpp -o demo.exe
./demo.exe --test
"59 60 61" | ./demo.exe
```

Current behavior: only scores above 60 pass.
Next task: include a score of exactly 60 and add a regression test.
