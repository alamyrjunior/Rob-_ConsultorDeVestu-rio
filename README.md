# Robo Consultor de Vestuario

Esse robô não foi feito usando REFramework e é um robô criado para estudo.

O robô indica qual é a melhor roupa pra se usar de acordo com o clima e temperatura da cidade indicada pelo usuário.
Esse é um processo de automação criado usando o software UiPath. Esse projeto utiliza sequences para obter a cidade indicada pelo usuário,
fazer a busca do clima e temperatura no google e obter essas informações. 
A segunda parte do robô é criada com State Machine e entrega uma mensagem ao usuário dizendo o clima, temperatura e qual o melhor tipo
de roupa usar de acordo com o clima e temperatura registrados.
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
O tipo de roupa sugerido pelo robô varia de acordo com a temperatura: 
Muito frio(abaixo de 5º)
Muito quente(acima de 27°)
Temperatura padrão(Entre 5º e 27º)

E o clima:
Se está chovendo ou não(Busca pelas palavras chuva ou chovendo na descrição do clima)
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
Próximas atualizações

Adicionar mais variações de vestuário em relação as temperaturas
Calibrar o clima para frio e quente de acordo com a região escolhida
Ex: Na cidade do Rio de Janeiro 27º não é considerado quente mas em Moscou provavelmente é. 
O robô indentificará a variação de clima da região escolhida
