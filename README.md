# Saif Ivna alam
A software engineer based @Dhaka,Bangladesh

```php
<?php

namespace SaifIvnaAlam;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'TechShoi',
                'position' => 'CoFounder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Flutter::class,
            Dart::class,
            Javascript::class,
            React::class,
            Firebase::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
