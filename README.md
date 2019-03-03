ares

cd aresback
composer install
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
cd ../aresfront/public
index.html
