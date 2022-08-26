# [Межгалактический хакатон 2022](https://new.skillfactory.ru/hackaton)
## Команда Datamind (misis-2)
<!- vim-markdown-toc Redcarpet ->
*[Участники команды](#участники_команды)
*[Кейс](#название_кейса)
*[Постановка задачи](#формулировка_задачи)
*[Описание файлов](#структура_репозитория)
*[Выводы](#выводы)
<!- vim-markdown-toc Redcarpet ->
## Участники команды:
### Максим Самойлов, Вильдан Харисов, [Сергей Тотьмянин](https://github.com/ZergSS), Иван Галков, [Алексей Тяжев](https://github.com/rengoft)

## Кейс: "Предсказание бойца-победителя UFC."

Перед вами стоит задача создать модель, предсказывающую победителя на основе исторических статистических данных о боях лиги UFC. Успешную модель можно будет использовать, делая букмекерские ставки. Но для начала необходимо убедиться, что у вас правильно выстроена стратегия валидации модели - чтобы потом не сесть в просак.
Участникам необходимо создать модель, которая будет предсказывать победителя в боях UFC. Для создания успешной модели необходима определенная доля креативности - как сгенерировать информативные признаки из имеющихся данных? Как правильно выстроить стратегию валидации модели? Каким образом агрегировать данные в табличный формат, пригодный для использования в обучении модели?


## Описание файлов
Base_data_prep.ipynb - подготовка данных (базовый расчет)<br>
Base_data_prep_4.ipynb - подготовка данных (финал)<br>
Base_modeling.ipynb - получение базовой модели<br>
Base_modeling_4.ipynb - получение финальной модели<br>
data.csv - подготовленный датасет<br>
processed_data2.pkl - сериализованный data.csv в формате pkl
