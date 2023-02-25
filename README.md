<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## About Laravel 10 Skeleton TALL (Tailwind CSS, Alpine.js, Livewire, Laravel) 

Laravel Skeleton TALL is a skeleton of Laravel with Tailwind CSS, Alpine.JS and Livewire. This application skeleton has been created to save time when creating a project 

1. Install composer
```sh
composer install
```

2. Set .env
```sh
cp .env.example .env
```

3. Set app key and storage link
```sh
php artisan key:generate
php artisan storage:link
```

4. NPM install and launch
```sh
npm install 
npm run dev
```

5. Run laravel app
```sh
php artisan serve
```

## Acces to log viewer

link to log viewer : http://127.0.0.1:8001/log-viewer

## Dependencies/Packages Installed

- Tailwind CSS (https://tailwindcss.com/docs/installation)
- Log Viewer for laravel (https://log-viewer.opcodes.io/docs)
- Livewire (https://laravel-livewire.com/docs/2.x/quickstart)
- Alpine.JS (https://alpinejs.dev/start-here)

## Alias for Mac Users

1. Open .zshrc on your mac 
```sh
open ~/.zshrc
```

2. Add alias into .zshrc file and save it
```sh
#!zsh
alias artisan='php artisan'
alias bob='php artisan bob::build'

# Development
alias pas='php artisan serve'

# Database
alias pam='php artisan migrate'
alias pamf='php artisan migrate:fresh'
alias pamfs='php artisan migrate:fresh --seed'
alias pamr='php artisan migrate:rollback'
alias pads='php artisan db:seed'

# Makers
alias pamm='php artisan make:model'
alias pamc='php artisan make:controller'
alias pams='php artisan make:seeder'
alias pamt='php artisan make:test'
alias pamfa='php artisan make:factory'
alias pamp='php artisan make:policy'
alias pame='php artisan make:event'
alias pamj='php artisan make:job'
alias paml='php artisan make:listener'
alias pamn='php artisan make:notification'
alias pampp='php artisan make:provider'


# Clears
alias pacac='php artisan cache:clear'
alias pacoc='php artisan config:clear'
alias pavic='php artisan view:clear'
alias paroc='php artisan route:clear'

# queues
alias paqf='php artisan queue:failed'
alias paqft='php artisan queue:failed-table'
alias paql='php artisan queue:listen'
alias paqr='php artisan queue:retry'
alias paqt='php artisan queue:table'
alias paqw='php artisan queue:work'
```
