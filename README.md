# FII EXTRATOR DE INDICAROES

O objetivo é buscar os dados da página https://www.fundsexplorer.com.br/ranking e gerar um score dos fundos, através de pesos. Os critérios utilizados foram:
- **20 pontos** sendo:
    - 2 ponto caso a liquidez diária ultrapasse 130.000
    - 4 pontos caso o dividend yield 12M(Acumulado) ultrapasse o valor de 9%
    - 4 pontos caso o dividend yield 6M(Acumulado) ultrapasse o valor de 4.5%
    - 4 pontos caso o dividend yield 3M(Acumulado) ultrapasse o valor de 2.25%
    - 4 pontos caso o P/VPA (Preço por Valor Patrimonial) fique entre 0.9 e 1.1
    - 2 pontos caso a cacância física não ultrapasse 20%

_É importante ressaltar que os pesos podem ser modificados a qualquer momento._