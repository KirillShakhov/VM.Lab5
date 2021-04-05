# VM.Labs

###Лабораторные работы по Вычислительной математике.

[![GitHub stars][stars-shield]][stars-url]
[![GitHub issues][issues-shield]][issues-url]
[![GitHub][license-shield]][license-url]
![GitHub repo size](https://img.shields.io/github/repo-size/KirillShakhov/VM.Labs)
![GitHub last commit](https://img.shields.io/github/last-commit/KirillShakhov/VM.Labs)
[![Java CI with Maven](https://github.com/KirillShakhov/VM.Labs/actions/workflows/maven.yml/badge.svg)](https://github.com/KirillShakhov/VM.Labs/actions/workflows/maven.yml)

####Лабораторная работа 1. «Решение системы линейных алгебраических уравнений СЛАУ»

Метод простых итераций

* В программе численный метод должен быть реализован в виде отдельной подпрограммы или класса, в который исходные данные передаются в качестве параметров, выходные - тоже (либо возвращаемое значение).
* Размерность матрицы n<=20 (задается из файла или с клавиатуры - по выбору конечного пользователя).
* Должна быть реализована возможность ввода коэффициентов матрицы,  как с клавиатуры, так и из файла (по выбору конечного пользователя).

Обязательно: Тестовые данные на матрице большого размера (5x5 / 6x6...) + в отчёт с решением.

Для итерационных методов должно быть реализовано:
* Точность задается с клавиатуры/файла
* Проверка диагонального преобладания (в случае, если диагональное преобладание в исходной  матрице отсутствует, сделать перестановку строк/столбцов до тех пор, пока преобладание не будет достигнуто). В случае невозможности достижения диагонального преобладания - выводить соответствующее сообщение.
* Вывод вектора неизвестных:
* Вывод количества итераций, за которое было найдено решение
* Вывод вектора погрешностей:

####ЛР2 - «Решение системы линейных алгебраических уравнений СЛАУ» 
Вариант: 2aб (2 - метод простых итераций, a - метод деления пополам, б - метод хорд)

####ЛР3 - «Численное интегрирование»
Вариант: 2 (Метод трапеций)


[stars-shield]: https://img.shields.io/github/stars/KirillShakhov/VM.Labs?style=social
[stars-url]: https://github.com/KirillShakhov/VM.Labs/stargazers
[issues-shield]: https://img.shields.io/github/issues/KirillShakhov/VM.Labs
[issues-url]: https://github.com/KirillShakhov/VM.Labs/issues
[license-shield]: https://img.shields.io/github/license/KirillShakhov/VM.Labs
[license-url]: https://github.com/KirillShakhov/VM.Labs/blob/master/LICENSE
