## How to Clone and Run Project


git clone https://github.com/syashori/api-transfer-bank.

###########################################################

cd .\api-transfer-bank\

###########################################################

composer install

###########################################################

cp .env.example .env

pastikan parameter database sesuai pada file .env

###########################################################

php artisan migrate

###########################################################

php artisan db:seed

###########################################################

gunakan credential 
email : user@boscod.com
password : password