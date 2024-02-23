<h1 align="center" >ZenNotes</h1>


<div align="center">
  
  <a href="https://opensource.org/licenses/MIT">![License](https://img.shields.io/badge/License-MIT-yellow)</a>
  <a href="https://github.com/rohankishore/ZenNotes/releases">![Demo](https://img.shields.io/badge/Download-Now-indigo)</a>
  <a href="https://www.fiverr.com/rohancodespy/">![Demo](https://img.shields.io/badge/Fiverr-Hire-green)</a>
    <a style="text-decoration:none">
    <img src="https://img.shields.io/github/downloads/rohankishore/ZenNotes/total.svg"/>
  </a>
</div>

## ✍️ What is ZenNotes?
ZenNotes is a minimalistic Notepad app with a sleek design inspired by [Fluent Design](https://fluent2.microsoft.design/). It offers the familiar look of the Windows Notepad while having much more powerful features like Translate, TTS, etc.

![image](https://github.com/rohankishore/ZenNotes/assets/109947257/542f9d8a-8e02-4bfd-a469-f91e9873f60a)

![image](https://github.com/rohankishore/ZenNotes/assets/109947257/49edd3d1-08b9-472b-ae31-0982683687bb)

<br>

## 📃 Features

- Edit files (duh)
- Windows Fluent Design with Mica support
- Built-in Translation
- Text to Speech
- Encrypt and Decrypt
- Markdown support (Note: BR and HR may require closing tags to work)

<br>

## 👒 Getting Started

##### You can either Download Notes(1) by going to the [Releases](https://github.com/rohankishore/ZenNotes/releases) page or build it yourself by following the steps below.

- Clone the repo / Download it
- ```bash
  pip install -r requirements.txt
  ```

- ```bash
  python -m main.py
  ```

### Build ZenNotes

```bash
python -m build.py
```

or type in the [Pyinstaller](https://pypi.org/project/pyinstaller/) command:

```bash
pyinstaller --onedir -w --icon="icon.ico" main.py
```


<br>

## 💖 Credits & Acknowledgements

This project was made possible because of [zhiyiYp](https://github.com/zhiyiYp)'s [PyQt-Fluent-Widgets](https://github.com/zhiyiYo/PyQt-Fluent-Widgets).

Icon Credit : [Fluent Icons](https://fluenticons.co/)

<br>


## 🪪 License

This project is licensed under the MIT License. See LICENSE.md for more info.

