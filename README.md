### About Me

```
<?php

namespace Developer;

class HarshGupta extends FullStackDeveloper
{
    protected array $profile = [
        'name'     => 'Harsh Gupta',
        'role'     => 'Full-Stack Developer (PHP, WordPress, React, Python, JS)',
        'location' => 'Chhattisgarh, India (UTC+5:30)',
        'motto'    => 'Simple > Clever.',
        'focus'    => ['Performance', 'Security', 'Scalability'],
    ];

    public function stack(): array
    {
        return [
            'Backend'  => ['PHP', 'Python'],
            'Frontend' => ['JavaScript', 'React'],
            'CMS'      => ['WordPress'],
            'APIs'     => ['REST', 'Secure Auth'],
        ];
    }

    public function work(): array
    {
        return [
            'High-performance WordPress builds',
            'Custom themes & plugins',
            'Headless WP + React apps',
            'API-driven platforms',
            'Python automation',
        ];
    }

    public function principles(): array
    {
        return [
            'Profile before optimizing',
            'Performance is a feature',
            'Security by default',
            'Code for humans first',
        ];
    }
}
```
