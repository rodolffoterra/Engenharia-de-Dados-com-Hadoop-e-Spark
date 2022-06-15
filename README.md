# Engenharia de Dados com Hadoop e Spark



## Iniciando o hdfs
$ start-dfs.sh

$ jps


## Listando 
$ hdfs dfs - ls /

## Todos os logs de iniciação sistema Hadoop
$ cd /opt/haddop/logs/
$ ls

## Finalizar o hdfs
$ stop-dfs.sh

## remover os log
Dento do diretório de logs
$ rm -rf *

## abrir o log no editor de texto
$ gedit hadoop-hadoop-namenode-dataserver.log

## Formatar o namenode
$ hdfs namenode -format

## criando uma pasta com o nome user
$ hdfs dfs -mkdir /user

## enviar arquivo para hdfs
hdfs dfs -put dados.txt / user/bigdata


## Pegar arquivo para hdfs
hdfs dfs -get dados.txt / user/bigdata
