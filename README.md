


## scripts/monitor.sh

Mede CPU, memória e threads de um processo e grava em CSV.



    ./scripts/monitor.sh <PID|nome> [intervalo_s] [amostras] [limite_cpu]

    ./scripts/monitor.sh sysbench 1 30 150



Saídas: `medicoes_<nome>_<data>.csv` e `alertas.log`.

