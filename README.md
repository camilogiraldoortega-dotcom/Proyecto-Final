README - TALLER FINAL
=====================================

¿QUÉ HACE ESTE CÓDIGO?
Ayuda a armar un portafolio de acciones óptimo.
Tú pones los tickers, él:
- Baja precios de 5 años (Yahoo Finance)
- Calcula retorno, riesgo, beta, VaR
- Usa Black-Litterman para ajustar expectativas
- Optimiza pesos (máximo Sharpe)
- Genera frontera eficiente
- Hace Monte Carlo (10.000 futuros)
- Muestra todo con gráficos

CÓMO USARLO
1. Ejecuta en Colab
2. Te pide tickers uno por uno → escribe 'done' al final
3. Espera... y listo!

EJEMPLO:
[1/30]: NVDA
[2/30]: BABA
[3/30]: OXY
[4/30]: done

SALIDA
- Resumen en consola con pesos óptimos
- Gráfico interactivo (frontera eficiente)
- grafico_pesos.png/pdf (pastel bonito)
- montecarlo.png/pdf (simulación de riesgo)

NOTAS
- Máx 30 tickers
- Usa tasa libre riesgo = 1%
