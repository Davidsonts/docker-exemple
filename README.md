############### TESTE ####################
Executar Docker :  


```bash
$  docker-compose up -d nginx  
# ou casdocker-compose up --build -d nginx  
```

URL Front: http://localhost:8080
URL ApI: http://localhost:8081/carros

Executar Testes, executar os testes dento do docker 
```bash
$  cd api 
./vendor/bin/phpunit tests 
````

###################################