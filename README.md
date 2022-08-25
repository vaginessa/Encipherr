<p align="center">
  <a href="https://encipherr.pythonanywhere.com/">
    <img src="https://github.com/Oussama1403/Encipherr/blob/main/project-src/static/pwa/512x512-blue.png" width="100">
  </a>
  <h3 align="center">Encipherr</h3>

 
  <p align="center">
    Free online encryption and decryption tool.
    <br>
    <a href="https://encipherr.pythonanywhere.com/"><strong> Explore Encipherr »</strong></a>
  </p>
</p>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<div align="center">

[contributors-shield]: https://img.shields.io/github/contributors/Oussama1403/Encipherr.svg?style=for-the-badge
[contributors-url]: https://github.com/Oussama1403/Encipherr/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Oussama1403/Encipherr.svg?style=for-the-badge
[forks-url]: https://github.com/Oussama1403/Encipherr/network/members
[stars-shield]: https://img.shields.io/github/stars/Oussama1403/Encipherr.svg?style=for-the-badge
[stars-url]: https://github.com/Oussama1403/Encipherr/stargazers
[issues-shield]: https://img.shields.io/github/issues/Oussama1403/Encipherr.svg?style=for-the-badge
[issues-url]: https://github.com/Oussama1403/Encipherr/issues
[license-shield]: https://img.shields.io/github/license/Oussama1403/Encipherr.svg?style=for-the-badge
[license-url]: https://github.com/Oussama1403/Encipherr/blob/main/LICENSE.txt

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


### Made with love using:
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

</div>

## About The Project

[![screenshot](screenshot.png)](https://encipherr.pythonanywhere.com/)

Encipherr is a web application developed with <a href="https://flask.palletsprojects.com/en/2.0.x/" target="_blank">Flask</a> & 
<a href="https://getbootstrap.com" target="_blank">Bootstrap Framework</a>.It offers a free powerful encryption of texts and files using <a href="https://fr.wikipedia.org/wiki/Advanced_Encryption_Standard" target="_blank">AES</a> encryption algorithm.  
AES is both fast, and cryptographically strong. It is a good default choice for encryption.  
Try Encipherr now.

## Usage
Visit <a href="https://Encipherr.pythonanywhere.com/" target="_blank">Encipherr website</a> \
or install project files and run it locally:

```bash
git clone https://github.com/Oussama1403/Encipherr

```
The project directory will contain:
```
├── CHANGELOG.md
├── LICENSE.txt
├── project-src
│   ├── db.sqlite3
│   ├── flask_app.py
│   ├── static
│   │   ├── css
│   │   │   └── style.css
│   │   ├── eg.html
│   │   ├── js
│   │   │   ├── ajaxcall.js
│   │   │   ├── egg.js
│   │   │   └── upload.js
│   │   ├── logo.png
│   │   └── pwa
│   │       ├── 512x512-blue.png
│   │       ├── 512x512.png
│   │       ├── app.js
│   │       ├── manifest.json
│   │       └── offline.html
│   ├── sw.js
│   └── templates
│       ├── about.html
│       ├── base.html
│       ├── home.html
│       └── privacy.html
├── README.md
├── requirements.txt
└── screenshot.png

```

:warning: Make sure python3 and flask framework are installed.

install modules:
```bash
pip install -r requirements.txt
```
then run the server by typing in your terminal:

```python
python3 flask_app.py
```
## CHANGELOG
Read the latest notable changes made to a Encipherr.[here](CHANGELOG.md)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to test your changes.

## License
[MIT](https://choosealicense.com/licenses/mit/)
