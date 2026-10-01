# 🪙 clavebit.com - Calculadora de Claves Privadas Bitcoin y billetera jerárquica con frase semilla. Consolidación de Utxos. Rescatar una transacción atascada (RBF y CPFP). Generador de transacciones.
Una herramienta web minimalista, rápida y segura para calcular claves privadas de Bitcoin de forma local. Desarrollada exclusivamente con HTML, CSS y JavaScript puro, sin dependencias externas ni instaladores. Generador de billetera jerárquica HD (BIP39/BIP84). Además cuenta con dos de las herramientas más útiles para el uso del Bitcoin: consolidación de UTXOs y rescatar una transacción atascada (RBF y CPFP). Generador de transacciones.


## 🛡️ Principios de Seguridad (Trust No One)

En el mundo Bitcoin, la seguridad es lo primero. Esta herramienta ha sido diseñada bajo el principio de **cero confianza**:

*   **100% Client-Side:** Todo el cálculo criptográfico se realiza directamente en tu navegador web.
*   **Sin Servidor (No Backend):** Este proyecto no envía tus datos, entropía o claves generadas a ningún servidor externo. No hay bases de datos ni APIs ocultas.
*   **Código Auditable:** Al no utilizar herramientas de empaquetado (como Webpack o Vite) ni librerías de terceros (npm), cualquiera puede revisar las líneas de código de los archivos `.js` para verificar que no existen puertas traseras.
*   **Tag de CSP en el HTML** (Respaldo Local)
*   **Huellas SHA-256 de los archivos** 

- index.html: e45d17e555612c091c1692532ab4dfd7cab450d9c22176297abe66cfa131dae4
- instrucciones.pdf: e632fd790f8a21b5b5ddaf84d8058ddfa2cfb42b238ff4ebfc418b50e262a2d5
- radar.html: c6a3e65cba049f521ae55cae64bcab65c2d71cb2c0e837ab2a70b6a7fbbc84bb
- rbf.html: aaa093fb0cc1cc1ccc9919a871a3d588c06696193f7f287e737ba287cbbe719a
- transaccion.html: 4333fb3fed04e9f95d990c0aa637f34ec905abf7f03f1f22db93eea9529ee5b4
- billeterahd.html: a78a20311d723e79672b1e50703ec659e2cad2df959a1bfbc6c4a08449d51fc1

## 🔌 Uso Seguro en Modo Offline (Recomendado)

Para maximizar la seguridad y asegurarte de que nadie pueda interceptar tus claves, te recomendamos ejecutar esta herramienta en un entorno aislado de internet:

1.  **Entra en el navegador en modo incógnito**
2.  **Desconecta tu internet:** Apaga el Wi-Fi de tu ordenador o desconecta el cable de red.
3.  **Ejecuta de forma local:** La web funcionará perfectamente sin conexión a la red.

## 📄 Licencia y Descargo de Responsabilidad

Este proyecto está bajo la **Licencia MIT**. Consulta el archivo `LICENSE` para ver el texto legal completo.

⚠️ **DESCARGO DE RESPONSABILIDAD (DISCLAIMER):** clavebit.com se proporciona "tal cual", sin garantía de ningún tipo. El uso de claves privadas calculadas por software de terceros implica riesgos de pérdida de fondos si no se gestionan adecuadamente. El autor no se hace responsable de pérdidas financieras, hackeos o errores derivados del uso de esta herramienta.
