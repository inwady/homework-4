# Project TP, ok.ru tests

checklist:
1. При нажатии на кнопку "Музыка" появляется панель с необходимыми компонентами.
2. Предлагает проиграть музыку. Клик кнопки Play. Меняется контент "старт" и "стоп".
3. Возникает Push Up, если нажать на знак вопроса. Появляется форма с просьбой задать вопрос.
4. Нажимаем на ссылку в разделе "Популярное", переходим в группу. Нажимаем добавить в Альбом. Появляется "Добавлен".
5. Нажимаем создать сборник. Появляется форма создания.
6. Создаем сборник, проверяем на добавление.
7. В сборнике нажимаем "Загрузить музыку". Музыка должна загрузиться.
8. Проверка скролла звука при нажатии на кнопку громкости.
9. В разделе моя музыка есть кнопка редактировать.
10. Нажимаем кнопку крестик. Закрывается вкладка музыки.

## Run
```
# default ./config/okdev.yaml
python run_tests.py [-c config]
```