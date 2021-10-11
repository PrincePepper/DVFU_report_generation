# Автоматическая генерация отчета в LaTex ✉
Сделал более менее нормальную генерацию титульного листа Дальневосточного федерального унивеситета
### Вот пример:
![titul_page.jpg](https://github.com/PrincePepper/DVFU_report_generation/blob/main/titul_page.jpg)
### А вот и описание параметров:
```
\fefupage{Середа С.}{Б9119-01.03.02систпро}{к лабораторной работе №1}{т}{Вычислительная математика}
```
1. ФИО студента;
2. Номер группы;
3. Какой вид раьоты;
4. Студент или Студентка, __следует писать или «т» или «ка»__
5. Предмет

Чтобы вставить свою подпись досточно заменить файл в папке `pictures\signature.png` на свой с таким же именем и форматом

### P.S.
Также присутсвует команды:
- вставка картинки с описанием
- создание заголовка
- создание подзаголовка
- готовый листиг для кода, чтобы его вставить то вот так следует это делать:
```
\begin{lstlisting}[language=python, caption=описание]
твой код	
\end{lstlisting}
```
## Планируется сделать сайт, чтобы сразу получать готовый pdf с титульником
***The project was released for my University course***

##### My contacts:
1. [Telegram](https://tgmsg.ru/princepepper)
2. [Вконтакте](https://vk.com/princepepper)
3. [Instargam](https://www.instagram.com/prince_pepper_official/?hl=ru)
4. <sereda.wk@gmail.com>
