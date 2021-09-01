# Python-Questions
A long list of (advanced) Python questions, and their explanations ✨
<!--
<div align="center">
  <img height="60" src="https://img.icons8.com/color/48/000000/python--v1.png"/>
  <h1>JavaScript Questions</h1>

---

<span>I post multiple choice JavaScript questions on my [Instagram](https://www.instagram.com/theavocoder) **stories**, which I'll also post here! Last updated: <a href=#20200612><b>June 12th</b></a>

From basic to advanced: test how well you know JavaScript, refresh your knowledge a bit, or prepare for your coding interview! :muscle: :rocket: I update this repo regularly with new questions. I added the answers in the **collapsed sections** below the questions, simply click on them to expand it. It's just for fun, good luck! :heart:</span>

Feel free to reach out to me! 😊 <br />
<a href="https://www.instagram.com/theavocoder">Instagram</a> || <a href="https://www.twitter.com/lydiahallie">Twitter</a> || <a href="https://www.linkedin.com/in/lydia-hallie">LinkedIn</a> || <a href="https://www.lydiahallie.dev">Blog</a>
</div>

| Feel free to use them in a project! 😃  I would _really_ appreciate a reference to this repo, I create the questions and explanations (yes I'm sad lol) and the community helps me so much to maintain and improve it! 💪🏼 Thank you and have fun!   |
|---|

---

<details><summary><b> See 18 Available Translations 🇸🇦🇪🇬🇧🇦🇩🇪🇪🇸🇫🇷🇮🇩🇯🇵🇰🇷🇳🇱🇧🇷🇷🇺🇹🇭🇹🇷🇺🇦🇻🇳🇨🇳🇹🇼</b></summary>
<p>

- [🇸🇦 العربية](./ar-AR/README_AR.md)
- [🇪🇬 اللغة العامية](./ar-EG/README_ar-EG.md)
- [🇧🇦 Bosanski](./bs-BS/README-bs_BS.md)
- [🇩🇪 Deutsch](./de-DE/README.md)
- [🇪🇸 Español](./es-ES/README-ES.md)
- [🇫🇷 Français](./fr-FR/README_fr-FR.md)
- [🇮🇩 Indonesia](./id-ID/README.md)
- [🇯🇵 日本語](./ja-JA/README-ja_JA.md)
- [🇰🇷 한국어](./ko-KR/README-ko_KR.md)
- [🇳🇱 Nederlands](./nl-NL/README.md)
- [🇧🇷 Português Brasil](./pt-BR/README_pt_BR.md)
- [🇷🇺 Русский](./ru-RU/README.md)
- [🇹🇭 ไทย](./th-TH/README-th_TH.md)
- [🇹🇷 Türkçe](./tr-TR/README-tr_TR.md)
- [🇺🇦 Українська мова](./uk-UA/README.md)
- [🇻🇳 Tiếng Việt](./vi-VI/README-vi.md)
- [🇨🇳 简体中文](./zh-CN/README-zh_CN.md)
- [🇹🇼 繁體中文](./zh-TW/README_zh-TW.md)

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




