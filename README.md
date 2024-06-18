# Атомик Хак 2.0

## Краткое описание

<img src="https://github.com/ArturArtikov/Portfolio/blob/main/1_media/2_hackathon_projects/hackathon5.png" height=200 align="left"> 

**Кейс:** Разработка системы технической поддержки пользователей

**Задача:** Создать систему технической поддержки пользователей, дающую ответы на вопросы по предоставленной документации

**Организаторы:** Госкорпорация РОСАТОМ

**Результат:** Обученная языковая модель, способная давать ответы на запрос, в соответствии с документацией, а также способная работать без связи с сетью интернет

**Сфера применения:** Ядерная Энергетика

<br/>

## Входные данные

* ПримерДляХакатона.dt - база данных 1С, содержащая пример веб-страницы, через которую производится ответ на вопросы пользователей
* Вопросы и ответы.xlsx - база данных в excel, содержащая вопросы и ответы по ним в различных категориях, всего представлено 22368 вопросов
* Инструкции - 25 файлов с технической документацией по различным вопросам и способам их решения (используется как источник информации для обучения модели)

<br/>

## Этапы работы над проектом

1. Сбор всех полученных данных
2. Обработка данных из PDF-файлов с помощью PDFMiner
3. Сохранение обработанных данных в виде файлов .csv
4. Очистка текстовых данных от неверных и ненужных символов, огрешностей в тексте
5. Инициализация языковой модели с помощью библиотек PyTorch, Transformers, Accelerate
6. Создание промптов, описывающих работу модели
7. Обучение модели на 1 датасете и тестирование предсказаний
8. Доработка модели с учетом изменения промпта, а также добавление дополнительных библиотек - Langchain, Optium, Peft
9. Настройка модели на улавливание контекста вопроса
10. Обучение модели на поиск ответа в полученных данных и формировании ответа на основе данных документации
11. Дополнительное тестирование модели
12. Дообучение модели на оставшихся 24 файлах данных
13. Проверка работоспособности модели при ответах на вопросы из разных видов документации
14. Корректировка и финальная настройка модели
15. Создание презентации по проекту
16. Создание и заполнение репозитория по проекту
17. Защита проекта на питч-сессии

<br/>

## Сроки и результаты

**Сроки:** 14.06-16.06.2024

**Результат:** Обученная языковая модель, способная давать ответы на запрос, в соответствии с документацией

**Возможные улучшения:** Добавление регистрации пользователя для определения дополнительных промптов конкретного пользователя (уровни допуска); добавление Frontend-части для более удобной, с визуальной точки зрения, отправки запроса и получения ответа

**Презентацию решения** можно найти по [ссылке]()

<br/>

## Командный состав

Команда: __*Netrunners*__

Список участников команды:

* [Надежда Агафонова](https://t.me/LanderWine): Капитан | Product Manager
* [Карим Галлямов](https://t.me/kgall739): ML-Engineer
* [Артур Артиков](https://t.me/ArturArtikov): Data Scientist
* [Степан Золин](https://t.me/DrHeogg): Data Scientist
* [Дмитрий Фалеев](https://t.me/ioslik): Product Analyst

<br/>

## Используемый стек и технологии

![Google Colaboratory](https://img.shields.io/badge/Google%20Colaboratory-ffffff.svg?style=for-the-badge&logo=google-colab&logoColor=orange)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![PDFMiner](https://img.shields.io/badge/PDFMiner-%23fb5252.svg?style=for-the-badge)
![Transformers](https://img.shields.io/badge/Transformers-%23f0b60c.svg?style=for-the-badge)
![Accelerate](https://img.shields.io/badge/Accelerate-%23faec3e.svg?style=for-the-badge)
![Sentencepiece](https://img.shields.io/badge/Sentencepiece-%2382dff9.svg?style=for-the-badge&logo=Langchain)
![Optimum](https://img.shields.io/badge/Optimum-%23cac5c1.svg?style=for-the-badge&logo=Langchain)
![Peft](https://img.shields.io/badge/Peft-%239f6df9.svg?style=for-the-badge&logo=Langchain)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Langchain](https://img.shields.io/badge/Langchain-%23eca574.svg?style=for-the-badge&logo=Langchain)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)
![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)
