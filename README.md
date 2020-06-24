# test_sheep
#Дано <br>
Есть 4 загона в которых вырастает живность  <br>
![alt text](https://github.com/[enderoasis]/[test_sheep]/blob/[master]/imgt.JPG?raw=true)

Тестовое задание:<br>
•	Написать API с использованием RESTful<br>
•	Работу на FrontEnd-e с написанным API<br>
•	Проектирование бд<br>

Правила:
•	4 загона для овечек
•	изначальное количество овечек 10 расположены рандомно по загонам <br>
•	1 день длится 10 секунд
•	каждый день в одном из загонов где больше 1 овечки появляется ещё одна овечка<br>
•	каждый 10 день одну любую овечку забирают(сами знаете куда)<br>
•	если в загоне осталась одна овечка то берём загон где больше всего овечек и пересаживаем одну из них к одинокой овечке<br>
•	загоны никогда не должны быть пусты<br>
•	должен вестись счёт дней, который не обнуляется при обновлении страницы<br>
•	должна быть история действий происходящих в загонах(выводить никуда не надо)<br>

Плюсом будем:<br>
•	Страничка с отчётом за каждый день или период дней по запросу. Где мы должны видеть:<br>
o	общее количество овечек <br>
o	количество убитых овечек <br>
o	количество живых овечек<br>
o	номер самого населённого загона<br>
o	номер самого менее населённого загона<br>
•	Написать консоль для команд:<br>
o	добавить овечку в загон<br>
o	удалить овечку из загона<br>
o	переместить овечку из загона в другой загон<br>

Примечание:<br>
Для решения данной задачи предлагается использовать следующие технологии\языки\фреймворки\библиотеки:<br>
•	BackEnd:<br>
o	Laravel последней стабильной версии<br>
o	MySQL или PostgreSQL или SQLite<br>
•	FrontEnd:<br>
o	Vue JS, Bootstrap или любой другой<br>
