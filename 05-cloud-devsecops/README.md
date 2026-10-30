# Fase 05 · Cloud Security y DevSecOps

Esta fase incorpora seguridad a los servicios cloud y a la cadena de entrega de software de AegisTech.

## Arquitectura

El diseño considera IAM, secretos, redes, cifrado y registros en proveedores cloud, junto con contenedores Docker/Kubernetes e infraestructura como código mediante Terraform.

Los pipelines de Jenkins o GitHub Actions integran análisis SAST, DAST y SCA, escaneo de imágenes, detección de secretos y trazabilidad de dependencias mediante SBOM.

## Controles

- Restricción de identidades y privilegios.
- Evaluación automatizada de código, dependencias e imágenes.
- Políticas de bloqueo ante condiciones críticas definidas.
- Conservación de evidencias de controles del pipeline.
- Integración de hallazgos con gestión de vulnerabilidades.

Los eventos de construcción, despliegue e infraestructura enriquecen el contexto del [SOC](../03-soc-blue-team/README.md).
