# MAI IT-project
Предварительно необходимо установить библиотеку ultralytics
```
pip install ultralytics
```
### Команда для запуска 
```
yolo task=detect mode=predict model=weights.pt source=<путь к папке>
```
model - путь к файлу weights.pt\
source - папка с изображениями для обработки\
результат будет доступен в папке runs/detect/predict

### Пояснение к файлам
weights.pt - веса полученные при обучении на протяжении 50 эпох\
weights2.pt - веса полученные при обучении на протяжении 100 эпох

