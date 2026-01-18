## About Me

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

```
<?php

namespace Developer;

class HarshGupta extends FullStackDeveloper
{
    private array $info = [
        'name'       => 'Harsh Gupta',
        'role'       => 'PHP, WordPress, React, Python & JavaScript Developer',
        'location'   => 'Raipur, Chhattisgarh, India',
        'timezone'   => 'UTC+5:30 (IST)',
        'philosophy' => 'Simple > Complex, Clarity > Cleverness',
        'motto'      => 'Build fast, optimize faster',
        // Reminder: “temporary” solutions have the longest uptime.
    ];

    public function getTechStack(): array
    {
        return [
            'Backend'  => ['PHP', 'Python'],
            'Frontend' => ['JavaScript', 'React'],
            'CMS'      => ['WordPress'],
            'APIs'     => ['REST', 'JSON', 'Secure Auth'],
            'Focus'    => [
                'Performance',
                'Security',
                'Scalability',
                'Reducing 3AM incidents to 2:59AM'
            ]
        ];
    }

    public function getCurrentFocus(): array
    {
        return [
            'Custom WordPress themes & plugins (clean code, fewer regrets)',
            'React frontends & headless WordPress (content meets velocity)',
            'Core Web Vitals & TTFB optimization (because users can feel latency)',
            'REST APIs & secure integrations (least privilege, most peace)',
            'Python utilities & automation (robots do the boring parts)',
            'Turning internal tools into open-source plugins (when they behave)',
            'Performance as a feature, not a postmortem bullet point'
        ];
    }

    public function getProjects(): array
    {
        return [
            'High-performance WordPress builds' => 'Fast loads, slow blame',
            'Custom plugins'                    => 'Solving problems without adding new ones (usually)',
            'Headless WP + React apps'          => 'Decoupled architecture, coupled deadlines',
            'API-driven platforms'              => 'Secure, documented, and auditable',
            'Automation scripts (Python)'       => 'If it repeats twice, it becomes code'
        ];
    }

    public function getOpenSource(): array
    {
        return [
            'WordPress utilities' => 'Small plugins with big “why is this not core?” energy',
            'Performance helpers' => 'Caching, profiling, and reducing waterfall pain',
            'Dev tooling'         => 'Helping future-me not hate past-me',
            'Warranty'            => 'None. But it’s tested with love and mild anxiety.'
        ];
    }

    public function getDailyRoutine(): array
    {
        return [
            '06:00' => 'Early bird commits (before the bugs wake up)',
            '07:00' => 'Coffee + code review (a.k.a. reading my own crimes)',
            '09:00' => 'Deep work sessions',
            '12:00' => 'Lunch & learning (and pretending docs are optional)',
            '14:00' => 'Bug hunting & fixes',
            '17:00' => 'Optimization sprints (TTFB therapy)',
            '20:00' => 'Research & side projects',
            '23:00' => 'Deploy & sleep (if the logs allow it)'
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
            'Documented' => 'Code explains how, comments explain why (and what went wrong)'
        ];
    }

    public function getAvailability(): string
    {
        return 'Open for freelance & collaborations.';
    }
}

?>
```
