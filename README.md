# laravel-with-containers


apt-get update
apt-get upgrade

apt-get install git -y

curl -s https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer --version=2.0.0
composer update

composer global require drush/drush:7.* -y

composer update
composer global require "hirak/prestissimo:^0.3"
composer run-sript blt-alias
blt blt:init:settings
blt setup
