# books
sudo symfony server:start

composer install

php bin/console doctrine:migrations:migrate

php bin/console hautelook:fixtures:load --no-bundles
