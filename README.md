CrptApi

Необходимо реализовать на языке Java (можно использовать 17 версию) класс для работы с API Честного знака. Класс должен быть thread-safe и поддерживать ограничение на количество запросов к API. Ограничение указывается в конструкторе в виде количества запросов в определенный интервал времени. Например:
public CrptApi(TimeUnit timeUnit, int requestLimit)
timeUnit – указывает промежуток времени – секунда, минута и пр.
requestLimit – положительное значение, которое определяет максимальное количество запросов в этом промежутке времени.
