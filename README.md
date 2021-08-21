Приветствую!

В этом репозитории собраны API тесты по тестированию сайта "https://petfriends1.herokuapp.com/"
В папке images находятся фотки питомцев.
В папке settings id данные.
В папке API собраны методы.
Сами тесты вы можете найти в файле test_PF1.py.
В нем присутствуют следующие тесты:
1. Тест на то, что запрос api ключа возвращает статус 200 и в тезультате содержится слово key.
2. Тест на то, что можно добавить питомца с корректными данными.
3. Тест на то, что запрос всех питомцев возвращает не пустой список.
4. Тест на то, что можно добавить питомца с неполными данными без фото (упрощенный метод).
5. Тест на то, возможность обновления фотографии питомца.
6. Тест на то, возможность обновления информации о питомце.
7. Тест на то, что можно добавить питомца с некорректными данными (имя).
8. Тест на то, что можно добавить питомца с некорректными данными (имя, тип).
9. Тест на то, что можно добавить питомца с некорректными данными (имя, тип, возраст).
10. Тест на то, что можно добавить питомца без фото.
11. Тест на то, что можно добавить питомца с большими значениями (имя, тип, возраст).
12. Тест на то, возможность удаления питомца.
13. Тест на то, что можно добавить питомца с пустыми данными, только фото (это баг).
14. Тест на неправильный ввод имени пользователя и пароля.
15. Тест на ввод некорректного строкового ключа.

Удачных тестов!
