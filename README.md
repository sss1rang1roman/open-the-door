## Тип моего проекта:
> Eco bot
Персональный бот помощник  в вопросах экологии. Получайте информацию о загрязнении окружающей среды, глобальном потеплении, узнавайте о способах уменьшить свой экологический след и проверяйте свои знания!

## Библиотеки, которые я буду использовать
-   import telebot
    from telebot.types import Message
    import random
-   from flask import Flask, redirect, url_for, session, request, render_template
    from random import randint, shuffle
    from db_scripts import get_question_after, get_quizes, cheack_answer
    import os
    import sqlite3
## Референсы, которые мне пригодятся
- https://ru.wikipedia.org/wiki/Глобальное_потепление
- https://thecode.media/baza-po-vyorstke-samye-osnovy-css/

## Гайды-статьи, где есть полезная для меня информация
Короткий комментарий, чтобы понимать про что статья ... [слово на котором будет ссылка](https://ru.wikipedia.org/wiki/Глобальное_потепление)