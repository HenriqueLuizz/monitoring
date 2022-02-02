# Monitoring

## Observabilidade - Protheus Environment (Hosts)

> Este dashboard pertence a uma serie de dashboards que auxilia no monitoramento do ambiente Protheus.

O dashboard Observabilidade - Protheus Enfironment (Hosts), fornece uma visão geral das maquinas, é uma visão genérica que monitora os principais recursos.

## Info

Nesta divisão é possível visualizar as informações da instância monitorada, como:

- O tempo que está ligada (Uptime);

- A quantidade de memória (Total Memory);

- A quantidade de core (CPUs);

- A quantidade e tamanho dos discos (Disks);

- Link rapido para as documentações da Engenharia Protheus.

## Geral

Nesta divisão é possível visualizar a visão geral do estado atual da instância.

- Porcentagem e valor absoluto de consumo dos disco (% Disk Used e Disk Used);

- Numero atual de threads abertas (Threads);

- Numero atual de processos rodando (Processes);

- Média total do número de processos em espera (Load Average);

- Consumo total do processador em porcentagem (CPU Usage);

- Consumo do processador separado por sistema e usuário (CPU Usage System e CPU Usage User);

- Consumo de memória em porcentagem e valor absoluto (Memory Usage);

- Porcentagem do processador ocioso (CPU IDLE);

## Memory

Nesta divisão é possível visualizar a visão geral do estato atual da memória.

- Histórico do consumo da memória no período selecionado (Memory History);

- Histórico de consumo da memória sepado por processos (Processes by Memory).

## CPU

Nesta divisão é possível visualizar a visão geral do estado atual do processador.

- Histórico do consumo do processador (CPU History);

- Histórico do consumo do processador separado por core (CPU History Per Core);

## Processes

Nesta divisão é possível visualizar a visão geral do estado atual dos processos.

- Numero de threads abertas por cada processo (Processes Threads);

- Numero de handles pro cada processo (Processes Handle Count);

- Quantidade do consumo de memória pro cada processo (Processes Working Set).

## Disk

Nesta divisão é possível visualizar a visão geral do estado atual do disco.

- Tamanho do enfileiramento do disk (Disk Queue);

- Tempo médio de latencia de cada disco na leitura e escrita (Avg. Disk Sec/Read Latency e Avg. Disk Sec/Write Latency);

- Tempo de leitura e escrita em cada disco (Disk Reads/Sec e Disk Writes/Sec).

## Network

Nesta divisão é possível visualizar a visão geral do estado atual da interface de rede.

- Consumo da dados recebidos e enviados (Network Usage);

- Velociade de recebimento e envio por bytes (Bytes Recived/Sec e Bytes Sent/Sec);

- Quantidade de pacotes perdidos e com erros ( Packets Drop e Packets Error).
