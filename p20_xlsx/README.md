# Файлы Excel для проверки программы "Оценка стоимости квартир"

Список ЖК для гарантий: 192 строки, всё строящееся жильё. В файлах для проверки в каждой строке типовая квартира: 2 комнаты, 60 м², средний этаж, год 2027.

Чтобы скачать файл, нажмите на его название, затем на кнопку скачивания справа над файлом (Download raw file).

- [complexes_kz_batch_template.xlsx](complexes_kz_batch_template.xlsx) - проверка с координатами: широта и долгота заполнены (в 4 строках координат нет, их программа ищет по адресу).
- [complexes_kz_template_addresses_193.xlsx](complexes_kz_template_addresses_193.xlsx) - проверка без координат: только адрес, программа ищет точку по адресу (нужен интернет). Чтобы оценить все строки, поставьте галочку "Строящееся жильё".
- [complexes_kz_rows_1_193.xlsx](complexes_kz_rows_1_193.xlsx) - исходный список ЖК (строки 1-193, столбцы A-H).
- [complexes_kz_rows_1_193_with_price.xlsx](complexes_kz_rows_1_193_with_price.xlsx) - исходный список и оценка: цена квартиры (2 комнаты, 60 м²) и цена за 1 м².
- [complexes_kz_geocoded.xlsx](complexes_kz_geocoded.xlsx) - список ЖК с координатами и их проверкой.
- [complexes_kz_predictions.xlsx](complexes_kz_predictions.xlsx) - полный ответ оценки по файлу с координатами (цена, цена за м², интервал, предупреждения).
- [complexes_kz_all_xlsx_2026-11-20.zip](complexes_kz_all_xlsx_2026-11-20.zip) - все файлы Excel одним архивом.

Программа для Windows и инструкция к ней: [последняя версия](https://github.com/gulikz/soft/releases/latest).
