# Подготовка датасета Flowers Recognition

## 1. Источник данных
В проекте используется датасет **Flowers Recognition Dataset** с платформы Kaggle.
Ссылка на датасет: https://www.kaggle.com/datasets/alxmamaev/flowers-recognition
Идентификатор датасета: alxmamaev/flowers-recognition
Автор: Alexander Mamaev  
Состав: содержит изображения 5 классов цветов:
- daisy
- dandelion
- rose
- sunflower
- tulip

## 2. Загрузка датасета
Необходимо скачать датасет **alxmamaev/flowers-recognition** любым удобным способом
https://www.kaggle.com/datasets/alxmamaev/flowers-recognition

## 3. Размещение в проекте
В корне проекта должна быть папка `data`.

Скачанный архив необходимо **распаковать в папку `data`** так,  
чтобы **подпапки классов находились непосредственно в её корне**.

### Правильная структура:

data/
├─ daisy/
├─ dandelion/
├─ rose/
├─ sunflower/
├─ tulip/

Если после распаковки появился дополнительный каталог или только каталог `flowers`,
его содержимое нужно переместить в папку `data`.

## 4. Требования к данным

- Формат изображений: `.jpg` / `.jpeg`
- Цветовая модель: RGB
- Размер изображений может быть произвольным  
  (приведение к единому размеру выполняется в коде)