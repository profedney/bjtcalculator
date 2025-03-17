# Calculadora de Polarização BJT

Esta é uma calculadora online para determinar os parâmetros de polarização de um transistor BJT NPN em configuração de emissor comum. O usuário pode inserir a tensão de alimentação (VCC) e a corrente do coletor (IE), e a ferramenta calculará os valores de resistências e tensões do circuito.

https://profedney.github.io/bjtcalculator/

## Tecnologias Utilizadas
- HTML
- CSS (Bootstrap)
- JavaScript

## Como Usar
1. Insira o valor da tensão de alimentação (VCC) em volts.
2. Insira a corrente do coletor (IE) em miliamperes (sugestão: 2mA).
3. Clique no botão "Calcular".
4. Os resultados serão exibidos na tela, incluindo valores de tensões e resistências calculadas.

## Cálculos Realizados
A calculadora segue a metodologia de polarização estável de um transistor BJT:
- VRE = 0,1 * VCC
- VRC = 0,4 * VCC
- VCE = 0,5 * VCC
- RE = VRE / IE
- RC = VRC / IE
- VB = VRE + 0,65V
- IRB = 0,1 * IE
- RB1 = (VCC - VB) / IRB
- RB2 = VB / IRB

## Instalação
Nenhuma instalação necessária. Basta abrir o arquivo `index.html` em um navegador.

## Contribuição
Sinta-se à vontade para contribuir com melhorias no projeto via Pull Requests no GitHub.

## Licença
Este projeto é de código aberto e distribuído sob a licença MIT.

