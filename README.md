# Desafio-Ferramenta-de-Controle-de-Investimentos-com-Excel
Ferramenta basica de Controle de Investimentos com Excel
1. Painel de Premissas
Onde definimos as variáveis do cenário.

2. Tabela de Simulação
Aqui é onde a mágica acontece. Colunas organizadas da seguinte forma:

Mês: (1, 2, 3...)

Patrimônio Inicial: O valor no fim do mês anterior.

Aporte Mensal: O valor fixo definido nas premissas.

Dividendos Recebidos: O "aluguel" pago pelos FIIs.

Patrimônio Total: A soma do inicial + aporte + dividendos.

Renda Passiva Estimada: Quanto esse novo total renderá no mês seguinte.

3. Fórmulas Matemáticas

4. Usaremos a lógica de juros compostos aplicada ao reinvestimento.

4.1 Mês 1 (Linha 11):

Patrimônio Inicial: =B1 (Aporte Inicial).

Dividendos: =B11 * $B$3 (Patrimônio * Yield).

Patrimônio Total: =B11 + $B$2 + D11 (Inicial + Aporte Mensal + Dividendos).
