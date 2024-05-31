# Правильная установка ComfyUI
---
**Установка Python 3.11**

Со страницы  <a href="https://www.python.org/downloads/windows">https://www.python.org/downloads/windows</a> скачиваем дистрибутив питона версии 3.11
<p align="center">
  <img src="img/001.jpg">
</p>

---
Запускаем дистрибутив, **ОБЯЗАТЕЛЬНО** ставим администраторские привилегии и убираем галочку на пункте "Добавить в PATH"!!!

<p align="center">
  <img src="img/002.jpg">
</p>

Мы не будет добавлять путь к питону в PATH по той причине, что, как правило, одним экземпляром питона, и одной версией питона, нам ограничиться в будущем не получится!!!

Со временем возникнет необходимость установить еще одну версию питона, запустить еще один экземпляр питона, и, если у на с путь к питону помещен в PATH, то этот экземпляр питона будет найден первым и все команды, которые мы будем отдавать питону без явного указания  экземпляра питона, будут перехватываться и исполняться именно им, независимо от того, хотим мы этого или нет.

Расположение питона в PATH можно добавлять лишь в том случае, когда вы гарантированно знаете, что у вас будет единственный экземпляр питона, и одно-единственное приложение, работающее на питоне, что бывает крайне редко. Со временем вам потребуется еще что-то добавить, и наличие указателя на питона в PATH приведет к непонятным и трудно-обнаруживаемым ошибкам в работе питона!!!

Поэтому, та технология работы с питоном, которую я вам тут предложу, основана на моем личном опыте работы с несколькими вресиями и экземплярами питона, и более отвечает внутренней идеологии установки и  настройки  питона, чем просто "В Windows так проще". 

---

Устанавливаем все "галочки" так, как на этом фото.

<p align="center">
  <img src="img/003.jpg">
</p>

---

Устанавливаем все "галочки" так, как на этом фото.

<p align="center">
  <img src="img/004.jpg">
</p>

Несколько слов об именах папок с питоном - почему именно так: 

1. Придется много набивать адреса "ручками". поэтому чем короче путь, тем лучше!
2. Мы ставим **3.11** версию питона, поэтому имя папки полностью отражает номер версии.
3. Всего существуют такие версии питона: "**3.8**", "**3.9**", "**3.10**", "**3.11**", "**3.12**", "**3.13**" *(в будущем еще добавятся)* и вам надо свободно ориентироваться в номерах версий, и все время помнить номер "текущей рабочей версии питона", которая *(на "сейчас" для ComfyUI)* является "**3.11**". Для другого интерфейса она может иметь другой номер, а через какое-то время выйдет ворсия ComfyUI и для более высоких версий питона *(3.13 и выше)*.  
4. Следовательно, мы резервируем за версиями питона имена следующих папок: "**c:\p38** = версия **3.8**", "**c:\p31** = версия **3.10**", "**c:\p311** = версия **3.11**", "**c:\p312** = версия **3.12**", "**c:\p313**= версия **3.13**" и так далее.    
5. Ведя такую нумерацию в обозначении версий, вы, в процессе набора команды, УЖЕ будете "считывать" то, какой именно версии питона вы отдаете команду, что поможет избежать огромного (!!!) количества ошибок в будущем!
6. Короткий путь с номером версии намного информативнее, чем те пути, кторые предлагает Windows "по умолчанию", когда не то, что "запомнить путь к питону", а даже просто "прочитать путь к питону" будет "МногаБукаФфниАсилил". Это выводы из "опыта".
7. К тому же вы всегда будете помнить, что текущая версия питона у вас расподожен по адресу "**c:\p311\python.exe**" *(расширение EXE можно не набирать)*.

<p align="center">
  <img src="img/005.jpg">
</p>
