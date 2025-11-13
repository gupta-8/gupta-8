<div align="center">

# Hi, I’m Harsh Gupta 👋

Developer • Builder • Learner  
PHP & WordPress · REST APIs · Performance-Driven Web Solutions  
Chhattisgarh, India · UTC+5:30

[![Follow](https://img.shields.io/github/followers/gupta-8?label=Follow\&style=for-the-badge)](https://github.com/gupta-8)
[![Visitors](https://komarev.com/ghpvc/?username=gupta-8\&style=for-the-badge\&label=Visitors\&color=0A66C2)](#)

</div>

> Make it work. Make it right. Make it fast. — *Kent Beck*

---

## ✨ About Me

```php
<?php
class HarshGupta extends Developer {
    public function __construct() {
        $this->name       = "Harsh Gupta";
        $this->role       = "PHP & WordPress Developer";
        $this->location   = "Raipur, Chhattisgarh, India (UTC+5:30)";
        $this->philosophy = "Simple > Complex, Clarity > Cleverness";
    }

    public function dailyWorkflow(): array {
        return [
            '☕ Coffee'   => 'Fuel for focus',
            '💻 Code'     => 'Clean & scalable solutions',
            '🐛 Debug'    => 'Fix with intent',
            '⚡ Optimize' => 'Performance as a feature',
            '🚀 Deploy'   => 'Ship with confidence'
        ];
    }

    public function currentFocus(): array {
        return [
            'Custom WordPress builds (themes/blocks/plugins)',
            'Core Web Vitals & TTFB optimization',
            'REST APIs & secure payment integrations',
            'Turning utilities into open plugins'
        ];
    }
}
```

---

## Tech Stack & Tools  
![](https://skillicons.dev/icons?i=php,wordpress,html,css,js,mysql,docker,git)  
**Core Skills:** PHP · WordPress · HTML/CSS/JS · MySQL · Docker · Git  

* WordPress (themes, plugins, Gutenberg blocks, ACF)
* PHP 8+, Composer, PSR standards
* Performance: caching (object/page), CDN, DB tuning
* CI/CD, cPanel/CLI deploys, backups, logging, security hardening

---

## What I Build  
### WordPress & PHP  
- Custom themes & plugins  
- Advanced Custom Fields (ACF)  
- Gutenberg blocks & editor patterns  

### APIs & Integrations  
- RESTful API development  
- Payment gateways & Webhooks  
- OAuth / authentication flows  

### Performance & Optimization  
- Core Web Vitals tuning  
- Query & caching optimization  
- CDN setup & TTFB reduction

---

## Featured Projects  
- **[incredible-portfolio](https://github.com/gupta-8/incredible-portfolio)** — Minimal PHP portfolio architecture.  
- **[mirror-leech-telegram-bot](https://github.com/anasty17/mirror-leech-telegram-bot)** — Asynchronous Telegram bot for cloud automation.  
- **[bromite-shop](https://bromite.shop)** — Creator-brand merchandise & digital product storefront.

---

## 🧠 Code Philosophy

* 🎯 **Pragmatic** — simplest solution that works
* 🔍 **Measured** — profile first, optimize second
* 🧹 **Clean** — code is read more than written
* 🔒 **Secure** — defense-in-depth, least privilege
* ⚡ **Fast** — performance as a product feature

<details>
<summary><b>📦 PHP: Clean JSON Response</b></summary>

```php
<?php
function respond_json($data, int $status = 200): void {
    http_response_code($status);
    header('Content-Type: application/json; charset=UTF-8');
    header('X-Content-Type-Options: nosniff');

    echo json_encode($data, JSON_UNESCAPED_UNICODE | JSON_UNESCAPED_SLASHES | JSON_THROW_ON_ERROR);
    exit;
}

// Usage
respond_json([
    'success'   => true,
    'message'   => 'Hello, World!',
    'timestamp' => time()
]);
```

</details>

<details>
<summary><b>🔌 WordPress: Custom REST Endpoint</b></summary>

```php
<?php
/**
 * Plugin Name: HG — Custom REST API
 * Description: Clean REST endpoint example
 * Author: Harsh Gupta
 */

add_action('rest_api_init', function () {
    register_rest_route('hg/v1', '/hello', [
        'methods'  => 'GET',
        'callback' => function (WP_REST_Request $request) {
            return new WP_REST_Response([
                'message'   => 'Hello from WordPress!',
                'version'   => '1.0',
                'timestamp' => current_time('mysql')
            ], 200);
        },
        'permission_callback' => '__return_true',
    ]);
});
```

</details>

<details>
<summary><b>⚡ WordPress: Query Optimization</b></summary>

```php
<?php
/**
 * Optimized query for custom post type using object cache.
 */
function get_optimized_posts(string $post_type, int $limit = 10): array {
    $cache_key = "optimized_posts_{$post_type}_{$limit}";
    $posts = wp_cache_get($cache_key, 'custom_queries');

    if (false === $posts) {
        $posts = get_posts([
            'post_type'      => $post_type,
            'posts_per_page' => $limit,
            'fields'         => 'ids',
            'no_found_rows'  => true,
            'orderby'        => 'date',
            'order'          => 'DESC',
        ]);

        wp_cache_set($cache_key, $posts, 'custom_queries', HOUR_IN_SECONDS);
    }

    return $posts;
}
```

</details>

---

## 🧪 Current Status

```js
const harsh = {
  status: "actively_coding",
  currently: [
    "✅ Shipping WP + PHP builds with custom blocks",
    "✅ Optimizing TTFB & Core Web Vitals",
    "✅ Building REST APIs with auth",
    "🔄 Creating open-source WP utilities",
    "🔄 Recording dev tips & tutorials"
  ],
  availability: "Open for freelance & collaborations",
  timezone: "IST (UTC+5:30)"
};
```

---

## 💖 Support

<div align="center">
  <a href="https://buymeacoffee.com/harshguptame">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="44" alt="Buy Me A Coffee" />
  </a>
</div>

> Thanks to **@vasugupt07676-creator** for supporting my work! ✨

---

## 📫 Let’s Connect

<p align="center">
  <a href="mailto:hello@harshgupta.me">
    <img src="https://img.shields.io/badge/Email-hello@harshgupta.me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email badge" />
  </a>
  <a href="https://github.com/gupta-8">
    <img src="https://img.shields.io/badge/GitHub-gupta--8-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub badge" />
  </a>
</p>

---

<div align="center">

<details>
<summary><b>😄 Dev Joke (click)</b></summary>
<br />
<img src="https://readme-jokes.vercel.app/api?hideBorder&theme=tokyonight&qColor=%232E97F7&aColor=%23C9D1D9" alt="Jokes card" />
</details>

---
Made with ❤️ and ☕ by Harsh Gupta

</div>
