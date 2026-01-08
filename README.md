# 📊 Standalone Mermaid Editor

Una solución local y privada para la creación, recolección y gestión de diagramas de flujo utilizando **Mermaid.js**, eliminando la dependencia de herramientas SaaS y restricciones de suscripción.

## 🚀 Motivación

Este proyecto nace de la necesidad de tener un entorno de diagramación robusto sin las limitaciones comunes de las plataformas web actuales:
* **Sin suscripciones:** Olvídate de muros de pago para funciones básicas.
* **Sin límites de prueba:** Crea tantos diagramas como necesites, para siempre.
* **Privacidad Total:** Los datos y flujos permanecen en tu máquina local, no en servidores de terceros.
* **Modo Offline:** Diseña y visualiza tus flujos sin necesidad de conexión a internet.

## 🛠️ Características

* **Sintaxis Mermaid:** Aprovecha la potencia y simplicidad de "Diagrams as Code".
* **Almacenamiento Local:** Organización de archivos `.mmd` o `.mermaid` directamente en tu sistema de archivos.
* **Exportación Libre:** Genera versiones como standalone webpage

## 📋 Uso Básico

Para crear un nuevo diagrama, simplemente define el bloque de código:

ejemplo:  
graph TD  
    A[Inicio] --> B{Local?}  
    B -- Sí --> C[Libertad Total]  
    B -- No --> D[Restricciones SaaS]  
    C --> E[Fin]  

```mermaid
graph TD
    A[Inicio] --> B{Local?}
    B -- Sí --> C[Libertad Total]
    B -- No --> D[Restricciones SaaS]
    C --> E[Fin]
