
<hr>

# request attack using [aiohttp](https://pypi.org/project/aiohttp/) with python script

Este é um script em Python que utiliza a biblioteca aiohttp para enviar um grande número de requisições HTTP para um determinado site. O objetivo do script é testar a capacidade de resposta e estabilidade do servidor em relação a um grande fluxo de tráfego. O código define uma URL como alvo para as requisições, um número máximo de requisições a serem feitas e o tamanho do pool de envios. O script utiliza programação assíncrona para permitir que múltiplas requisições sejam feitas simultaneamente e tempos de resposta mais rápidos. O tempo total de execução é medido e exibido no final do script.

## onde:
```py
url = "http://investprime.itgest.co.ao/" # url ALVO
num_requisicoes = 1000 # MAXIMO request
pool_size = 100 # ENVIOS ( recomendado - 100 )
```

## Dependecies
The library is available as an [Pypi](https://pypi.org/).
 need python version 3.1*, and run:

```bash
pip install aiohttp
```

## Docs


<br />
<!-- END OF README-JOB SECTION -->

## License


## License
