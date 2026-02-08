# 📊Sensibilidad Sectorial a Eventos de Dividendo

Impacto de Eventos en el Contexto Fundamental

## 📌Descripción del proyecto

Este proyecto analiza cómo distintos sectores reaccionan a un mismo tipo de evento corporativo, en este caso Dividendos, midiendo el gap de precio de apertura generado por el evento.

El objetivo es detectar sensibilidad diferencial: no todos los sectores interpretan ni descuentan los dividendos de la misma forma.

## 🧠Insight financiero

¿En qué sector el evento “Dividendo” genera el mayor gap promedio de precio entre el cierre previo y la apertura del día del evento?

Un gap elevado indica:
- mayor sorpresa del mercado
- ajustes abruptos de valoración
- mayor impacto en expectativas de cash-flow

## 💼Valor de negocio

📈 Identifica sectores más sensibles a políticas de retorno al accionista

🧭 Útil para estrategias event-driven

⚠️ Ayuda a anticipar volatilidad específica por sector

🌍 Facilita comparaciones estructurales entre industrias

Ideal para:
- traders de dividendos
- gestores de renta variable
- análisis de eficiencia del mercado

🗄️ Tablas utilizadas
- eventos_corporativos
- Tipo y fecha del evento (Dividendo)
- tickers
- Clasificación sectorial
- precios_diarios
- Precios de apertura y cierre

## ⚙️Metodología

1️⃣ Selección de eventos

Se filtran únicamente eventos corporativos de tipo Dividendo

2️⃣ Cálculo del gap de precio

Para cada evento:

- Se obtiene el cierre del día previo

- Se compara con la apertura del día del evento

Fórmula:

Gap (%) = (Apertura_evento – Cierre_previo) / Cierre_previo * 100

3️⃣ Agregación sectorial

- Los gaps individuales se promedian por sector
- Se excluyen observaciones sin cierre previo válido

4️⃣ Ranking final

- Los sectores se ordenan de mayor a menor gap promedio

## 📊Interpretación de resultados

- Gap promedio alto
- Mayor impacto del dividendo
- Posible ineficiencia o sorpresa
- Ajustes rápidos de precio
- Gap promedio bajo
- Evento esperado
- Dividendo ya descontado
- Mayor eficiencia informacional

## 🚀Posibles extensiones

- Segmentar por país de cotización
- Comparar dividendos ordinarios vs extraordinarios
- Analizar persistencia del movimiento post-evento
- Cruzar con volumen para validar convicción
- Ajustar por tamaño relativo del dividendo (yield)

## 🧩Conclusión

- Este proyecto demuestra que el impacto de un mismo evento fundamental no es homogéneo.
- Al analizar dividendos a nivel sectorial, se revelan patrones estructurales de sensibilidad que no son evidentes a simple vista.

Es análisis fundamental… con precisión cuantitativa.

## 👤Autora
Flavia Hepp Proyecto de SQL aplicó un análisis de riesgo basado en eventos.
