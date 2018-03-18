Приложение для восстановления изображения с использованием нейройной сети
====
# Идея
У изображения закрашиваются пиксели определенным цветом. Затем, с помощью **самоорганизующейся кaрты Кoхонена** строится карта, в ней содержится информация о том, какие цвета располагаются рядом, а какие нет. Потом, на основе этой карты, происходит заполнение _испорченных_ пикселей

# Как пользоваться:
 1. Oткрыть поврежденное изображение
 2. Создать карту на его основе
 3. Открыть получившуюся (либо сохраненную ранее) карту
 4. Восстановить
 5. Если требуется, сохранить полученное изображение

p.s. есть возможность предварительно _испортить_ файл, с указаннием цвета _плохих_ пикселей и процента повреждения 

# Pitfalls:  
Не рекомендуется выбирать большое значение размера блока или количество нейронов - приложение будет работать очень долго
