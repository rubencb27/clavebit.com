# 🪙 clavebit.com - Calculadora de Claves Privadas Bitcoin
Una herramienta web minimalista, rápida y segura para calcular claves privadas de Bitcoin de forma local. Desarrollada exclusivamente con HTML, CSS y JavaScript puro, sin dependencias externas ni instaladores.

## 🛡️ Principios de Seguridad (Trust No One)

En el mundo Bitcoin, la seguridad es lo primero. Esta herramienta ha sido diseñada bajo el principio de **cero confianza**:

*   **100% Client-Side:** Todo el cálculo criptográfico se realiza directamente en tu navegador web.
*   **Sin Servidor (No Backend):** Este proyecto no envía tus datos, entropía o claves generadas a ningún servidor externo. No hay bases de datos ni APIs ocultas.
*   **Código Auditable:** Al no utilizar herramientas de empaquetado (como Webpack o Vite) ni librerías de terceros (npm), cualquiera puede revisar las líneas de código de los archivos `.js` para verificar que no existen puertas traseras.
*   **Tag de CSP en el HTML** (Respaldo Local)
*   **Mecanismo de Destrucción de Memoria** (Wipe)
*   **No autocompletado:** solucionado fuga de Datos por caché de entrada

## 🔌 Uso Seguro en Modo Offline (Recomendado)

Para maximizar la seguridad y asegurarte de que nadie pueda interceptar tus claves, te recomendamos ejecutar esta herramienta en un entorno aislado de internet:

1.  **Entra en el navegador en modo incógnito**
2.  **Desconecta tu internet:** Apaga el Wi-Fi de tu ordenador o desconecta el cable de red.
3.  **Ejecuta de forma local:** La web funcionará perfectamente sin conexión a la red.

## 📄 Licencia y Descargo de Responsabilidad

Este proyecto está bajo la **Licencia MIT**. Consulta el archivo `LICENSE` para ver el texto legal completo.

⚠️ **DESCARGO DE RESPONSABILIDAD (DISCLAIMER):** clavebit.com se proporciona "tal cual", sin garantía de ningún tipo. El uso de claves privadas calculadas por software de terceros implica riesgos de pérdida de fondos si no se gestionan adecuadamente. El autor no se hace responsable de pérdidas financieras, hackeos o errores derivados del uso de esta herramienta.
