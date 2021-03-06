# Python-Questions
A long list of (advanced) Python questions, and their explanations โจ
<!--
<div align="center">
  <img height="60" src="https://img.icons8.com/color/48/000000/python--v1.png"/>
  <h1>JavaScript Questions</h1>

---

<span>I post multiple choice JavaScript questions on my [Instagram](https://www.instagram.com/theavocoder) **stories**, which I'll also post here! Last updated: <a href=#20200612><b>June 12th</b></a>

From basic to advanced: test how well you know JavaScript, refresh your knowledge a bit, or prepare for your coding interview! :muscle: :rocket: I update this repo regularly with new questions. I added the answers in the **collapsed sections** below the questions, simply click on them to expand it. It's just for fun, good luck! :heart:</span>

Feel free to reach out to me! ๐ <br />
<a href="https://www.instagram.com/theavocoder">Instagram</a> || <a href="https://www.twitter.com/lydiahallie">Twitter</a> || <a href="https://www.linkedin.com/in/lydia-hallie">LinkedIn</a> || <a href="https://www.lydiahallie.dev">Blog</a>
</div>

| Feel free to use them in a project! ๐  I would _really_ appreciate a reference to this repo, I create the questions and explanations (yes I'm sad lol) and the community helps me so much to maintain and improve it! ๐ช๐ผ Thank you and have fun!   |
|---|

---

<details><summary><b> See 18 Available Translations ๐ธ๐ฆ๐ช๐ฌ๐ง๐ฆ๐ฉ๐ช๐ช๐ธ๐ซ๐ท๐ฎ๐ฉ๐ฏ๐ต๐ฐ๐ท๐ณ๐ฑ๐ง๐ท๐ท๐บ๐น๐ญ๐น๐ท๐บ๐ฆ๐ป๐ณ๐จ๐ณ๐น๐ผ</b></summary>
<p>

- [๐ธ๐ฆ ุงูุนุฑุจูุฉ](./ar-AR/README_AR.md)
- [๐ช๐ฌ ุงููุบุฉ ุงูุนุงููุฉ](./ar-EG/README_ar-EG.md)
- [๐ง๐ฆ Bosanski](./bs-BS/README-bs_BS.md)
- [๐ฉ๐ช Deutsch](./de-DE/README.md)
- [๐ช๐ธ Espaรฑol](./es-ES/README-ES.md)
- [๐ซ๐ท Franรงais](./fr-FR/README_fr-FR.md)
- [๐ฎ๐ฉ Indonesia](./id-ID/README.md)
- [๐ฏ๐ต ๆฅๆฌ่ช](./ja-JA/README-ja_JA.md)
- [๐ฐ๐ท ํ๊ตญ์ด](./ko-KR/README-ko_KR.md)
- [๐ณ๐ฑ Nederlands](./nl-NL/README.md)
- [๐ง๐ท Portuguรชs Brasil](./pt-BR/README_pt_BR.md)
- [๐ท๐บ ะ?ัััะบะธะน](./ru-RU/README.md)
- [๐น๐ญ เนเธเธข](./th-TH/README-th_TH.md)
- [๐น๐ท Tรผrkรงe](./tr-TR/README-tr_TR.md)
- [๐บ๐ฆ ะฃะบัะฐัะฝััะบะฐ ะผะพะฒะฐ](./uk-UA/README.md)
- [๐ป๐ณ Tiแบฟng Viแปt](./vi-VI/README-vi.md)
- [๐จ๐ณ ็ฎไฝไธญๆ](./zh-CN/README-zh_CN.md)
- [๐น๐ผ ็น้ซไธญๆ](./zh-TW/README_zh-TW.md)

</p>
</details>

-->

---

###### 1. What's the output?

```
a = int(1.4e2)
b = int("1.4e2")
c = int(3.9)
d = int(True)

print(a)
print(b)
print(c)
print(d)
```

- A: 
```error
   error
   3
   1
```
- B: 
```140
   error
   3
   1
```
- C: 
```140
   140
   3
   1
```
     
<details><summary><b>Answer</b></summary>
<p>

#### Answer: B

int() argument must be a string (like "1" or "2.4" etc), a bytes-like object or a number

</p>
</details>

---

###### 2. What's the output?

```
a = int("hello")
b = int(True)
c = int(3.9)
d = int("3.9")

print(a)
print(b)
print(c)
```

- A: ```
        error
        1
        3
        error
      ```
- B: ```
        1
        1
        4
        3
      ```
- C: ```
        1
        error
        3
        3.9
      ```
- D: ```1
        error 
        4
        error
      ```      
<details><summary><b>Answer</b></summary>
<p>

#### Answer: A

int() argument must be a string (like "1" or "2.4" etc), a bytes-like object or a number

</p>
</details>

---




