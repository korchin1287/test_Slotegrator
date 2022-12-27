# test_Slotegrator

Перед запуском убедится, что в сценарии правильно прописан путь до файла users.csv
При необходимости прописать его в CSV Data Set Config

Переместить файл Test_API_Slotegrator.jmx и users.csv в \bin 

Запуск в non-GUI следующей командой:

jmeter -n -t Test_API_Slotegrator.jmx -l report_Slotegrator.csv