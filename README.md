# Семинары по машинному обучению для бакалавров 3 курса кафедры ММП и магистров 1 курса кафедр ИИТ и МФ факультета ВМК МГУ, весенний семестр 2020/2021
В репозитории находятся материалы и домашние задания по семинарам "ММРО 2020/2021"

<p align="center">
<img src="http://funzoo.ru/uploads/posts/2009-11/1258648863_tn.jpg" height=200pt> <img src="https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/trash/kernel_trick.jpg" height=200pt>
</p>

**Курс сдается через систему [anytask](https://anytask.org/course/807)**

На семинары и работу ассистентов можно оставить отзыв: [[анонимно без регистрации и смс](https://docs.google.com/forms/d/e/1FAIpQLSeW89-GCnceWDvd439vqZBY69-oSUzo-UWtL5aq-fCnOWOzow/viewform)]

**Полезные ссылки:**

* Материалы прошлых лет:
  - [Раз](https://github.com/esokolov/ml-course-msu)
  - [Два](https://github.com/esokolov/ml-course-hse)
* [Курс лекций по ММРО](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
* [Курс Практикума на ЭВМ, осень](https://github.com/mmp-practicum-team/mmp_practicum_fall_2020)
* [Курс ММРО 19/20, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2019)
* [Курс ММРО 20/21, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020)

## Правила выставления оценок

Общая оценка выставляется по следующей формуле:
![](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/trash/formula.png)
, где 

* Check --- 5 * <сумма баллов за проверочные> / <суммарный макс балл за проверочные>
* Labs --- min(5, 5 * <сумма баллов за лабораторные + конкурсы + теор. дз.> / <суммарный макс балл за (лабораторные + теор.дз + конкурс) (без бонусов)>
* Exam --- оценка за экзамен, до 5 баллов

Причем
* Для общей оценки 5 необходимо сдать **все (4)** _лабораторные работы и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за эказамен не меньше 4;
* Для общей оценки 4 необходимо сдать **не менее 3-х** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* Для общей оценки 3 необходимо сдать **не менее 2-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* floor --- округление дробного числа до ближайшего целого вниз.

**Обратите внимание,** что округление общей оценки (и только ее) производится вверх.

## Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 18 февраля  | Семинар 1  | <ul><li>Имплементации бустинга</li></ul> | <ul><li>[Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/sem10-gbm%20(3).pdf)</li><li>[Ноутбук, базовый](https://github.com/esokolov/ml-course-hse/blob/master/2019-fall/seminars/sem09-gbm-part2.ipynb)</li><li>[Визуализация](http://arogozhnikov.github.io/2016/06/24/gradient_boosting_explained.html)</li><li>[Ноутбук, продвинутый](https://github.com/esokolov/ml-course-hse/blob/master/2019-fall/seminars/sem10-gbm.ipynb)</li><li>[Семинар к ODT](https://github.com/esokolov/ml-course-hse/blob/master/2019-fall/seminars/sem09-gbm-part1.pdf)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 25 февраля  | Семинар 2  | <ul><li>Решение задач на байесовский подход</li></ul> | <ul><li>[Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/Sem13_bayes.pdf)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 4 марта  | Семинар 3  | <ul><li>Аппроксимация ядер</li><li>Ядра для строк</li></ul> | <ul><li>[Семинар по аппроксимации](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/lecture-notes/lecture14-kernels.pdf)</li><li>[Семинар по ядрам для строк](https://github.com/esokolov/ml-course-hse/blob/master/2017-spring/seminars/sem14-kernels.pdf)</li></ul> | [Дз на аппроксимацию ядер](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/homework-practice/homework-practice-08-random-features.ipynb) |
| 11 марта  | Семинар 4  | <ul><li>Вывод линейного дискриминанта Фишера</li><li>Ядровой Дискриминант Фишера</li></ul> | <ul><li>[Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/sem15-fld.pdf)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 18 марта  | Семинар 5  | <ul><li>EM-алгоритм</li></ul> | <ul><li>[Семинар по EM-алгоритму](https://github.com/esokolov/ml-course-hse/blob/master/2019-spring/seminars/sem15-em.pdf)</li></ul> | [ДЗ на EM](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/tree/main/homework-practice/homework-practice-09-em) |
| 25 марта  | Семинар 6  | <ul><li>EM-алгоритм: продолжение</li></ul> | <ul><li>[Семинар раз](https://github.com/esokolov/ml-course-hse/blob/master/2019-spring/seminars/sem15-em.pdf)</li><li>[Семинар 2](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem15-em.pdf)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 8 апреля  | Семинар 7  | <ul><li>Multilabeling</li></ul> | <ul><li>[Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2018-spring/seminars/sem19-multilabel.pdf)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 15 апреля  | Семинар 8  | <ul><li>Кластеризация</li><li>Extrinsic метрики качества</li><li>Cпектральная кластеризация</li></ul> | <ul><li>[Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/lecture17-clusterization.pdf)</li></ul> | [ДЗ на кластеризацию](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/homework-practice/homework-practice-10-unsupervised.ipynb) |
| 22 апреля  | Семинар 9  | <ul><li>Ранжирование</li></ul> | <ul><li>[Семинар раз](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/lecture24-ranking.pdf)</li><li>[Семинар два](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/sem23-ranking.pdf)</li></ul> | ¯\\\_(ツ)\_/¯  |
| 29 апреля  | Семинар 10  | <ul><li>Обучение метрик</li></ul> | <ul><li>[Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/sem20-knn.pdf)</li></ul> | [ДЗ на обучение метрик и несбалансированные данные](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/homework-practice/homework-practice-11-metric-learning-emb/homework-practice-11-metric-learning-imb.ipynb) |
| 6 мая  | Семинар 11  | <ul><li>Рек. системы</li></ul> | <ul><li>См. запись семинара</li></ul> |  ¯\\\_(ツ)\_/¯  |
| 13 мая  | Семинар 12  | <ul><li>ALS, HALS</li><li>Факторизационные машины</li><li>Интерпретируемость моделей</li></ul> | <ul><li>[Семинар по рек. системам](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/sem24-recommendations.pdf)</li><li>[Семинар по интерпретируемости](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/sem25-interpreting.pdf)</li></ul> |  ¯\\\_(ツ)\_/¯  |
