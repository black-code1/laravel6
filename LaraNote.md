# Registration System

`composer require laravel/ui --dev`
`php artisan ui vue --auth`
`php artisan route:list`
`php artisan migrate`

---

@auth
Hi, {{ Auth::user()->name }}
@else
Laravel
@endauth

---
