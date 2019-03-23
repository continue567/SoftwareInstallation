Самый простой способ установить матлаб это запустить "SetupSimple.exe"
При этом не надо закрывать программу "SetupSimple" до того как закончится установка Матлаба.
Кога вас попросят активировать программу ОТКАЖИТЕСЬ.

Если упрощенный способ не сработал придется проделать установку вручную по пунктам:
(для экономии времени можно попробовать сначала сделать только пункт 7 ... 
 если не помогло - то придется проделать все с пункта 1)

Всегда выбираем опцию без использования интернет "without using the internet"
Ниже "X:\" означает букву диска куда вы смонтировали iso-образ c установщиком Матлаба)

1) запустить "X:\setup.exe"
    ИЛИ 
   запустить "X:\bin\win32\setup.exe" (если хотите установить 32-битный матлаб под 64-битной виндовз)
2) выбрать "install manually without using the internet"		
3) когда спросят ввести "file installation key" ввести
   12313-94680-65562-90832
4) установить Маталаб (если хотите чтобы Матлаб занимал меньше места и был чуточку быстрее
    то выбирайте "Custom" установку и устанавливайте ТОЛЬКО требуемые в вашей работе компоненты)
5) когда вас попросит активировать можно ЛИБО отказаться от активации
    ЛИБО согласиться и выбрать способ активации без интренета и указать файл лицензии "X:\serial\license.lic"
7) скопировать папку "bin"
    из папки "X:\serial\MatlabX32" или "X:\serial\MatlabX64" (в зависимость от битности установленного матлаба)
    в папку куда вы установили Матлаб  С ПЕРЕЗАПИСЬЮ  файлов 
    Это действие может потребовать от вас Административных прав (для виндовз новее чем WinXP)  



For english-speaking persons:

The simplest way to install Matlab is to run "SetupSimple.exe"
Do not close "SetupSimple" programm until installation of Matlab is finished.
When you will be ascked to activate the program REFUSE to do so.

If simplified setup does not work for you just execute folowing steps manually:
(to save time try to execute STEP 7 ONLY ...  and if it did not helped - execute all steps from step 1)

(let the "X:\" be the letter of mounted matlab dvd-image)
1) run "X:\setup.exe"
    OR 
   run "X:\bin\win32\setup.exe" (if you want to install 32-bit Matlab under 64-bit Windows)
2) choose "install manually without using the internet"		
3) when you will be asked to enter the "file installation key" use
    12313-94680-65562-90832
4) setup Matlab (if you want Matlab to use less space and be little bit faster select "Custom" setup
    and select ONLY componets required for you)
5) when asked to activate the product select activation without internet
6) select "X:\serial\license.lic" when asked for license file
7) copy folder "bin" and its content
    from folder "X:\serial\MatlabX32" or "X:\serial\MatlabX64" (depending on 32-bit or 64-bit you have installed)
    to folder where you installed Matlab  WITH OVERWRITING  of existing files
    This could ask you to use Administrative rights (for Windows newer then WinXP)  
