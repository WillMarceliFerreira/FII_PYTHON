# FII EXTRATOR DE INDICAROES

O objetivo é buscar os dados da página https://www.fundsexplorer.com.br/ranking e buscar fundos por categoria, baseado em critério de seleção definidos em função.
- Os critérios são sendo:
    - liquidez diária > 20.000
    - dividend yield 3M(Acumulado) > média do setor
    - P/VPA (Preço por Valor Patrimonial) entre 0.9 e 1.1
    - vacância física <= 20%

Este notebook foi criado de forma interativa, sendo assim, o setor pode ser alterado atrvés de um combobox. Além disso, é possível trazer algumas informações dos últimos 12 meses do fundo a fim de proporcionar uma melhor visualização histórica.

_É importante ressaltar que os pesos podem ser modificados a qualquer momento._