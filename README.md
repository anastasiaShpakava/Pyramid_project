Необходимо разработать приложение и тесты к нему согласно
требованиям, приведенным ниже. В приложении должна быть реализована
функциональность, определенная индивидуальным заданием.
Требования
 Все созданные объекты геометрических фигур сохранить в объекте-репозитории. Паттерн
Repository.
 Площади, Объемы, Периметры фигур должны храниться в объекте класса-Warehouse.
 Любое изменение параметра фигуры должно вызывать пересчет соответствующих значений
в классе- Warehouse.
Для решения данной задачи использовать паттерны Observer (можно использовать Flow
API) и Singleton (потокобезопасные варианты использовать запрещено).
 Разработать методы по добавлению, удалению объектов репозитория.
 Разработать спецификации по поиску объектов и групп объектов в репозитории. По ID, по
имени, по координатам (например: найти все объекты точки которых находятся в первом
квадранте, найти все объекты площади поверхности (объемы, периметры) которых
заключены в заданный диапазон, найти объекты находящиеся на расстоянии в заданном
диапазоне от начала координат)
 Разработать методы сортировки наборов объектов по ID, по имени, по координатам Х первой
точки, по координатам Y первой точки и т д. Использовать интерфейс Comparator

