# Заключение

Использование методов "ToGo", "Fly" и "Swim" в основном классе некоректно, т.к. приходится выполнять дополнительные
действия по переопределению отсутствующих действий у животного, что при массовом добавлении класа может спровоцировать ошибки человеческого фактора и у классов наследников появятся действия которые не должны присутствовать у него.

Действия описанные в родительском классе должны быть максимально абстрактнымии поумолчанию должны присутствовать у наследованных классов.
