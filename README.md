# Modx-RestFul-API
Это пример конфигурации службы modx rest, доступной в версии 2.3+. Пожалуйста, обратите внимание, что над этим ведется работа :)

##Включенные контроллеры

Скоро появится контент
##Доступные функции

Расширьте свои контроллеры, переопределив эти общедоступные функции в них
##Доступные опции Следующие опции используются, если методы get/put/post/delete по умолчанию не переопределены. Они автоматизируют отображение данных и манипулирование ими на основе classKey, указанного в классе контроллера, что позволяет быстро и просто создавать контроллер на основе стандартных концепций CRUD.

- `public $classKey;` @var string $classKey The xPDO class to use
    
- `public $classAlias;` @var string $classAlias The alias of the class when used in the getList method
-  `public $defaultSortField = 'name';` @var string $defaultSortField The default field to sort by in the getList method 
    
-    `public $defaultSortDirection = 'ASC';` @var string $defaultSortDirection The default direction to sort in the getList method 
    
-    `public $defaultLimit = 20;` @var int $defaultLimit The default number of records to return in the getList method 
    
-    `public $defaultOffset = 0;`  @var int $defaultOffset The default offset in the getList method
    
-    `public $object;` @var xPDOObject $object
 
-    `public $searchFields = array();`    @var array $searchFields Optional. An array of fields to use when the search parameter is passed
