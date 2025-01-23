![](https://komarev.com/ghpvc/?username=astraadev&color=bb2527&abbreviated=true)
<img src="https://img.shields.io/badge/dynamic/json?&label=Total%20Stars&color=bb2527&style=flat&style=for-the-badge&query=%24.stars&url=https://api.github-star-counter.workers.dev/user/AstraaDev" alt="Profile Stars"></a>
<img src="https://img.shields.io/badge/dynamic/json?&label=Total%20Forks&color=bb2527&style=flat&style=for-the-badge&query=%24.forks&url=https://api.github-star-counter.workers.dev/user/AstraaDev" alt="Profile Forks"></a>

```asm
section .data
    msg db 'a5traa', 0

section .text
    global _start

_start:
    mov eax, 4
    mov ebx, 1
    mov ecx, msg
    mov edx, 6
    int 0x80

    mov eax, 1
    xor ebx, ebx
    int 0x80
```

```lua
       OS  :  macOS, debian
Languages  :  C, Cpp, ASM, Py, Java
   Editor  :  vim
    Motto  :  Seek strength. The rest will follow.
```
