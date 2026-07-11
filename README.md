# 🚀 ZenTop Monitor
<img width="750" height="572" alt="Снимок экрана от 2026-07-11 17-53-23" src="https://github.com/user-attachments/assets/35582094-10e2-40f7-83ac-a065caf2d884" />

<img width="750" height="572" alt="Снимок экрана от 2026-07-11 17-53-29" src="https://github.com/user-attachments/assets/b0afedc4-a15b-4473-8b27-d0054c5a5737" />

<img width="750" height="572" alt="Снимок экрана от 2026-07-11 17-53-44" src="https://github.com/user-attachments/assets/f7800ea4-0b13-48e4-8231-b8ef1826b7d4" />

<img width="750" height="572" alt="Снимок экрана от 2026-07-11 17-53-48" src="https://github.com/user-attachments/assets/c4a61386-9a9e-44aa-922b-0a98e86edb84" />



**ZenTop** is a fast, lightweight and adaptive system resource monitor on pure Bash for Linux. It updates data smoothly at 200 ms (5 FPS) without straining the processor or flickering when redrawn. 

**ZenTop** — это быстрый, легкий и адаптивный монитор системных ресурсов на чистом Bash для Linux. Он плавно обновляет данные на частоте 200 мс (5 FPS), не нагружая процессор и не мерцая при перерисовке.

## ✨ Basic features (Основные фишки)
- **Dynamic design**: automatically adjusts to the size of the terminal window. If the window is smaller than 62x24, the script hides the graphics, preventing layout failure.
     **|**
     **Динамический дизайн**: автоматически подстраивается под размеры окна терминала. Если окно меньше 62x24, скрипт прячет графику, предотвращая сбой верстки.
  
- **Smart CPU definition**: the script polls `/proc/cpuinfo` and displays the proprietary ASCII logo depending on what processor you have — AMD or Intel.
     **|**
     **Умное определение CPU**: скрипт опрашивает `/proc/cpuinfo` и выводит фирменный ASCII-логотип в зависимости от того, какой у вас процессор — AMD или Intel.
  
- **Multi-level palette**: the percentages of RAM and battery smoothly change their color from green to dangerous red depending on the current load.
     **|**
     **Многоуровневая палитра**: проценты оперативной памяти и батареи плавно меняют свой цвет от зеленого до опасного красного в зависимости от текущей нагрузки.
  
- **Hacker Easter eggs**: if you run the script on an unrecognized processor, the utility will produce a daring: *«CPU not recognized, but you're cool anyway!»*.
     **|**
     **Хакерские пасхалки**: если запустить скрипт на нераспознанном процессоре, утилита выдаст дерзкое: *«CPU not recognized, but you're cool anyway!»*.
  
- **Garbage protection**: keyboard input is completely blocked while the script is running, protecting the screen from accidental keystrokes. The output is strictly according to `Ctrl + C` with the output of a beautiful final logo.
     **|**
     **Защита от мусора**: ввод клавиатуры полностью блокируется во время работы скрипта, защищая экран от случайных нажатий клавиш. Выход строго по `Ctrl + C` с выводом красивого финального логотипа.

## 🛠️ Launch (Как запустить)
1. Download the script and make it executable (Скачайте скрипт и сделайте его исполняемым ):
   
   chmod +x zentop-en  ///  chmod +x zentop-ru

3. Run the program (Запустите программу):
   ``` Bash 
   ./zentop-en  ///  ./zentop-ru
   ```
