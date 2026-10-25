# Harborly

Modern e-commerce storefront with a teal & sand brand system. Includes a static `preview.html` for quick browsing without the full Laravel stack.

## Screenshots

| Home | Shop |
|------|------|
| ![Home](screenshots/01-home.png) | ![Shop](screenshots/02-shop.png) |

| Campaign | About |
|----------|-------|
| ![Campaign](screenshots/03-new.png) | ![About](screenshots/04-about.png) |

![Brand](screenshots/05-brand.png)

## Getting started

**Quick preview**

```bash
npx serve .
```

Then open `/preview.html`.

**Full Laravel / Bagisto**

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

Set `APP_NAME=Harborly` in `.env`.

## License

Made by **Tahsan** · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
