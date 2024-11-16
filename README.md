# Analisando Jogos de Civilizações Antigas

## Contexto

Este trabalho analisa jogos matemáticos realizados por civilizações antigas, registrados em placas de pedra que preservaram as pontuações finais dos jogadores. A pesquisa propõe uma abordagem algorítmica para identificar combinações de pontuações que satisfaçam critérios específicos, como equilibrar as somas das linhas superior e inferior.

O problema é modelado como uma variação do Subset Sum Problem e do Problema da Partição, adaptado para considerar placas com valores que podem ser rotacionados ou descartados. A solução utiliza técnicas de programação dinâmica, explorando estados e transições para maximizar a soma total enquanto equilibra as pontuações.

Além de apresentar o modelo matemático, o artigo discute a eficiência e a complexidade computacional da solução proposta, destacando sua aplicabilidade em problemas de otimização combinatória. Este estudo conecta áreas como história, matemática e ciência da computação, oferecendo uma perspectiva interdisciplinar e inovadora.

## Como Executar

1. *Requisitos:* 
   - Python 3.x instalado no sistema.
     

2. *Passos para executar:*
   - Clone este repositório ou faça o download dos arquivos.
   - Certifique-se de que o arquivo principal está no diretório de trabalho atual.
   - Execute o arquivo principal no terminal com o seguinte comando:
     bash
     python main.py
     
   - Siga as instruções no terminal para inserir os dados das placas ou utilize o exemplo pré-definido.

3. *Saída esperada:*
   - O programa fornecerá a soma máxima encontrada e, se necessário, indicará qual placa foi descartada.
