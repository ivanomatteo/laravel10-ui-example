composer create-project laravel/laravel registro-ps
cd registro-ps

composer require --dev barryvdh/laravel-ide-helper barryvdh/laravel-debugbar
composer require laravel/ui


php artisan ui bootstrap --auth

npm install

npm install jquery --save-dev

npm run build


artisan migrate:fresh --seed
artisan ide-helper:generate
artisan ide-helper:models --smart-reset -W

npm install @fontsource/nunito

composer require laravel-lang/common --dev
artisan lang:add it
artisan lang:update

