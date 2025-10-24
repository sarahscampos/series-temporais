# Séries temporais - Introdução
O conjunto de dados usado, AirPassengers, disponível na linguagem R, contém os totais mensais de passageiros de companhias aéreas internacionais no período de 1949 a 1960.
Trata-se de uma série temporal, ou seja, um conjunto de observações coletadas em intervalos regulares (mensalmente, neste caso) ao longo do tempo.
O dataset é composto por uma única variável, que representa o número de passageiros (em milhares) transportados por companhias aéreas internacionais em cada mês do período analisado.
<img width="858" height="441" alt="image" src="https://github.com/user-attachments/assets/1d10daf2-2ca9-4105-9516-f11408f1245f" />

## Decomposição da série temporal 
- **Original**: série temporal completa, com todos os componentes.
- **Tendência**: mostra a direção geral dos dados ao longo do tempo.
- **Sazonal**: variações que se repetem em intervalos regulares.
- **Aleatório**: flutuações imprevisíveis que não seguem padrão.
<img width="858" height="498" alt="image" src="https://github.com/user-attachments/assets/eae6b2e1-bee9-43aa-851c-64c7b480baf0" />

## Previsão usando ETS
O método ETS (Error, Trend, Seasonal) realiza previsões de séries temporais com base em modelos de suavização exponencial, que consideram três componentes: erro, tendência e sazonalidade.
<img width="838" height="472" alt="image" src="https://github.com/user-attachments/assets/b96bac9d-8cbf-4026-bfb6-79870861f93f" />

## Previsão usando ARIMA
O modelo ARIMA (AutoRegressive Integrated Moving Average) realiza previsões de séries temporais com base em três componentes: autorregressão (AR), integração (I) e média móvel (MA).
<img width="847" height="514" alt="image" src="https://github.com/user-attachments/assets/ae11a53f-f821-4da5-97de-64440e312a82" />

