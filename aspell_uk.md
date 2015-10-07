# Вступ #

Це - проект створення відкритих словників для перевірки орфографії української мови.
Ці словники можуть використовуватися в декількох відкритих системах перевірки орфографії, наведених нижче.

# Новини #

[Новини проекту словників орфографії](spelling_uk_news.md)

# Опис #

Орфографічні словники мають декілька форматів, що можуть використовуватися в наступних двигунах перевірки орфографії:
  * hunspell
  * myspell
  * aspell (>=0.60)
  * ispell

# Ліцензії #

Словники перевірки орфографії spell-uk розповсюджуються на умовах ліцензій GPL, LGPL або MPL 1.1.

# Звантаження #

Сторінка проекту для розробників та звантажень знаходиться на http://sourceforge.net/projects/ispell-uk. Там знаходяться CVS і інша інформація про проект.

## Архіви (tgz та zip) та пакунки (rpm та src.rpm). ##

http://sourceforge.net/projects/ispell-uk/

## Доступ через CVS. ##

cvs -d:pserver:anonymous@cvs.sourceforge.net:/cvsroot/ispell-uk login
cvs -z3 -d:pserver:anonymous@cvs.sourceforge.net:/cvsroot/ispell-uk co -P aspell-uk

**ВВАЖАЙТЕ**: підкаталог має назву **aspell-uk**, а не **ispell-uk**! В підкаталозі ispell-uk знаходиться стара версія ispell-uk, яку, скоріш за все, буде заморожено.


## Встановлення з сирцевого коду. ##

  * Відредагувати файл encodins.inc відповідно до необхідних кодувань
  * make install-aspell
  * make install-myspell
  * make install-ispell

# Зворотний зв'язок. #

Коментарі та побажання можна надсилати на адресу ispell-uk-develop at lists.sourceforge.net


# Документація та посилання #

## hunspell ##
[Домашня сторінка hunspell](http://hunspell.sourceforge.net/)
Hunspell побудовано на основі коду myspell і це на сьогодні найактивніший і найгнучкіший двигун перевірки правопису. hunspell працює зі словниками у форматі myspell але також має свої розширення.

## myspell ##

OpenOffice.org:
[Ручне встановлення словників орфографії OpenOffice.org](http://lingucomponent.openoffice.org/manual_instal.html)
[Домівка словників орфографії OpenOffice.org](http://lingucomponent.openoffice.org/dictionary.html)

Mozilla:
[Сторінка встановлення словників для Mozilla](http://spellchecker.mozdev.org/installation.html)

## ALTLinux hyphenator ##
[Перенесення слів в OpenOffice.org](http://lingucomponent.openoffice.org/hyphenator.html)

## aspell ##
[Домашня сторінка aspell](http://aspell.sourceforge.net/)
aspell є нащадком ispell і широко використовується у вільних програмних засобах, але, схоже, hunspell перебирає роль лідера.

## ispell ##
[Домашня сторінка ispell](http://lasr.cs.ucla.edu/geoff/ispell.html)
ispell - найстаріший з двигунів перевірки правопису, фактично він зараз використовується лише на старих системах, де неможливо скомпілювати нові двигуни, або на які їх не було портовано.