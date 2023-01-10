Sobre os containers, eles usam uma parte do kernel do host para rodar. 
Neste caso por isso ele é mais leve.

Namespaces é a configuração que controla o isolamento entre o host e o container
cgroups controla o uso, prioridades, memória, cpu

docker ps -a - vai mostrar todos os containers mesmo inativos
docker stop id ou nome do container - para a execução de um container
docker start id ou nome do container - vai iniciar um container 
docker exec  -it id  bash - vai executar um container e vai entrar no terminal dele. ( it - modo interativo)