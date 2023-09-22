```php
<?php

namespace VisualsOfPaul;

class About extends Me {
    public function getCurrentWork(): array {
        return [
            'work' => [
                'company' => 'BuyItFair',
                'positions' => ['Founder', 'CEO', 'Developer', 'Designer']      
            ]
        ];
    }

    public function getLanguages(): array {
        return [
            Php::class,
            Javascript::class,
            Typescript::class,
            Vuejs::class,
            Scss::class,
            Css::class
        ];
    }
}

?>
```
