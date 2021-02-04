<h1> Гайд по установке хакинтоша </h1>
<h2> Введение. Базовые понятия. </h2>
<b> Hackintosh (хакинтош) </b> - это macOS, установленная на обычный компьютер.
Стал возможным, с момента выхода Mac OS X 10.4 Tiger (в это время Apple перешла на
процессоры Intel).
<b>Загрузчик (в хакинтоше)</b> - это программа, которая эмулирует EFI компьютера Mac для запуска macOS. Самые распространенные: Clover, OpenCore, Chameleon.
<b>Кексты (kexts)</b> - <b>K</b>ernel <b>EXT</b>ension - расширение ядра. Своего рода драйверы в macOS.

<h2>Для чего мне все это?</h2> Если у вас больше нет никаких сил пользоваться Windows, но по какой либо причине вы не хотите пользоваться Linux, то вы можете попробовать macOS.

<h2>Начальная подготовка. Проверка железа на совместимость. Выбор версии macOS.</h2> Итак, когда мы определились с базовыми понятиями, давайте начнем.
Для начала, нужно понять: совместимо железо с macOS или нет, и если да, то какую версию ОС установить. На самом деле, в большинстве случаев даже если железо не совместимо, установить macOS можно, в т.ч., установив патченное ядро, но ОС будет работать нестабильно (про установку на несовместимое железо, в т.ч. AMD - в конец файла).
<h3>Процессор.</h3> Поддерживаемыми процессорами можно считать те, которые были когда либо в компьютерах Apple, либо очень близки к тем => сразу же отпадают процессоры AMD. 
Для того, чтобы узнать, какие процессоры были в компьютерах Apple, можно воспользоваться программой <a href="http://mactracker.ca">Mactracker</a> Но данный вариант подходит только для владельцев техники Apple, будь то Mac (macOS 10.12+) или iPhone/iPad (iOS 12+). Для всех остальных могу предложить либо <a href="http://everymac.com/systems/apple/index-apple-specs-applespec.html">этот сайт</a> (для пользователей Windows), либо <a href="http://github.com/sudo-HackerMan/thm-mactracker">собственную программу</a> (для пользователей Linux). 
Кратко изложу здесь рекомендации по выбору процессора:
На данный момент лучше всего i3/i5/i7 (кодовые имена: Ivy Bridge (для более старых ОС), ...)
Процессоры Atom/Celeron/Pentium отпадают.
Процессоры Core Solo/Core Duo/Core 2 Duo подойдут для старых ОС, таких как 10.8 Mountain Lion, 10.9 Mavericks.
...
