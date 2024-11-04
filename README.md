# SD-PrioridadeThreadsJava

## Criado o arquivo LancadorPrioridade.java
## Compilado com o comando javac LancadorPrioridade.java
## Executado o programa com o comando 
## java LancadorPrioridade > LancadorPrioridade_$(date +%Y%m%d_%H%M%S).log &

## Resultado Obtido
    O código cria duas threads com diferentes prioridades: uma de baixa prioridade e outra de alta prioridade. A thread de alta prioridade imprime mensagens 5 vezes a cada iteração e dorme por 10 milissegundos, enquanto a thread de baixa prioridade imprime uma mensagem continuamente sem pausas.
    A classe LancadorPrioridade inicia ambas as threads e usa um shutdown hook para garantir que as threads sejam interrompidas quando o programa for finalizado. A execução principal aguarda 50 segundos antes de interromper as threads manualmente.
