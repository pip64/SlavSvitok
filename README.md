# СлавСвиток
Это транслируемый в JS язык программирования, который был придуман для взлома базы ящерской.

Скоро выйдет.

# Пример кода
Данный код взрывает базу ящерскую.
```
деревушка БазаЯщерская впереди
    построение (название) впереди
        лично название = название
        лично взорвана = неверно
    конец

    получить_название () впереди
        воздать лично название
    конец

    взорвать () впереди
        ячеечка названиебазы = лично запуск получить_название

        условно !лично взорвана впереди
            лично взорвана = верно

            свиточек.вписать "Ну, держитесь ящеры! *Ящерская база", названиебазы, "взорвана*"
        конец иначе впереди
            свиточек.вписать "База ящерская", названиебазы, "уже взорвана!"
        конец
    конец
конец

ячеечка ящерскаябаза = построить БазаЯщерская "АнтиПерунская Ящерская База"

запуск ящерскаябаза.взорвать
```
