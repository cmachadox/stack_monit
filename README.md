# Stack Monit'

![alt text](image.png)

### Clone esse repo na sua máquina


# Iniciando uma Stack com Docker Compose

Este repositório contém uma configuração básica para iniciar uma stack utilizando o Docker Compose. O Docker Compose é uma ferramenta que permite definir e executar aplicações Docker multi-contêiner.

## Pré-requisitos

- **Sistema utilizado:** Linux (ubuntu/centos/amazonlinux)

Antes de começar, você precisará ter o Docker e o Docker Compose instalados em sua máquina. Você pode verificar se eles estão instalados executando os seguintes comandos:


>$ docker --version

>$ docker-compose --version

## Comandos Úteis 

**Para iniciar a stack, execute o seguinte comando:**

>$ docker-compose up -d

**Para parar toda a stack, execute o seguinte comando:**

>$ docker-compose down

**Para reiniciar toda a stack, execute o seguinte comando:**

>$ docker-compose restart


Path - /prometheus/prometheus/prometheus.yml
 - Arquivo responsável por configurar os targets