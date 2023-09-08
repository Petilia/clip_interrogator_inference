В репозитории реализован инференс модели CLIP Interrogator.

Для сборки docker-образа необходимо выполнить:

```bash
./docker/build.sh
```

Для запуска docker-контейнера необходимо выполнить:

```bash
./docker/start.sh
```
В [./src/inference_clip.ipynb](./src/inference_clip.ipynb) лежит код для инференса CLIP Interrogator на выбранных фотографиях для 10 отелей. Сам же датасет необходимо скачать по ссылке и распоковать в ./src. (Датасет - https://drive.google.com/file/d/1nxC1gJ56jRKnc-I8u8hAcBpEuYYGyLbJ/view?usp=drive_link).

В [./src/train_models.ipynb](./src/train_models.ipynb) лежит код для лемматизации/кластеризации полученных аннотаций.
