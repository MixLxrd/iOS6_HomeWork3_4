# iOS6_HomeWork3_4
Верстка экранов для iOS. Auto Layout

### Основное задание

1. В Main.storyboard на экране ProfileViewController создайте UIView, задайте положение и размер с помощью Auto Layout:
- Слева и справа нулевые отступы;
- Сверху привязать к Safe Area;
- Высоту задать равной 220.

Удалить программное создание и изменение размера `profileHeaderView`.

2. Привязать к классу ProfileHeaderView, добавить всё subviews в storyboard и привязать с помощью IBOutlet:
- avatarImageView
- fullNameLabel
- statusLabel
- statusTextField
- setStatusButton

Удалить код в методе `layoutSubviews()` и сделать всю верстку с помощью Auto Layout в storyboard. Конфигурацию отображения всех subviews (изменение layer, backgroundColor и т.д.) оставить в коде.

3. Программно добавить новую UIButton, изменить title и задать следующие правила отображения с помощью кода:
- Слева и справа нулевые отступы;
- Снизу привязать к Safe Area.

### Дополнительное задание ***
1. На экране FeedViewController создайте UIStackView с вертикальным расположением элементов в storyboard или программно. Удалите кнопку для открытия поста, которая была добавлена ранее.
2. Расположите его по центру экрана.
2. Добавьте две UIButton в UIStackView.
3. Задайте spacing, равный 10.
4. Добавьте открытие экрана PostViewController на нажатие каждой кнопки.

Заархивируйте готовую работу в .zip-файл и прикрепите в личном кабинете.
