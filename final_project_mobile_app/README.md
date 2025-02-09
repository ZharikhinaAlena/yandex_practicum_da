# Анализ поведения пользователей в мобильном приложении "Ненужные вещи"
### Описание проекта
В нашем распоряжени данные о событиях, совершенных в мобильном приложении "Ненужные вещи". В нем пользователи продают свои ненужные вещи, размещая их на доске объявлений. Заказчик исследования - продакт-менеджер, он хочет поработать над вовлечённостью пользователей и увеличить конверсию в целевое событие - просмотр контактов. За целевое действие принят просмотр контактов, так как предполагается, что в этом случае пользователь заинтересовался и совершил звонок.
### Цель проекта
Проанализировать поведение пользователей и выявить общие поведенческие сценарии. Для этого необходимо изучить, как пользователи доходят до целевого события и оценить, какие действия чаще совершают пользователи, которые просматривают контакты. В дальнейшем на основе нашего исследования будет проведена сегментация пользователей.
## Stack
- Pandas
- Matplotlib
- Numpy
- Seaborn
- Plotly
## Общий вывод
 Проанализировав поведение пользователей внутри приложения, было выделено несколько основных сценариев, приводящих к целевому действию:
- использование поисковой системы внутри приложения;
- поиск объявлений на карте;
- просмотр рекомендаций и клик на рекомендацию.
Конверсия в целевое событие в каждом из сценариев очень слабая.

Также мы проверили две статистические гипотезы. Первая гипотеза была отвергнута, конверсия в целевое действие значительно выше у пользователей, которые кликают на рекомендации, чем у тех, кому только показывают рекомендации. Вторая гипотеза, о равенстве конверсии пользователей в целевое событие из источников yandex и google, подтвердилась.

**Рекомендации**
- Требуется разобраться с низкими показателями конверсии при переходе от рекомендованных объявлений к просмотру контактов. Сделать акцент на улучшении персональных рекомендаций, пересмотреть принцип работы алгоритма подбора рекомендованных объявлений. 
- Рекомендуем рассмотреть возможность улучшения интерфейса и поработать над алгоритами поиска;
- Наличие фотографий в объявлениях увеличивает вероятность того, что пользователь дойдет до целевого действия, в связи с этим рекомендуем стимулировать пользователей выкладывать более подробные фотообзоры или исключить возможность публиковать объявление без фото.
