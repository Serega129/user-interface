user_interface — это модуль, который отвечает только за общение с пользователем через консоль.

функции:
show_main_menu()
get_task_input()
show_message(text, level="info")

описание функций: 
show_main_menu()
Показывает главное меню и ждёт выбора пользователя.

get_task_input()
Запрашивает у пользователя данные для новой задачи.

show_message(text, level="info")
Показывает сообщение с иконкой в зависимости от уровня.

параметры:
show_main_menu()
-
get_task_input()
-
show_message(text, level="info")
text — текст сообщения
level — тип: "info", "success", "warning", "error"

формат возвращаемых данных: 
show_main_menu()
Строку с командой.

get_task_input()
Словарь с введёнными данными.

show_message(text, level="info")
None

примеры использования:
show_main_menu()
choice = show_main_menu()

get_task_input()
data = get_task_input()

show_message(text, level="info")
show_message("Готово!", "success")
