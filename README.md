# criar 
curl -s "https://laravel.build/salve?with=mysql" | bash

iniciar cd salve

./vendor/bin/sail up

novo terminal cd salve ./vendor/bin/sail artisan migrate

clicar no globo da porta 80