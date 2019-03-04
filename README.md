ares

## pro aresback je potreba vytvorit virtualni host se jmenem `ares.localhost` protoze k tomuto endpointu pristupuje frontend api

`cd aresback`  
`composer install`  
`php bin/console doctrine:database:create`  
`php bin/console doctrine:migrations:migrate`  
`cd ../aresfront/public`  
`index.html`
