# Вакансия: PHP-разработчик в Комитет

Мы ищем php middle разработчика для работы над бэкендом [наших](https://cmtt.ru) изданий. Можно работать как удалённо, так и в нашем офисе на Лиговском проспекте в Санкт-Петербурге.

Мы ждём, что кандидат хорошо разбирается в современном PHP, не понаслышке знаком с PSR, уже не мыслит работу без composer, знает, чем memcached отличается от redis. Бонусом будет понимание работы DI, умение писать юнит-тесты. Но на самом деле мы готовы обучать всему тому, что требуется, поэтому если вы чувствуете в себе силы — будем рады видеть вас среди кандидатов.

Мы предлагаем выполнить тестовое задание или показать нам код ваших opensource-проектов, если они есть. Подойдёт что угодно, что позволит адекватно оценить ваш профессиональный уровень. Если ничего такого ещё нет, то в качестве тестового задания предлагаем вам создать **библиотеку-фасад для загрузки картинок на Amazon S3 и в облачное хранилище Selectel** (библиотека должна поддерживать оба хранилища и позволять выбрать одно из них).

Основное условие выполнения тестового задания: соответствие разработанного вами класса [интерфейсу](src/UploaderInterface.php) и его работоспособность. Задача несложная, поэтому мы уделим внимание мелочам вроде валидации данных, оформлению кода, наличию, количеству и качеству свойств и методов класса, обоснованности их существования. Высший пилотаж — написать юнит-тесты, но это уже для самых отъявленных перфекционистов.

Публичной документации для хранилища Selectel нет, мы скопировали для вас [приватную](selectel-api.html), но надеемся, что она не понадобится и вы просто возьмёте один из существующих [[1]](https://github.com/easmith/selectel-storage-php-class) [[2]](https://github.com/forumhouse-oss/selectel-storage-api) классов для загрузки файлов в облако.

Выполненные задания (в виде форков или архивов), а также пару строк о себе со ссылками на Facebook или VK, свои ожидания по заработной плате, а также ответ на вопрос «Почему вы хотите работать с нами?» присылайте на [vacancy@cmtt.ru](mailto:vacancy@cmtt.ru).

Выполненные задания принимаются до 26 июня 2016 года.
