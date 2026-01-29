# Análisis de Tráfico y Diagnóstico de Red

> **Proyecto de Monitorización y Troubleshooting**

Este repositorio documenta técnicas de diagnóstico de red para identificar cuellos de botella, latencias y rutas de enrutamiento en infraestructuras corporativas.

## Herramientas y Protocolos Analizados
- **Tracert (Traceroute):** Análisis de saltos (hops) para detectar puntos de fallo en la comunicación con servidores externos (DNS Google / Proveedores ISP).
- **Protocolos de Transporte:** Estudio comparativo entre **TCP** (fiabilidad crítica para transferencia de archivos) y **UDP** (velocidad para streaming/VoIP).

## Caso Práctico: Traza de Rutas
Se analizó la latencia paso a paso desde la red local hasta el destino final, identificando los routers intermedios y tiempos de respuesta.

![Traza de Ruta](network-trace.png)
