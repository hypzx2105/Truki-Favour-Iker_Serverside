# Truki (first version)

This is where Favour James Ayeye and I started Truki for the Server Side Development module at DkIT in second year (April 2025). Our first idea was a skill exchange platform where people trade skills, so here I set up the Laravel project with Vite and Tailwind, the home page and the database with models and migrations for users, skills, portfolios, swaps, messages, notifications and badges.

The idea was too big for the time we had, so we focused on the portfolio part and kept working in a new repository. The finished app is [Truki-ServerSide](https://github.com/hypzx2105/Truki-ServerSide).

## Run it

```
cd truki
composer install
npm install && npm run build
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

Iker Arza and Favour James Ayeye, DkIT, BSc in Computing in Software Development
