# 🚀 ZenTop Monitor
<img width="443" height="423" alt="Снимок экрана от 2026-07-09 22-38-38" src="https://github.com/user-attachments/assets/d257bc7f-8a5c-4b99-a397-be409e845a4c" />

<img width="437" height="321" alt="Снимок экрана от 2026-07-09 22-39-05" src="https://github.com/user-attachments/assets/ec49d25f-2f5c-4c09-894d-96425986f31e" />




**ZenTop** is a fast, lightweight and adaptive system resource monitor on pure Bash for Linux. It updates data smoothly at 200 ms (5 FPS) without straining the processor or flickering when redrawn. (— это быстрый, легкий и адаптивный монитор системных ресурсов на чистом Bash для Linux. Он плавно обновляет данные на частоте 200 мс (5 FPS), не нагружая процессор и не мерцая при перерисовке.)

## ✨ Basic features (Основные фишки)
- **Dynamic design** (**Динамический дизайн**): automatically adjusts to the size of the terminal window. If the window is smaller than 62x24, the script hides the graphics, preventing layout failure. **(** автоматически подстраивается под размеры окна терминала. Если окно меньше 62x24, скрипт прячет графику, предотвращая сбой верстки.**)**
- **Smart CPU definition** (**Умное определение CPU**): the script polls `/proc/cpuinfo` and displays the proprietary ASCII logo depending on what processor you have — AMD or Intel. **(** скрипт опрашивает `/proc/cpuinfo` и выводит фирменный ASCII-логотип в зависимости от того, какой у вас процессор — AMD или Intel.**)**
- **Multi-level palette** (**Многоуровневая палитра**): the percentages of RAM and battery smoothly change their color from green to dangerous red depending on the current load. **(** проценты оперативной памяти и батареи плавно меняют свой цвет от зеленого до опасного красного в зависимости от текущей нагрузки.**)**
- **Hacker Easter eggs** (**Хакерские пасхалки**): if you run the script on an unrecognized processor, the utility will produce a daring: *«CPU not recognized, but you're cool anyway!»*. **(** если запустить скрипт на нераспознанном процессоре, утилита выдаст дерзкое: *«CPU not recognized, but you're cool anyway!»*.**)**
- **Garbage protection** (**Защита от мусора**): keyboard input is completely blocked while the script is running, protecting the screen from accidental keystrokes. The output is strictly according to `Ctrl + C` with the output of a beautiful final logo. **(** ввод клавиатуры полностью блокируется во время работы скрипта, защищая экран от случайных нажатий клавиш. Выход строго по `Ctrl + C` с выводом красивого финального логотипа.**)**

## 🛠️ Launch (Как запустить)
1. Download the script and make it executable **(** Скачайте скрипт и сделайте его исполняемым **)**:
 
   chmod +x zentop-en  ///  chmod +x zentop-ru

3. Run the program **(** Запустите программу **)**:
   
   ./zentop-en  ///  ./zentop-ru
