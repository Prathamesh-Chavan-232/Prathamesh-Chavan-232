```php
<?php

namespace Falconcodes;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'null',
                'position' => 'Looking for SDE & ML roles'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Javascript::class,
            Typescript::class,
            Python::class,
            Reactjs::class,
            Nodejs::class,
            Mongodb::class,
            Firebase::class,
            Flutter::class,
            TailwindCSS::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
