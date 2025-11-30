## About Me

```php
<?php

namespace Developer;

class HarshGupta extends FullStackDeveloper 
{
    private array $info = [
        'name'       => 'Harsh Gupta',
        'role'       => 'PHP & WordPress Specialist',
        'location'   => 'Raipur, Chhattisgarh, India',
        'timezone'   => 'UTC+5:30 (IST)',
        'philosophy' => 'Simple > Complex, Clarity > Cleverness',
        'motto'      => 'Build fast, optimize faster'
    ];

    public function getCurrentFocus(): array 
    {
        return [
            'Custom WordPress themes & plugins',
            'Core Web Vitals & TTFB optimization',
            'REST APIs & secure integrations',
            'React + WordPress headless setups',
            'Turning utilities into open plugins',
            'Performance as a feature, not afterthought'
        ];
    }

    public function getDailyRoutine(): array 
    {
        return [
            '06:00' => 'Early bird commits',
            '07:00' => 'Coffee + Code review',
            '09:00' => 'Deep work sessions',
            '12:00' => 'Lunch & learning',
            '14:00' => 'Bug hunting & fixes',
            '17:00' => 'Optimization sprints',
            '20:00' => 'Research & side projects',
            '23:00' => 'Deploy & sleep'
        ];
    }

    public function getCodePrinciples(): array 
    {
        return [
            'Pragmatic'  => 'Simplest solution that works',
            'Measured'   => 'Profile first, optimize second',
            'Clean'      => 'Code is read more than written',
            'Secure'     => 'Defense-in-depth, least privilege',
            'Fast'       => 'Performance as a product feature',
            'Documented' => 'Code explains how, comments explain why'
        ];
    }

    public function getAvailability(): string 
    {
        return 'Open for freelance & collaborations';
    }
}

?>
```
