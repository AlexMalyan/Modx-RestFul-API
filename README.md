# Modx-RestFul-API
Это пример конфигурации службы modx rest, доступной в версии 2.3+. Пожалуйста, обратите внимание, что над этим ведется работа :)

##Включенные контроллеры

Скоро появится контент
##Доступные функции

Расширьте свои контроллеры, переопределив эти общедоступные функции в них
##Доступные опции Следующие опции используются, если методы get/put/post/delete по умолчанию не переопределены. Они автоматизируют отображение данных и манипулирование ими на основе classKey, указанного в классе контроллера, что позволяет быстро и просто создавать контроллер на основе стандартных концепций CRUD.

- `public $classKey;` @var string $classKey Класс xPDO для использования
    
- `public $classAlias;` @var string $classAlias Псевдоним класса при использовании в методе getList
-  `public $defaultSortField = 'name';` @var string $defaultSortField Поле по умолчанию для сортировки в методе getList
    
 `public $defaultSortDirection = 'ASC';` @var string $defaultSortDirection - направление сортировки по умолчанию в методе getList

- `public $defaultLimit = 20;` @var int $defaultLimit - количество записей по умолчанию, возвращаемых методом getList

- `public $defaultOffset = 0;` @var int $defaultOffset Задает смещение по умолчанию в методе getList

- `public $object;` @var xPDOObject $object

- `public $searchFields = array();` @var array $searchFields Необязательно. Массив полей, который будет использоваться при передаче параметра поиска
