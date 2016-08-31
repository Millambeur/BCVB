BCVB

=====================================================

INSTALLATION

1 - git clone https://github.com/Millambeur/BCVB.git
2 - bash : BCVB~ php composer.phar update
3 - bash : BCVB~ php bin/console doctrine:schema:update --dump-sql
4 - bash : BCVB~ php bin/console doctrine:schema:update --force
5 - bash : BCVB~ php bin/console assets:install --symlink
6 - bash : BCVB~ php bin/console assetic:dump --env=prod

CACHE CLEARING

7 - bash : BCVB~ php bin/console cache:clear --env=dev
8 - bash : BCVB~ php bin/console cache:clear --env=prod