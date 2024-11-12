<img src="https://img.shields.io/badge/dynamic/json?&label=Total%20Views&color=bb2527&style=flat&style=for-the-badge&query=%24.views&url=https://api.github-star-counter.workers.dev/user/AstraaDev" alt="Profile Views"></a>
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
       OS  :  i3, macOS
Languages  :  C, ASM, Py
   Editor  :  VIM, forever and ever
Debugging  :  Bit by bit, step by step
    Motto  :  Seek strength. The rest will follow.
```
