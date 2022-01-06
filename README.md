./bin/console doctrine:migrations:migrate

PGPASSWORD=secret psql -h localhost --user symfony symfony
