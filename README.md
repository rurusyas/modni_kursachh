# Synthetic sample generation by large language models in the context of cross-country surveys.

Сейчас в проекте лежат папки 
1) appendices (подробности статьи "Synthetic Replacements for Human Survey Data")
2) questions (массивы с социально демографическими характеристиками респондентов + 2 массива с поясняшками)
3) questions_new (отдельная папка q с переведенными социально демографическими характеристиками (тут же лежит WVS demo на 5 тысяч строк), questionnaire gender short + 2 массива с переведенными поясняшками)
4) WVS Wave 7 (все содержимое изначального zip-файла кроме ответов респондентов)
5) pilot_results (результаты пилотного запуска)
6) gpt data processing (код для: перевода всех вопросов + процесс сбора промтов в единое поле + ресет индексов + пилотный и основной запуски)
7) instruction_user (таблица с языком интервью и собранными воедино Q, instr_science и insrt_ethical)


