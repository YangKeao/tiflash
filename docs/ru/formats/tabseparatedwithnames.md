# TabSeparatedWithNames

Отличается от формата `TabSeparated` тем, что в первой строке пишутся имена столбцов.
При парсинге, первая строка полностью игнорируется: вы не можете использовать имена столбцов, чтобы указать их порядок расположения, или чтобы проверить их корректность.
(Поддержка обработки заголовка при парсинге может быть добавлена в будущем.)

Этот формат также доступен под именем `TSVWithNames`.