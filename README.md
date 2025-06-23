# qa_python

Реализованные тесты
Ниже перечислены тесты, покрывающие основную функциональность класса BooksCollector:

📚 Добавление книг
test_add_new_book_add_two_books — проверяет добавление двух разных книг.

test_add_new_book_does_not_add_duplicate — проверяет, что дубликаты не добавляются.

test_add_new_book_does_not_add_if_name_too_long — проверяет, что книга с названием длиной более 40 символов не добавляется.

test_add_new_book_with_valid_names (параметризованный) — проверяет добавление книг с корректными названиями разных типов.

🎭 Жанры
test_set_book_genre_sets_valid_genre — проверяет установку допустимого жанра книге.

test_set_book_genre_does_not_set_invalid_genre — проверяет, что недопустимый жанр не устанавливается.

test_get_book_genre_returns_correct_value — проверяет получение жанра книги.

test_get_books_with_specific_genre_returns_only_matching — проверяет фильтрацию книг по определённому жанру.

test_get_books_genre_returns_books_dict — проверяет, что возвращается корректный словарь книг с жанрами.

👶 Книги для детей
test_get_books_for_children_returns_only_safe_books — проверяет, что метод возвращает только книги без возрастных ограничений.

⭐ Избранное
test_add_book_in_favorites_adds_once — проверяет добавление книги в избранное.

test_add_book_in_favorites_does_not_add_twice — проверяет, что одна и та же книга не добавляется в избранное повторно.

test_add_book_in_favorites_does_not_add_if_book_unknown — проверяет, что в избранное нельзя добавить неизвестную книгу.

test_delete_book_from_favorites_removes_book — проверяет удаление книги из избранного.

test_get_list_of_favorites_books_returns_correct_list — проверяет, что список избранного возвращается корректно.

