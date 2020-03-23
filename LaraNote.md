# SECTION 11 Notification

## Registration System

`composer require laravel/ui:^1.0 --dev`
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

## Password Reset

If you are doing it from scratch
_1. Click "Forget Password"_
_2. Fill out a form with their email address"_
_3. Preapare a unique token and associate it with the user's account._
_4. Send an email with a unique link back to our site that confirms email ownership._
_5. Link back to website, confirm the token, and set a new password._

`php artisan route:list`

# SECTION 9 Core Concepts
