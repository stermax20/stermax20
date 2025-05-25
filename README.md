<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=stermax20's%20Github.&fontSize=90" />
</div>

<div style="text-align: left;">
  <h2 style="border-bottom: 1px solid #21262d; color: #c9d1d9;"> 🖐️ Hello, World! </h2>
</div>

```nasm
section .data:
  message: db "Hello, World!", 0x0a
  message_length equ $-message

section .text:
global _start

_start:
  mov eax, 0x4
  mov ebx, 1
  mov ecx, message
  mov edx, message_length
  int 0x80

  mov eax, 0x1
  mov ebx, 0
  int 0x80
```

<div style="text-align: left;">
  <div style="font-weight: 700; font-size: 15px; text-align: left; color: #c9d1d9;">
    <p>Thank you for visiting my GitHub. I'm stermax20 (Minseok Kim), a senior at Gyeongbuk Software Meister High School.<br> 
      As a software development major, I'm studying algorithm, backend development and domain driven design.<br> 
      Ultimately, my goal is to become a backend developer who sticks to DDD.</p>
  </div>
</div>

<div style="text-align: left;">
  <br>
  <h2 style="border-bottom: 1px solid #21262d; color: #c9d1d9;"> 🧑‍💻 Contact me </h2>
  <br>
  <div style="text-align: left;">
    <a href="http://www.stermax20.kro.kr">
      <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white&link=http://www.stermax20.kro.kr">
    </a>
    <a href="mailto:stermax20@outlook.kr">
      <img src="https://img.shields.io/badge/Outlook-005FF9?style=for-the-badge&logo=Outlook&logoColor=white&link=mailto:stermax20@outlook.kr">
    </a>
  </div>
  <br>
  <br>
  <h2 style="border-bottom: 1px solid #21262d; color: #c9d1d9;"> 🤖 My Baekjoon Tier </h2>
  <br>
  
  [![Solved.ac프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=stermax20)](https://solved.ac/stermax20)
  <br>
  <br>
  <h2 style="border-bottom: 1px solid #21262d; color: #c9d1d9;"> 🧠 Stacks </h2>
  <br>
  
  ![jsp](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=JSP&logoColor=white)
  ![springboot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
  ![express](https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white)
  ![nestjs](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
  ![junit5](https://img.shields.io/badge/junit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
  ![jest](https://img.shields.io/badge/jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
</div>
