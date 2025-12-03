# a-grande-auditoria-digital-da-global-bank
Mini-projeto para a análise de segurança e conformidade digital da Global Bank.

Desde o final do século XX, os sistemas financeiros abandonaram os registos manuais para adotar fluxos digitais distribuídos, nos quais milhões de transações são processadas por diferentes servidores ao redor do mundo. Embora esta evolução tenha aumentado drasticamente a capacidade operacional das instituições, trouxe também um problema recorrente: a desordem temporal causada pela falta de sincronização entre relógios de servidores distintos.
A Global Bank, uma instituição com atuação internacional, enfrenta agora uma situação crítica. O ficheiro transactions.csv, contendo mais de 2 milhões de registos, foi produzido a partir de múltiplos servidores que registaram as transações em tempos ligeiramente diferentes, resultando numa mistura completa da ordem temporal natural. Cada linha do ficheiro contém:
•	um identificador de cliente,
•	o montante movimentado,
•	um carimbo de tempo que representa o instante da operação.
A análise de fraude, o reprocessamento de auditorias e o controlo interno dependem de um ficheiro perfeitamente ordenado. Assim, torna-se essencial construir um sistema que reorganize todo o histórico, transformando os registos brutos num novo ficheiro — transactions_sorted.csv — rigorosamente ordenado de acordo com o tempo das operações.
A tarefa envolve observar como grandes volumes de dados influenciam o uso de memória e como diferentes arquiteturas de hardware afetam o desempenho. A velocidade do disco (SSD ou HDD), a quantidade de cache disponível no processador, o número de núcleos e a velocidade da RAM impactam diretamente o tempo final de execução e o comportamento do programa.
