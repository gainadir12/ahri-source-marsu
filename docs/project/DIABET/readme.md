# Diabet
____
## Цель
____
> Повысить точность предсказания наличия у пациента диабета
на основе определенных диагностических измерений.
## Задачи
____
1. - [ ] анализ существующих решений.
2. - [ ] сбор данных и их обновление.
3. - [ ] обучение и оценка моделей на исходном датасете.
4. - [ ] выбор двух моделей с наибольшим значением точности.
5. - [ ] оценка качества и скорости работы модели на новых данных путем A / B тестирования.
6. - [ ] выбор и развертывание наилучшей модели.
## [Датасет](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset?select=diabetes.csv)
____
![Датасет](https://github.com/gainadir12/ahri-source-marsu/blob/master/docs/project/DIABET/img/dataset-cover.jpg)
## Целесообразность
____
Этот набор данных был получен из Национального института диабета и заболеваний пищеварительной системы и почек. Заболевания. Цель набора данных заключается в диагностическом прогнозировании наличия у пациента диабета,
на основе определенных диагностических измерений, включенных в набор данных. Было наложено несколько ограничений
на выбор этих экземпляров из более крупной базы данных. В частности, все пациенты здесь - женщины
в возрасте не менее 21 года из племени индейцев Пима.2
Из набора данных в файле (.csv) мы можем найти несколько переменных, некоторые из которых являются независимыми
(несколько медицинских предикторных переменных) и только одну целевую зависимую переменную (результат).

Переведено с помощью www.DeepL.com/Translator (бесплатная версия)
[Обзор датасета](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset?select=diabetes.csv)

Можно посмотреть на пример гистограммы интенсивности. Обратите внимание
разрыв между интенсивностью около 0 (передний план) и
255 (фон)<br>
![гистограммы интенсивности](./img/Fig2.png)

Если взглянуть на символы на изображениях CAPTCHA, можно заметить, что:

* используются только 19 символов 2,3,4,5,6,7,8 и b,c,d,e,f,g,m,n,p,w,x,y
* частота каждого символа примерно одинакова, за одним исключением: n используется в два раза чаще, чем другие символы.<br>
![Частота слов](./img/__results___9_0.png)

Эти данные можно применить для машинного обучения нейросети распознование симвлов 

____
### Component diagram

![Component diagram](./img/Component_diagram.png)

### Activity diagram

![Activity diagram](./img/Activity_diagram.png)