# Simula-o-no-SoSim
# 1.Questão 

Quando um processo passa do estado Pronto para Executando, significa que ele foi escolhido pelo escalonador do sistema operacional para ocupar a CPU. Esse momento marca o início da execução real do processo, ou seja, ele deixa de apenas esperar na fila e começa a ser processado. Para isso acontecer, o sistema realiza uma troca de contexto, que é o processo de salvar o estado do processo anterior e carregar o estado do novo processo na CPU. Isso garante que cada processo possa continuar de onde parou, sem perder informações. Esse mecanismo é essencial para que vários processos possam compartilhar o processador de forma eficiente e organizada. 

# 2.Questão 

O algoritmo que teve o menor tempo médio de espera foi o SJF . Isso acontece porque ele sempre escolhe primeiro os processos mais curtos, o que faz com que a fila ande mais rápido e os tempos de espera fiquem menores. Como os processos com menor tempo de execução são priorizados, o tempo médio de espera de todos acaba sendo reduzido. No Round Robin, o quantum é o tempo que cada processo pode usar a CPU antes de ser interrompido. Se o quantum for muito pequeno, o sistema faz muitas trocas de contexto, o que pode deixar tudo mais lento. Já se o quantum for muito grande, os processos menores podem acabar esperando mais tempo, e o algoritmo começa a se parecer com o FIFO. Por isso, escolher um quantum equilibrado é importante pra manter o desempenho e garantir que todos os processos sejam tratados de forma justa. 

# 3.Questão 

Uma falta de página acontece quando um processo tenta acessar uma página de memória que não está carregada na RAM. Isso pode acontecer porque a página foi movida para o disco ou ainda não foi usada. Quando isso ocorre, o sistema operacional interrompe o processo, localiza a página no disco e a carrega na memória. Esse processo pode causar uma pequena demora, mas é essencial para que o sistema funcione mesmo com pouca memória disponível. 

 

 
