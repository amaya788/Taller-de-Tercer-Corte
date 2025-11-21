# Taller de Tercer Corte

## Integrantes
1. **David Esteban Diaz Castro**
2. **Ferney Arturo Amaya Gómez** 
3. **Jhonny Alejandro Mejia**

---

## 1. Algoritmos de Inteligencia Artificial Heurística para Redes Industriales

### 1.1. Arquitecturas y Configuración

Se exponen arquitecturas basadas en algoritmos genéticos, colonias de hormigas y enfriamiento simulado para detección de errores y gestión de firewalls y routers en entornos industriales. Las configuraciones incluyen módulos de análisis de tráfico, sistemas de decisión basados en reglas heurísticas y mecanismos de aprendizaje automático adaptativo.

#### 1.1.1. Algoritmos Genéticos

<img width="415" height="298" alt="John Holland" src="https://github.com/user-attachments/assets/7dd11b11-d44c-4c43-838e-102028769ead" />

**Figura 1.** John Holland en 1962 - Pionero de los algoritmos genéticos

> *"Fue un pionero en el estudio de los sistemas adaptativos y sentó las bases para desarrollos posteriores en este campo. Su contribución más destacada fue ser el primero en proponer explícitamente el uso del cruzamiento y otros operadores de recombinación, elementos fundamentales en los algoritmos evolutivos modernos."*

#### 1.1.2. Colonias de Hormigas

Las hormigas se comunican a través de sus feromonas, las cuales son sustancias que les permiten encontrar los caminos más cortos entre su nido y la fuente de alimentos. Esta característica ha sido utilizada para la solución de problemas de optimización que necesiten mejorar sustancialmente los tiempos de cómputo para la solución de una aplicación específica [2].

Quien introdujo este algoritmo fue Marco Dorigo en los inicios de 1990, diseñado para la solución de problemas de optimización complejos.

<div style="display: flex; gap: 20px;">
  <img width="487" height="253" alt="Algoritmo colonia hormigas" src="https://github.com/user-attachments/assets/3299c86b-3c95-4993-9cb2-f7c3f0235c9e" />
  <img width="346" height="478" alt="Marco Dorigo" src="https://github.com/user-attachments/assets/4d40aacf-f495-403b-ae9a-6037209a8e97" />
</div>

**Figura 2.** Algoritmo de colonia de hormigas | **Figura 3.** Marco Dorigo

#### 1.1.3. Enfriamiento Simulado

También llamado temple simulado, recocido simulado, cristalización o enfriamiento simulado, es un algoritmo de búsqueda metaheurística para problemas de optimización global; el objetivo general de este tipo de algoritmos es encontrar una buena aproximación al **valor óptimo de una función en un espacio de búsqueda grande**.

<div style="display: flex; gap: 20px;">
  <img width="345" height="345" alt="Enfriamiento simulado 1" src="https://github.com/user-attachments/assets/3ee2ba90-1cba-47ec-b760-a67ab6315588" />
  <img width="342" height="342" alt="Enfriamiento simulado 2" src="https://github.com/user-attachments/assets/5a7e023b-5ac5-4ca4-80da-a5235b089c83" />
</div>

**Figura 4.** Ejemplo ilustrando la importancia del protocolo de enfriamiento

> *El problema consiste en disponer los píxeles en la imagen de tal manera que se minimice una función de energía potencial que causa que los colores similares se atraigan a distancias cortas y se repelan a distancias largas. [4]*

---

### 1.2. Industria IoT y Simbiosis con Ethernet

Se explora la integración IoT-Ethernet mediante gateways industriales, protocolos de comunicación unificados y arquitecturas de datos distribuidas. La simbiosis se manifiesta en la convergencia de tecnologías OT/IT y el manejo unificado de datos desde sensor hasta cloud.

<img width="838" height="471" alt="IoT Ethernet Gateways" src="https://github.com/user-attachments/assets/0a45a10f-5c14-421d-93a5-066203ff2897" />

**Figura 5.** Dispositivos IoT-Ethernet mediante gateways industriales

#### 1.2.1. Protocolos de Comunicación Unificados y Arquitecturas de Datos Distribuidas

**Tabla 1.** Clasificación de protocolos para integración IoT-Ethernet

| Categoría | Protocolos | Descripción Breve |
|-----------|------------|-------------------|
| **Protocolos Industriales sobre Ethernet** | EtherNet/IP | Basado en CIP; usado en automatización industrial |
|  | PROFINET | Comunicación rápida y determinista para PLC y maquinaria |
|  | Modbus TCP | Versión sobre Ethernet del clásico Modbus; muy usado por sensores y PLC |
|  | EtherCAT | Protocolo de alta velocidad para control en tiempo real |
|  | POWERLINK | Ethernet determinista para aplicaciones industriales exigentes |
|  | S7 Communication | Protocolo propietario de Siemens para PLC S7 |
| **Protocolos IoT que pasan por Gateways Ethernet** | MQTT / MQTT-SN | Publicación/suscripción de baja latencia, ideal para IoT |
|  | CoAP | Ligero, similar a HTTP, para dispositivos con recursos limitados |
|  | AMQP | Orientado a mensajería empresarial y telemetría |
|  | HTTP/HTTPS | Protocolo universal para intercambio de datos en IoT |
|  | WebSockets | Comunicación bidireccional en tiempo real |
| **Protocolos de Interoperabilidad Industrial** | OPC UA | Estándar universal para integración IoT + industria |
|  | DDS | Middleware distribuido para sistemas críticos en tiempo real |
|  | BACnet/IP | Usado en automatización de edificios e instalaciones |
| **Protocolos de Red y Seguridad** | IPv4/IPv6 | Base de direccionamiento para integración IoT-Ethernet |
|  | TLS/DTLS | Seguridad mediante cifrado en comunicaciones IoT/industriales |
|  | DNS / mDNS | Resolución de nombres en redes industriales e IoT |
|  | VLAN (802.1Q) | Segmentación de red para seguridad y control del tráfico |
|  | TSN | Extensión de Ethernet para garantizar tiempos deterministas |

---

### 1.3. Computación Cuántica en Comunicaciones Industriales

Se visualiza el entorno de computación cuántica aplicado a criptografía avanzada, optimización de redes complejas y simulación de sistemas industriales. Su adopción en el sector es incipiente, pero con potencial transformador a largo plazo.

#### 1.3.1. La Piedra Angular: Principio de Incertidumbre de Heisenberg

Supongamos entonces que tenemos un fotón que puede estar polarizado en una de cuatro direcciones distintas: vertical (|), horizontal (-), diagonal a la izquierda (\) o diagonal a la derecha (/). Estas cuatro polarizaciones forman dos bases ortogonales: por un lado, I y -, a la que llamaremos base (+), y por otro lado, /y , a la que llamaremos (x).

<img width="921" height="553" alt="Criptografía Cuántica" src="https://github.com/user-attachments/assets/619ef619-6d04-490f-bfd8-94ed8659d577" />

**Figura 6.** Ilustración de criptografía cuántica

Las computadoras cuánticas, al igual que las clásicas, están formadas por **hardware** y **software**, aunque su estructura interna es muy distinta debido a la naturaleza de los cúbits.

#### 1.3.2. Hardware Cuántico

El hardware de una computadora cuántica se organiza en tres planos fundamentales:

1. **Plano de Datos Cuánticos**
   - Es el corazón del sistema
   - Aquí se encuentran los **cúbits físicos**
   - Elementos encargados de estabilizarlos y mantener las condiciones necesarias

2. **Plano de Control y Medición**
   - Transforma **señales digitales clásicas** en **señales analógicas u ondas de control**
   - Permite ejecutar operaciones cuánticas sobre los cúbits
   - Realiza mediciones del estado cuántico

3. **Plano de Procesamiento de Control y Host**
   - Procesador de control ejecuta secuencia de instrucciones del algoritmo cuántico
   - Procesador host actúa como puente entre software cuántico y hardware
   - Envía instrucciones en forma de señales digitales hacia el sistema de control [7]

---

## 2. Propuesta: Sistema Inteligente para Redes Industriales

### 2.1. Funcionalidades del Sistema

- **Observación:** monitoreo del tráfico de red industrial (PROFINET, Ethernet/IP, OPC UA)
- **Detección:** identificación de anomalías y fallos mediante:
  - Reglas simples (heurísticas)
  - Modelo de IA para reconocimiento de patrones extraños
- **Toma de decisiones:** acciones automáticas que incluyen:
  - Priorización de tráfico importante
  - Bloqueo de tráfico sospechoso
  - Cambio de rutas o configuraciones para reducir congestión
- **Optimización:** uso de módulo cuántico simulado para mejorar decisiones
- **Notificación:** envío de alertas y registro de actividades

### 2.2. Proceso de Funcionamiento

1. **Captura:** el gateway industrial captura el tráfico
2. **Análisis:** detección y análisis de anomalías con IA
3. **Acción:** ejecución automática de medidas correctivas
4. **Optimización:** aplicación de algoritmo de Colonias de Hormigas mediante módulo cuántico simulado para optimización de rutas

### 2.3. Problemas Resueltos

1. Reducción de fallos en la comunicación industrial
2. Detección de ataques o tráfico anormal
3. Mantenimiento de operación de red bajo condiciones de congestión
4. Preparación para adopción de tecnologías cuánticas futuras

### 2.4. Resultados Esperados

- Prototipo funcional para análisis de red industrial en tiempo real
- Sistema de acciones automáticas para mejora de estabilidad y seguridad
- Módulo experimental cuántico para optimización avanzada

---

## 3. Análisis del Cuadro Mágico de Gartner

<img width="549" height="314" alt="Cuadrante Mágico Gartner" src="https://github.com/user-attachments/assets/0cef3f59-fe76-4548-bfa8-96d2417f6052" />

**Figura 7.** Cuadrante Mágico de Gartner

El **Cuadrante Mágico (Magic Quadrant)** es una metodología reconocida y utilizada como guía empresarial para la selección de proveedores tecnológicos.

### 3.1. Características del Cuadrante Mágico

- Publicación anual que sirve como guía para selección de soluciones tecnológicas
- Herramienta estratégica para proveedores para demostrar relevancia en el mercado
- Permite comparación rápida de empresas tecnológicas y seguimiento de su evolución [8]

### 3.2. Interpretación de los Cuadrantes

1. **Líderes**
   - Empresas con alto desempeño actual
   - Excelente preparación para el futuro
   - Capacidad de ejecución y visión claras

2. **Visionarios**
   - Ideas innovadoras y visión de mercado
   - Capacidad de ejecución en desarrollo
   - Potencial de crecimiento futuro

3. **Jugadores de Nicho**
   - Enfoque en áreas específicas del mercado
   - Competencia limitada a segmentos especializados
   - Capacidad de innovación focalizada

4. **Retadores**
   - Fortaleza operativa actual
   - Visión de mercado limitada
   - Enfoque en ejecución más que en innovación

La ubicación de cada producto en los cuatro cuadrantes permite obtener un análisis visual que facilita la comparación rápida de las principales soluciones tecnológicas del mercado [9].

---

## 4. Referencias Bibliográficas

1. *Cs.us.es*, 2025. https://www.cs.us.es/~fsancho/Blog/posts/Algoritmos_Geneticos.md.html (consultado Nov. 21, 2025).

2. Optimización por colonia de hormigas: aplicaciones y tendencias. file:///C:/Users/rapio/Downloads/manfred,+Art+09+Vol+6-N10-11%20(1).pdf

3. ETHW, "Marco Dorigo - Engineering and Technology History Wiki," *ETHW*, Feb. 04, 2016. https://ethw.org/Marco_Dorigo (consultado Nov. 21, 2025).

4. C. de, "Algoritmo de recocido simulado," Wikipedia.org, Jun. 19, 2005. https://es.wikipedia.org/wiki/Algoritmo_de_recocido_simulado (consultado Nov. 21, 2025).

5. C. Gonzalez and C. Gonzalez, "Gateway IoT Industrial para Industria 4.0," Anatronic S.A, Sep. 08, 2023. https://anatronic.com/gateway-iot-industrial-para-industria-4-0/ (consultado Nov. 21, 2025).

6. name=Verónica Fernández Mármol and name=Gonzalo Álvarez Marañón; email=gonzalo@pcw.idg.es, "Criptografía Cuántica," Medina.name, 2025. http://joaquin.medina.name/web2008/documentos/informatica/documentacion/seguridad/criptografia/CriptografiaCuantica/2010_04_02_CriptografiaCuantica.html (consultado Nov. 21, 2025).

7. "¿En qué consiste la computación cuántica? - Explicación sobre la computación cuántica - AWS," Amazon Web Services, Inc., 2022. https://aws.amazon.com/es/what-is/quantum-computing/ (consultado Nov. 21, 2025).

8. desarrollosidn, "¿Qué es el Cuadrante Mágico de Gartner? | LIS Data Solutions," LIS Data Solutions, May 02, 2021. https://www.lisdatasolutions.com/es/blog/que-es-el-cuadrante-magico-de-gartner/ (consultado Nov. 21, 2025).

9. Gartner, "Gartner Magic Quadrant & Critical Capabilities - IT Research," Gartner, 2024. https://www.gartner.com/en/research/magic-quadrant

---

<div align="center">
  


</div>
