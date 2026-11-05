<div align="center">

# 👋 Hi, I'm Dmytro Stramousov

</div>

---

## 📈 GitHub activity

<div align="center">

<!-- Total Commits: includes commits from previous years, as counted by the widget. -->
<img src="https://github-readme-stats.vercel.app/api?username=dstramousov&show_icons=true&include_all_commits=true&number_format=long&theme=github_dark&hide_border=true&rank_icon=github" alt="GitHub statistics including total commits" />

<!-- Contributions include activity beyond commits. The chart shows public contribution activity. -->
<img src="https://ghchart.rshah.org/2ea043/dstramousov" width="100%" alt="GitHub contributions calendar" />

</div>

---


## About me

Software and Performance Test Engineer with 20+ years of experience in software development, UNIX environments, distributed systems and performance engineering.

I like building software that interacts with real things.

- ⚡ Performance, load, smoke and regression testing
- 🔎 Bottleneck analysis and system diagnostics
- 🐧 Linux / UNIX as the primary engineering environment
- 🧪 Backend and frontend test automation
- 🐍 Python tooling and automation
- 🐳 Dockerized test and development environments
- 🔧 Hardware, serial interfaces and embedded experiments
- 🎮 Game engines, graphics and procedural systems
- 🕹 Retro computers, emulation and old hardware
- 🧠 Experiments are more interesting than buzzwords

> Build it. Measure it. Break it. Understand it. Improve it.

## 🎮 MODE256 256*192 = 49 152 пикселя ностальгии.

Когда-то демосцена ZX Spectrum поразила меня магией на 3,5 МГц, и 48 килобайтами памяти и палитрой, которая напоминала бред шизофреника. 
Из ограничения сделали искусство из которого появились Дмитрии Гуртяк и иже с ними, а из каждого такта - восхтщение неофита , т.е. меня.
С тех пор прошло сорок лет: памяти теперь достаточно даже программам, которым "**достаточно 640Кб**". Но захотелось проверить, **что будет, если вернуть экрану честные 256×192 пикселя, а вычисления доверить современному CPU**. 
Так появился то чем я занимаюсь вечерами - Mode256,  2D/2.5D движок, в котором можно увидеть, или не увидеть то что когда то волновало.

### Что  работает

- **🎨 Программный рендеринг.** Собственный CPU-рендерер, RGBA, прозрачность, слои, буфер глубины и целочисленное масштабирование без "Игорьтонет". В кадре ровно **49 152 пикселя**.
- **🌲 Игровые миры и растительность.** Большие карты, камера, тайлы, сооружения и более **1300 растений** в лесной сцене. Контент собирается в **Tiled**, затем проходит собственный компилятор.
- **💡 Свет и тени.** Цветные источники, прожекторы, высота света, затухание, затенение поверхностей, силуэтные тени и геометрия сооружений.
- **🌧️ Погода и частицы.** Дождь, снег, ветер, порывы, турбулентность, искры, дым и фонтаны частиц. Осадки взаимодействуют с поверхностями и глубиной сцены.
- **🔥 Огонь.** Анимированные костры, искры и мерцающий тёплый свет.
- **📦 Физика и разрушения.** **Box2D**: столкновения, масса, инерция, вращение и толкание предметов. Ящики накапливают повреждения и распадаются на физические обломки.
- **🔫 Оружие и эффекты.** Пистолет и автоматическое оружие, отдача, разброс, перезарядка, трассеры, вспышки, рикошеты, дым и следы попаданий. Выстрелы на мгновение освещают сцену.
- **🤖 AI противников.** Охрана, патрулирование, поле зрения, проверка прямой видимости, память о последнем контакте, поиск точки наблюдения и обход препятствий.
- **🎮 Управление и камера.** Клавиатура, мышь, геймпад, физическое движение персонажа, плавное слежение камеры и навигационная инфраструктура.
- **🎵 Звук старой школы.** **PT3, TurboSound, AYFX** — музыка и эффекты с узнаваемым характером AY.
- **🔧 Инструменты и оптимизация.** **F12 Developer Inspector**, профилирование, настройка эффектов, пространственные индексы, отсечение невидимых объектов и кеширование.

**Технологии:** C++ · SDL3 · Box2D · Tiled · Python · CMake · Linux.

**Mode256 пока не готовая игра**, а развивающийся движок и лаборатория. Классическая демосцена доказывала, что невозможное можно показать.

*Когда-то 48 килобайт хватало для чуда. Теперь у нас гигабайты — и всё те же 256×192 пикселя, которые напоминают с чего это начиналось.*

---

<div align="center">
  <img
    src="Mode256_v0.0.187_Showreel_Smooth-1.webp"
    width="700"
    alt="Mode256 — Pixel Engine Demo"
  />
</div>

---

## 🛠 Tech & tools

### Performance & testing

<p>
  <img src="https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white" />
  <img src="https://img.shields.io/badge/Gatling-FF9E2A?style=for-the-badge&logo=gatling&logoColor=white" />
  <img src="https://img.shields.io/badge/WebPageTest-2C5E9E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Lighthouse-F44B21?style=for-the-badge&logo=lighthouse&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/Performance_Testing-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Load_Testing-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Smoke_Testing-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Regression_Testing-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Backend_Testing-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Frontend_Testing-111111?style=flat-square" />
</p>

### Development

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Perl-39457E?style=for-the-badge&logo=perl&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
</p>

### Backend, infrastructure & data

<p>
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Linux-111111?style=for-the-badge&logo=linux&logoColor=white" />
</p>

### Everyday tools

<p>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</p>

<details>
<summary><b>Legacy stack & older systems</b></summary>
<br>

`PHP` · `Perl` · `MySQL` · `Oracle` · `Informix` · `XML` · `AJAX` · `jQuery` · `Shell scripting`

</details>

---

## 🎓 Early certifications

> Brainbench certifications from the early 2000s

<p>
  <img src="https://img.shields.io/badge/Brainbench-C%20Programmer-2f81f7?style=for-the-badge" /><br>
  <img src="https://img.shields.io/badge/Brainbench-Perl%20Programmer-39457E?style=for-the-badge" /><br>
  <img src="https://img.shields.io/badge/Brainbench-Linux%20Programming%20(General)-FCC624?style=for-the-badge&logo=linux&logoColor=black" /><br>
</p>

- **Linux Programming (General)** — Brainbench, 2000
- **Perl Programmer** — Brainbench, 2001
- **C Programmer** — Brainbench, 2001
