# OCI Master Suite - Plataforma de Evaluación y Apoyo de Exposición

Plataforma web interactiva desarrollada para la preparación, evaluación y soporte técnico en vivo para la exposición de Oracle Cloud Infrastructure (OCI) por un equipo de 5 participantes.

## 🚀 Cómo Ejecutar la Plataforma
Solo necesitas abrir el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Microsoft Edge, Mozilla Firefox o Safari):

- Ruta absoluta: `C:\Users\PC04\.gemini\antigravity\scratch\oci-master-platform\index.html`

O hacer doble clic en el archivo `index.html` desde el Explorador de Archivos de Windows.

## 📦 Módulos Incluidos

1. **📝 Evaluador de Conocimientos (Quiz de 10 Preguntas Técnicas):**
   - Preguntas de nivel Architect Associate / Professional sobre:
     * Arquitectura física: Regiones, Availability Domains y Fault Domains (FDs).
     * Modelos de Nube: Multicloud (Oracle Database@Azure), Híbrida (Exadata Cloud@Customer), Dedicated Region.
     * Cómputo Flexible: Formas E4/A1 desvinculando vCPUs y RAM.
     * Almacenamiento: OCI Block Volume con control de VPUs (0 a 120 VPUs/GB).
     * Autonomous Database: Pilares Self-Driving, Self-Securing y Self-Repairing.
     * Transferencia de Red: Primeros 10 TB de Egress gratuitos al mes.
     * Redes VCN: Subredes, Service Gateway y NSGs vs Security Lists.
     * Virtualización Off-box Gen 2 sobre SmartNICs.
   - Feedback inmediato con justificación técnica y panel de resultados finales.

2. **🖥️ Simulador Interactivo OCI CLI:**
   - Consola tipo Bash con resaltado de sintaxis JSON, navegación de historial con flechas `Arriba`/`Abajo` y botones de acceso rápido para demostración en vivo.
   - Comandos preconfigurados con salidas realistas:
     * `oci iam compartment list`
     * `oci compute instance launch`
     * `oci db autonomous-database create`
     * `oci os bucket create`
     * `oci network vcn list`
     * `oci ce cluster create` (OKE Kubernetes)
     * `help`, `whoami`, `clear`

3. **💰 Calculadora de Costes y TCO (OCI vs AWS / Azure):**
   - Sliders de vCPUs, RAM, Almacenamiento SSD (TB) y Tráfico de Salida (Egress TB).
   - Cálculo automático en tiempo real destacando los 10 TB gratis de salida mensual y el ahorro de hasta el 65%-80% frente a AWS y Azure.
   - Botones con escenarios típicos: Startup, Enterprise OLTP y Big Data.

4. **👥 Guía de Repaso para los 5 Integrantes (10 Diapositivas):**
   - **Integrante 1 (Diapositivas 1 y 2):** Fundamentos, Evolución Gen 2, Regiones, ADs y Fault Domains.
   - **Integrante 2 (Diapositivas 3 y 4):** Modelos Multicloud (Database@Azure), Nube Híbrida y Dedicated Region.
   - **Integrante 3 (Diapositivas 5 y 6):** Cómputo Flexible, Networking VCN/NSG y Block Volume elástico con VPUs.
   - **Integrante 4 (Diapositivas 7 y 8):** Autonomous Database (ATP/ADW), Clusters OKE Kubernetes y Plataforma IA.
   - **Integrante 5 (Diapositivas 9 y 10):** Ingeniería de Costes, Egress gratuito, Gobernanza (Compartments/IAM) y Conclusión.
   - Incluye cronómetro de ensayo de 4 minutos por integrante y botón de "Simular Pregunta del Jurado".

5. **📋 Arquitectura Nuclear:**
   - Resumen conceptual rápido con tarjetas explicativas y datos clave para responder al jurado.
